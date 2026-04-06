# LINKLOAD

## Tactical Web Security Reconnaissance Platform

<div align="center">

```
   
                                                     
▄▄▄                       ▄▄▄                     ▄▄ 
███      ▀▀        ▄▄     ███                     ██ 
███      ██  ████▄ ██ ▄█▀ ███      ▄███▄  ▀▀█▄ ▄████ 
███      ██  ██ ██ ████   ███      ██ ██ ▄█▀██ ██ ██ 
████████ ██▄ ██ ██ ██ ▀█▄ ████████ ▀███▀ ▀█▄██ ▀████ 
                                                                       
                                                                                 
[ CYBER RECONNAISSANCE & THREAT ANALYSIS SYSTEM ]
```

</div>

[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-yellow.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-blue.svg)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18+-cyan.svg)](https://react.dev/)
[![Docker](https://img.shields.io/badge/Docker-Ready-blue.svg)](https://www.docker.com/)
[![Status](https://img.shields.io/badge/Status-OPERATIONAL-brightgreen.svg)]()
[![Tests](https://img.shields.io/badge/Tests-40+-brightgreen.svg)]()

---

## Mission Brief

Security teams rarely lose because they lack tools.
They lose because noise arrives faster than signal.

LinkLoad is built as a tactical command platform for web reconnaissance. It coordinates scanner units, fuses findings with intelligence, maps risk to MITRE ATT&CK, and delivers one operational picture through a single gateway.

If your team needs fast detection and clear prioritization under pressure, this stack is designed for that exact battlefield.

---

## Theater Status 

- [ACTIVE] Web reconnaissance operations in production workflows.
- [ACTIVE] Identity service split out and routed through BFF.
- [ACTIVE] Scanner orchestrator + sidecar scanner fleet.
- [ACTIVE] Async enrichment and intelligence processing via Redis.
- [ACTIVE/OPTIONAL] Full observability stack with Prometheus, Loki, and Grafana.
- [IN PROGRESS] ML lane is deployed and evolving as models mature.

---

## Operational Objectives

1. Launch scanners in parallel and reduce mission time.
2. Keep frontend simple: one gateway, one contract.
3. Preserve data integrity with a single-writer Core model.
4. Provide live mission feedback with WebSocket notifications and polling fallback.
5. Keep deployment repeatable with Docker Compose and service isolation.

---

## Command Topology

```
                    ┌──────────────────────────┐
                    │        Frontend          │
                    │   React Dashboard:3000   │
                    └─────────────┬────────────┘
                            │ REST + WS
                    ┌─────────────▼────────────┐
                    │      LinkLoad-BFF        │
                    │       Gateway:5000       │
                    └──────┬─────────┬─────────┘
                        │         │
           ┌─────────────────────▼───┐ ┌───▼────────────────────┐
           │   Sync Service Plane    │ │   Scanner Sidecars      │
           │ Identity | Scanner |    │ │ ZAP | Nuclei | Wapiti  │
           │ Core (Single Writer)    │ │ | Nikto                 │
           └───────────────┬─────────┘ └───────────┬────────────┘
                     │                       │
                     └──────────┬────────────┘
                          │
                     ┌───────▼────────┐
                     │  Redis Events  │
                     └───┬─────────┬──┘
                         │         │
                ┌──────────────▼───┐ ┌──▼───────────────┐
                │   Enrichment      │ │ Intelligence      │
                │ (Threat Context)  │ │ (Risk + MITRE +   │
                │                   │ │ Cost-Benefit)     │
                └──────────────┬────┘ └──────┬───────────┘
                         │             │
                         └──────┬──────┘
                             │
                         ┌──────▼───────┐
                         │      ML      │
                         └──────┬───────┘
                             │
                         ┌──────▼───────┐
                         │ PostgreSQL / │
                         │ Supabase DB  │
                         └──────────────┘
```

### Rules of the Battlespace

- Frontend talks only to BFF at http://localhost:5000.
- BFF routes auth to Identity and scan write/read paths to Scanner/Core.
- Redis carries cross-service event traffic.
- Core remains the authoritative persistence coordinator.

---

## Unit Roster

| Unit | Location | Tactical Role | Host Port |
|------|----------|---------------|-----------|
| Frontend | linkload-frontend | Mission dashboard | 3000 |
| BFF | linkload-bff | API gateway, policy, WS notifications | 5000 |
| Identity | linkload-identity | Authentication and account controls | Internal |
| Scanner Orchestrator | linkload-scanner/orchestrator | Fan-out scan command | Internal |
| ZAP | compose image | Active web app scanner | 8080 |
| Nuclei/Wapiti/Nikto | linkload-scanner/*-svc | Scanner sidecar APIs | Internal |
| Core | linkload-core | Result assembly and data write path | Internal |
| Enrichment | linkload-enrichment | Threat context augmentation | Internal |
| Intelligence | linkload-intelligence | Risk and MITRE analysis | Internal |
| ML | linkload-ml | ML post-processing lane | Internal |
| Redis | compose-managed | Event bus and cache | Internal |

---

## Mission Flow

1. Operator starts a scan from the frontend.
2. BFF forwards command traffic to the Scanner orchestrator.
3. Scanner fan-outs to ZAP, Nuclei, Wapiti, and Nikto.
4. Progress and completion events are published to Redis.
5. Enrichment and Intelligence consume events and add context.
6. ML lane can consume downstream events for advanced inference.
7. Core assembles normalized results and persists records.
8. Frontend receives updates through polling and optional WS notifications.

---

## Deployment Playbook

### Prerequisites

- Docker Engine 20.10+
- Docker Compose v2+
- Supabase project and credentials
- Optional AI provider keys for enrichment/intelligence

### Step 1: Clone

```bash
git clone https://github.com/pratiyk/Link-Load.git
cd Link-Load
```

### Step 2: Stage Environment Files

Minimum files:

- linkload-devops/.env
- linkload-core/.env

Reference templates:

- linkload-core/.env.example
- linkload-bff/.env.example
- linkload-frontend/.env.example
- linkload-identity/.env.example

Critical values:

- DATABASE_URL
- SUPABASE_URL
- SUPABASE_KEY
- SUPABASE_SERVICE_KEY
- SUPABASE_JWT_SECRET
- SECRET_KEY
- REACT_APP_SUPABASE_URL
- REACT_APP_SUPABASE_ANON_KEY

### Step 3: Launch Stack

```bash
cd linkload-devops
docker compose up -d --build
```

### Step 4: Confirm Service Readiness

- Frontend: http://localhost:3000
- BFF root: http://localhost:5000/
- BFF liveness: http://localhost:5000/health/live

```bash
cd linkload-devops
docker compose ps
```

---

## Live Telemetry Stack (Optional)

Run the observability package independently:

```bash
cd monitoring-service
docker compose up -d
```

Operational endpoints:

- Grafana: http://localhost:3030
- Prometheus: http://localhost:9090
- Loki: http://localhost:3100
- cAdvisor: http://localhost:8081

Note: monitoring-service expects the external network linkload_linkload-network created by the main stack.

---

## Frontend Runtime Injection

Frontend Supabase public settings are injected at container startup.

- linkload-frontend/docker-entrypoint.sh generates runtime-config.js.
- Browser reads window.__RUNTIME_CONFIG__ via src/config/runtimeConfig.js.
- Entry script blocks accidental service-role key exposure in frontend env.

This keeps public config flexible without rebuilding images for every env change.

---

## Real-Time Command Channel

BFF exposes notification WebSocket routes:

- /ws/scans/{scan_id}
- /ws/scans/{scan_id}/progress
- /ws/scans/{scan_id}/events

Progress and results are always available through polling-safe endpoints:

- /api/v1/scans/comprehensive/{scan_id}/status
- /api/v1/scans/comprehensive/{scan_id}/result

---

## Shared Signal Protocol

shared_events defines cross-service event contracts.

- Docker services mount it read-only and use PYTHONPATH=/workspace:/app.
- Local dev mode:

```bash
pip install -e ../shared_events
```

---

## Repository Battalions

- linkload-bff: gateway and API policy layer
- linkload-core: persistence and aggregation command center
- linkload-identity: identity and access control service
- linkload-scanner: orchestrator and scanner sidecars
- linkload-enrichment: async intelligence enrichment
- linkload-intelligence: risk and MITRE analysis
- linkload-ml: machine learning service lane
- linkload-frontend: operator dashboard
- linkload-devops: primary compose and runtime wiring
- monitoring-service: metrics, logs, dashboards
- shared_events: event models and bus utilities
- linkload-docs: architecture and implementation guides

---

## Training Drills

```bash
# Core tests
cd linkload-core
pytest

# Frontend tests
cd ../linkload-frontend
npm test -- --watchAll=false

# Shared events tests
cd ../shared_events
pytest
```

---

## Security and Rules of Engagement

- Scan only targets you own or are formally authorized to assess.
- Never expose private secrets through frontend variables.
- Use hardened secrets, strict CORS, and TLS for non-dev environments.
- Keep Supabase RLS policies enabled and reviewed.

---

## Field Manuals

- Platform architecture and deep dives: linkload-docs/
- Core API and technical references: linkload-core/docs/
- Service-level notes: each service folder README and docs

---

## License

Released under the MIT License.

## Credits

Architected by Prateek Shrivastava ([@pratiyk](https://github.com/pratiyk))
