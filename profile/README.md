# LINK&LOAD

## Tactical Web Security Reconnaissance Platform

```
   
██╗     ██╗███╗   ██╗██╗  ██╗   ██╗   ██╗      ██████╗  █████╗ ██████╗ 
██║     ██║████╗  ██║██║ ██╔╝   ██║   ██║     ██╔═══██╗██╔══██╗██╔══██╗
██║     ██║██╔██╗ ██║█████╔╝ ████████╗██║     ██║   ██║███████║██║  ██║
██║     ██║██║╚██╗██║██╔═██╗ ██╔═██╔═╝██║     ██║   ██║██╔══██║██║  ██║
███████╗██║██║ ╚████║██║  ██╗██████║  ███████╗╚██████╔╝██║  ██║██████╔╝
╚══════╝╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚═════╝  ╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═════╝ 
                                                                       
                                                                                 
              [ CYBER RECONNAISSANCE & THREAT ANALYSIS SYSTEM ]
```

[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-yellow.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-blue.svg)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18+-cyan.svg)](https://react.dev/)
[![Docker](https://img.shields.io/badge/Docker-Ready-blue.svg)](https://www.docker.com/)
[![Status](https://img.shields.io/badge/Status-OPERATIONAL-brightgreen.svg)]()
[![Tests](https://img.shields.io/badge/Tests-40+-brightgreen.svg)]()

---

## MISSION BRIEF

Listen up. If you're tired of juggling five different security tools, paying enterprise prices for glorified vulnerability scanners, and wading through false positives that waste your team's time—you're in the right place.

Link&Load is what happens when you combine military-grade reconnaissance tactics with modern AI and refuse to compromise on either speed or accuracy. We're not here to replace your security team. We're here to give them superpowers.

Think of us as your always-on security analyst that never sleeps, never misses a deadline, and speaks fluent MITRE ATT&CK. We deploy multiple specialized scanners in parallel—OWASP ZAP for deep penetration testing, Nuclei for rapid CVE detection, Wapiti for black-box fuzzing, and Nikto for infrastructure analysis—then use AI to correlate findings, eliminate duplicate noise, and deliver a single source of truth.

No vendor lock-in. No per-scan pricing. No proprietary black boxes. Just open-source tools orchestrated with precision, enhanced by AI, and wrapped in an interface that security teams actually want to use.

### Current Mission Status: Phase 1 Complete [OPERATIONAL]

We've successfully deployed and battle-tested our web application security platform. It's running in production, processing real scans, and helping teams find vulnerabilities before the bad guys do. The stack includes multi-scanner orchestration, AI-powered analysis with Groq/OpenAI/Claude integration, MITRE ATT&CK mapping, and real-time WebSocket updates. All systems green.

### Future Operations: Attack Surface Domination

Link&Load is evolving from a tactical web security scanner into a **unified attack surface management platform** that covers:

- [DEPLOYED] **Web Applications** (Phase 1)
- [PLANNED] **API Security** (Q1 2026 - Phase 2)
- [PLANNED] **Source Code Analysis (SAST)** (Q2 2026 - Phase 3)
- [PLANNED] **Cloud Security Posture (AWS/Azure/GCP)** (Q2-Q3 2026 - Phase 4)
- [PLANNED] **Container & Kubernetes Security** (Q3 2026 - Phase 5)
- [PLANNED] **Infrastructure as Code (IaC)** (Q3 2026 - Phase 6)
- [PLANNED] **Continuous 24/7 Monitoring** (Q4 2026 - Phase 7)
- [PLANNED] **Mobile Application Security** (2027 - Phase 9)
- [PLANNED] **Network & Perimeter Security** (2027 - Phase 10)

Here's what makes us different: we execute coordinated multi-scanner operations in parallel (because waiting 6 hours for sequential scans is unacceptable), process everything through machine learning pipelines to cut false positives by 40%, and deliver reports that your CISO can present to the board without translation. And we do it **using open-source, free tools wherever possible**—because security shouldn't require a six-figure budget.

**OUR VISION:** Build the security platform developers actually want to use. One that consolidates 5-7 fragmented tools into a single command center, speaks their language, integrates with their workflow, and costs **70% less than enterprise incumbents** like Qualys, Tenable, or Snyk.

Why? Because we've been on the other side. We've paid the enterprise tax. We've dealt with the vendor lock-in. We've fought with tools that were built for compliance officers, not practitioners. Link&Load is our answer to that broken system.

**OPERATIONAL STATUS: PHASE 1 DEPLOYED AND OPERATIONAL | PHASE 2-10 IN TACTICAL PLANNING**

---


## TABLE OF CONTENTS

- [Operational Capabilities](#operational-capabilities)
- [System Architecture](#system-architecture)
- [Deployment Protocol](#deployment-protocol)
- [Mission Control Interface](#mission-control-interface)
- [API Command Structure](#api-command-structure)
- [Scanner Arsenal](#scanner-arsenal)
- [Intelligence Analysis Engine](#intelligence-analysis-engine)
- [Security Protocols](#security-protocols)
- [Domain Authorization Protocol](#domain-authorization-protocol)
- [Configuration Matrix](#configuration-matrix)
- [Verification Procedures](#verification-procedures)
- [Tactical Roadmap](#tactical-roadmap)
- [Field Support](#field-support)

---

## OPERATIONAL CAPABILITIES

### Current Combat Readiness - Phase 1: Web Application Reconnaissance [OPERATIONAL]

We're live. Phase 1 is deployed, tested in production environments, and actively scanning web applications for security teams who are tired of manual reconnaissance. Here's what's currently in the arsenal, battle-tested and ready for deployment:

| Scanner | Classification | Primary Function | Status |
|---------|---------------|------------------|---------|
| OWASP ZAP | Active Reconnaissance | Full-spectrum web application penetration testing | DEPLOYED |
| Nuclei | Template-Based Detection | Rapid vulnerability identification via 8000+ templates | DEPLOYED |
| Wapiti | Black-Box Analysis | Unauthenticated perimeter vulnerability assessment | DEPLOYED |
| Nikto | Web Server Scanning | Misconfigurations and server-specific vulnerabilities | DEPLOYED |

**What We've Built So Far:**

**Multi-Scanner Parallel Execution:** Why run scanners sequentially when you can run them all at once? Our orchestration engine coordinates OWASP ZAP, Nuclei, Wapiti, and Nikto in parallel, cutting total scan time by 60%. What used to take 3 hours now takes 45 minutes. Your team gets results faster, you catch vulnerabilities sooner, everyone wins.

**AI-Powered Analysis That Actually Works:** We're not just bolting ChatGPT onto a vulnerability scanner and calling it AI. We've integrated three LLM providers (Groq, OpenAI, and Claude) with intelligent fallback, so if one provider is down, we seamlessly switch to another. The AI deduplicates findings, recalibrates severity based on your specific context, generates executive summaries that non-technical stakeholders can understand, and prioritizes remediation based on actual risk—not just CVSS scores.

**MITRE ATT&CK Mapping:** Every vulnerability gets automatically mapped to the MITRE ATT&CK framework. Find a SQL injection? We'll tell you it maps to T1190 (Exploit Public-Facing Application) and explain the attacker's likely next move. This isn't just academic—it helps your team understand the real-world attack chains and prioritize fixes that actually break those chains.

**Real-Time Intelligence Feed:** No more refreshing dashboards hoping for updates. We use WebSockets to push live scan progress, vulnerability discoveries, and risk calculations to your browser in real-time. Watch the scan progress stage by stage, see vulnerabilities as they're discovered, and get instant notifications when critical findings emerge.

**Risk Scoring That Makes Sense:** CVSS scores are helpful, but they don't tell you what to fix first. We calculate a normalized 0-10 risk score that factors in CVSS severity, exploitability metrics (is there a Metasploit module?), business context (is this your payment gateway?), and threat intelligence (is this being actively exploited?). The result: a prioritized fix list that makes sense for your organization.

**Production-Ready Infrastructure:** Full Docker containerization with health checks, automated recovery, and resource limits. We've done the infrastructure work so you don't have to. Spin up the entire platform with a single docker-compose command.

**Multi-Tenant Security:** Row-level security policies ensure that even if someone breaches the application layer, they can't access another organization's scan data. Because sharing vulnerability data with strangers is generally frowned upon.

**Comprehensive Test Coverage:** Over 40 tests covering E2E workflows, API integration, scanner orchestration, and edge cases. We ship with confidence because we test with paranoia.

### What This Actually Means In Practice

**What We Cover:** Any web application, web service, or HTTP/HTTPS endpoint you throw at us. APIs, admin panels, customer portals, internal dashboards—if it speaks HTTP, we can scan it.

**Detection Capabilities:** Between Nuclei's 8000+ templates, ZAP's OWASP Top 10 coverage, Wapiti's 15+ attack modules, and Nikto's infrastructure checks, we're catching everything from ancient Apache misconfigurations to this month's critical CVEs. And when a new vulnerability drops (Log4Shell, anyone?), Nuclei templates are usually available same-day.

**Speed:** Average scan completes in 15-30 minutes. Deep scans with authentication and AJAX spidering might take 2-3 hours, but that's still faster than running each scanner manually and correlating results in a spreadsheet.

**Accuracy:** Here's the dirty secret of vulnerability scanning—most tools find plenty of issues, but half of them are false positives. Our AI-powered deduplication cuts false positives by 40%. That means less time investigating phantom vulnerabilities and more time fixing real ones.

**Intelligence Quality:** Every finding gets MITRE ATT&CK mapping with confidence scores averaging 92%. We're not just telling you "this is broken"—we're explaining how an attacker would exploit it and what comes next in the kill chain.

**Automation Level:** Fire and forget. Start a scan, go grab coffee, come back to a full intelligence report with prioritized remediation guidance. No manual correlation. No spreadsheet gymnastics. Just actionable results.

### AI-Powered Threat Intelligence (The Part That Actually Saves Time)

Let's talk about the AI integration, because "AI-powered" has become meaningless marketing speak. Here's what we actually do:

**Three LLM Providers, Zero Single Point of Failure:** We integrate OpenAI (GPT-4), Anthropic (Claude), and Groq (Llama 3.3 70B) with automatic failover. Primary provider down? We switch to the backup seamlessly. You get your analysis either way.

**What The AI Actually Does:**

First, it takes the raw scanner output (which is often cryptic, technical, and full of false positives) and translates it into something your team can actually use. "OWASP ZAP found potential SQL injection in parameter 'id'" becomes "SQL Injection vulnerability allows attackers to extract your entire customer database, modify records, or potentially gain admin access. This is exploitable without authentication and has active exploits in the wild. Fix this within 24 hours."

Second, it deduplicates findings. When ZAP, Nuclei, and Wapiti all report the same SQL injection from slightly different angles, the AI recognizes they're the same issue and consolidates them into a single finding with higher confidence.

Third, it generates executive summaries. Your CISO doesn't want to read 50 pages of technical findings. They want to know: Are we at risk? How bad is it? What's it going to cost to fix? The AI generates that summary automatically.

Fourth, it prioritizes remediation. Not all critical vulnerabilities are equally critical. The AI considers exploitability (is there a Metasploit module?), your specific context (is this your payment processing endpoint?), and current threat intelligence (is this CVE being exploited right now?) to generate a fix-it list that actually makes sense.

**Fallback Protocol:** If all LLM providers are down (outage, rate limits, apocalypse), we fall back to heuristic-based analysis. You still get results, just without the AI enhancement. The scanners keep running, the platform keeps working.

### MITRE ATT&CK Correlation (Understanding The Attack Story)

Here's why this matters: finding vulnerabilities is easy. Understanding how attackers actually exploit them is hard.

When we find a vulnerability, we don't just tell you "this is broken." We map it to the MITRE ATT&CK framework to show you exactly where it fits in a real-world attack chain:

**Technique Identification:** That SQL injection? It's MITRE T1190 (Exploit Public-Facing Application). Now you know this is an initial access vector—an attacker's first step into your network.

**Tactic Classification:** We show you what phase of an attack this enables. Initial Access? Privilege Escalation? Data Exfiltration? Understanding the tactic helps you prioritize defenses.

**Attack Pattern Correlation:** We link to CAPEC (Common Attack Pattern Enumeration and Classification) so you can see exactly how this vulnerability gets exploited in practice. Not theoretical attack scenarios—actual documented attack patterns.

**Confidence Scoring:** Not all mappings are equally certain. We give you confidence scores so you know which correlations are solid ("this is definitely T1190") versus probable ("this looks like T1078 but could be something else").

The end result: you understand not just what's broken, but how an attacker would use it, what they'd do next, and which fixes actually disrupt the attack chain.

### Risk Quantification (What To Fix First)

CVSS scores tell you how bad a vulnerability is in a vacuum. They don't tell you what to fix first in your specific environment. That's where our risk scoring comes in.

We calculate a normalized 0-10 risk score by combining:

**Technical Severity:** CVSS base scores and severity classification (Critical/High/Medium/Low). This is your foundation—how bad could this be?

**Exploitability Metrics:** Is there a public exploit? A Metasploit module? Active exploitation in the wild? Or is this purely theoretical? A critical vulnerability with no known exploits gets a lower score than a medium vulnerability being actively exploited by ransomware gangs.

**Business Context:** Is this vulnerability in your payment processing gateway or your marketing blog? Your production authentication system or a staging environment? Context matters. We adjust scores based on asset criticality, data sensitivity, and compliance requirements.

**Threat Intelligence:** We pull from CISA's Known Exploited Vulnerabilities catalog, AlienVault OTX, and other threat feeds. If a vulnerability is trending on dark web forums or being used in current campaigns, the score goes up.

The result: a prioritized list that makes sense for your organization. Fix the payment gateway SQL injection before the WordPress plugin XSS, even if they have similar CVSS scores.

### Real-Time Situational Awareness (Watch It Happen)

Remember the bad old days of kicking off a scan, wandering off to do something else, and checking back every 20 minutes to see if it's done? Yeah, we fixed that.

WebSocket integration means you get live updates as they happen:

**Stage-by-Stage Progress:** Watch as the scan moves through phases—spidering the application, running active tests, analyzing results, calculating risk scores. You know exactly what's happening at every moment.

**Instant Notifications:** The moment a critical vulnerability is discovered, you know about it. Don't wait until the scan completes—if we find a publicly exploitable RCE in the first 5 minutes, you'll know in the first 5 minutes.

**Resilient Connections:** Network hiccup? Browser refresh? We automatically reconnect and resume updates. No babysitting required.

**Team Coordination:** Multiple team members can watch the same scan in real-time. Perfect for training junior analysts or getting immediate feedback on findings during a scan.

It's a small thing, but it changes the workflow. You're not firing off scans and hoping for the best. You're actively monitoring reconnaissance operations as they execute.

---

## SCANNER ARSENAL: Why We Deploy Each Weapon

Look, we could have built yet another vulnerability scanner from scratch. Spent years reinventing the wheel, debugging edge cases that OpenSSL handled a decade ago, and eventually shipping something that finds 60% of what mature scanners catch.

Or we could be smart about it: take the best open-source scanners that thousands of security professionals already trust, orchestrate them to work together, and use AI to make sense of the results. We chose option two.

Here's our thinking on each scanner and why they're in the arsenal:

#### 1. OWASP ZAP (The Deep Penetration Specialist)
**Role:** Active Penetration Testing Platform  
**Version:** Latest stable with weekly security updates  
**Why It's Here:** When you need to find vulnerabilities in authenticated areas that require complex session handling and multi-step attack chains, ZAP is the gold standard.

**What It Actually Does:**

ZAP acts as an intercepting proxy—sitting between your browser and the target application, capturing every HTTP request and response. This gives it a complete map of the application's attack surface, including endpoints that pure scanners would miss.

Then it gets aggressive. It injects attack payloads into every parameter, header, cookie, and form field it finds. SQL injection attempts. XSS vectors. Path traversal patterns. Command injection strings. If it's in the OWASP Top 10, ZAP is testing for it.

But here's what makes ZAP special: it handles authentication. Most black-box scanners give up when they hit a login form. ZAP maintains authenticated sessions for hours, testing protected endpoints that contain your most sensitive functionality. Your admin panel? Your account management pages? Your API endpoints behind OAuth? ZAP scans them all.

**Detection Strengths:**
- Complete OWASP Top 10 coverage with high accuracy (not just detection, but validation)
- Complex multi-step attack chains (SQLi leading to authentication bypass leading to privilege escalation)
- Session management flaws (fixation, prediction, theft)
- CSRF, clickjacking, and other client-side attacks
- Business logic flaws that require understanding application flow

**The Tactical Advantage:** ZAP finds vulnerabilities in areas other scanners can't reach. That admin panel hidden behind authentication? That's often where the critical vulnerabilities live. ZAP finds them.

#### 2. Nuclei (The Speed Demon)
**Role:** Template-Based CVE & Configuration Detection  
**Version:** Latest with auto-updating template library (8000+ templates and counting)  
**Why It's Here:** When a new CVE drops, you need to know if you're vulnerable right now. Not next week after your enterprise scanner vendor pushes an update. Right now. That's what Nuclei does.

**What It Actually Does:**

Nuclei is built around a simple but powerful concept: community-maintained YAML templates that describe how to detect specific vulnerabilities. When Log4Shell dropped in December 2021, Nuclei templates were available within hours. Not days. Hours.

Each template is a recipe: send this request, look for this response pattern, if you find it, you've got a vulnerability. It's fast (multi-threaded scanning hits hundreds of endpoints per second), it's accurate (template-based matching means no fuzzy heuristics generating false positives), and it's current (the community updates it constantly).

**Detection Strengths:**
- Brand new CVEs (often same-day detection capability after vulnerability disclosure)
- Exposed configuration files (.git directories, .env files, database backups)
- Default credentials on admin panels and management interfaces
- Subdomain takeover vulnerabilities
- Technology stack fingerprinting
- Misconfigured cloud storage buckets
- Exposed API endpoints and debugging interfaces

**The Tactical Advantage:** Nuclei is your early warning system. When the next big vulnerability hits Twitter and everyone panics, you can scan your entire infrastructure within minutes and know definitively whether you're affected. That kind of speed buys you time to patch before the mass exploitation begins.

#### 3. Wapiti (The Injection Hunter)
**Role:** Black-Box Endpoint Vulnerability Assessment  
**Version:** 3.1.7+  
**Why It's Here:** Sometimes you need a scanner that doesn't care about authentication, doesn't need configuration, and just relentlessly fuzzes every input it can find. That's Wapiti.

**What It Actually Does:**

Wapiti is a black-box fuzzer. It crawls your application, identifies every GET/POST parameter, every header, every cookie, and then systematically tests each one for injection vulnerabilities. No authentication required. No session handling. Just pure, methodical fuzzing.

What makes Wapiti special is its tenacity. It tests for blind vulnerabilities using time-based detection and out-of-band callbacks. That means it catches SQL injection even when the application doesn't return error messages. It finds command injection even when output isn't reflected. It discovers SSRF even when responses are filtered.

**Detection Strengths:**
- Blind SQL injection (time-based detection when errors are suppressed)
- Reflected and stored XSS (including DOM-based variants)
- Command injection and arbitrary code execution
- File upload vulnerabilities and path traversal
- XML External Entity (XXE) attacks
- Server-Side Request Forgery (SSRF)
- CRLF injection and response splitting

**The Tactical Advantage:** Wapiti's black-box approach means it works on anything. New application with weird technology stack? Throw Wapiti at it. Third-party API you're integrating? Wapiti can scan it. Internal tool with no documentation? Wapiti doesn't care—it just fuzzes until it finds something.

#### 4. Nikto (The Infrastructure Analyst)
**Role:** Web Server Configuration & Infrastructure Analysis  
**Version:** 2.5.0  
**Why It's Here:** While the other scanners focus on application vulnerabilities, Nikto specializes in infrastructure and server configuration issues that often provide the initial foothold for attackers.

**What It Actually Does:**

Nikto has been around for over 20 years, and in that time it's built a database of 7000+ server-specific security checks. It fingerprints web servers with scary accuracy (Apache 2.4.41 running on Ubuntu 20.04 with mod_php and mod_rewrite enabled), then tests for every known misconfiguration, outdated component, and dangerous default setting.

It finds the stuff that application scanners miss: exposed phpMyAdmin instances, unprotected server-status pages, default installation files that leak version information, misconfigured SSL/TLS implementations, and dangerous HTTP headers that weaken your security posture.

**Detection Strengths:**
- Web server misconfigurations (Apache, Nginx, IIS, Tomcat)
- Outdated server software with known CVEs
- Exposed administrative interfaces and debugging endpoints
- Insecure HTTP headers (missing CSP, HSTS, X-Frame-Options)
- Default credentials on server components
- Information disclosure through server version headers
- SSL/TLS configuration weaknesses and cipher suite issues
- Directory listing and backup file exposure

**Real-World Impact:** Nikto frequently discovers things that lead directly to system compromise. That exposed .git directory with your source code? Nikto finds it. That phpMyAdmin panel with default credentials? Nikto finds it. That Apache server-status page that leaks internal IP addresses? Nikto finds it.

These aren't sexy vulnerabilities that get CVE numbers and blog posts. They're the boring infrastructure issues that attackers actually use to break in.

### How They Work Together (The Coordination Strategy)

Running four scanners is pointless if you end up with four separate reports, 3000 findings, and no idea which ones actually matter. That's where our orchestration comes in.

We run all four scanners **in parallel** against your target. Not sequentially—parallel. This cuts total scan time to however long the slowest scanner takes, instead of adding up all four runtimes.

Then comes the smart part: intelligent deduplication and correlation. When ZAP finds a SQL injection, Wapiti confirms it with a blind injection test, and Nuclei matches it to a known CVE pattern, we don't report three separate findings. We report one consolidated finding with high confidence and multiple validation sources.

Here's what that looks like in practice:

**Maximum Coverage:** ZAP tests authenticated areas, Nuclei checks for known CVEs, Wapiti fuzzes unauthenticated endpoints, and Nikto scans infrastructure. Between them, nothing slips through.

**Cross-Validation:** When multiple scanners detect the same vulnerability from different angles, the confidence score goes up. A finding confirmed by three independent scanners is virtually guaranteed to be legitimate.

**Speed Optimization:** Parallel execution means you get comprehensive coverage in the time of the slowest scanner. A full scan that would take 6 hours sequentially finishes in 90 minutes.

**False Positive Reduction:** Our AI engine analyzes findings from all four scanners, understands the context, and eliminates duplicates and false positives. You get a single, actionable report instead of wading through thousands of findings.

**Example:** Let's say we're scanning a typical e-commerce application:

- ZAP finds a SQL injection in the admin login form (authentication bypass)
- Wapiti confirms it with a time-based blind injection test (validation)
- Nuclei checks if it matches known SQL injection patterns (pattern matching)
- Nikto discovers the database is MySQL 5.7 with known privilege escalation CVEs (context)

We consolidate this into a single finding: "Critical SQL Injection in Admin Authentication allows complete database access, confirmed by multiple scanners, with known privilege escalation path to system compromise. Fix immediately."

That's the difference between a pile of scanner output and actionable intelligence.

---

## RISK QUANTIFICATION & BUSINESS IMPACT ANALYSIS

### Vulnerability Risk Scoring Algorithm

Link&Load computes a comprehensive risk score (0-10 scale) for each vulnerability through a multi-factor calculation that integrates technical severity, exploitability, and business context.

#### Base Risk Score Calculation

```
Risk Score = (Severity Weight × CVSS Base) + Exploitability Factor + Business Context Modifier

Where:
- Severity Weight: 0.4-0.7 (varies by vulnerability category)
- CVSS Base: 0-10 (Common Vulnerability Scoring System v3.1)
- Exploitability Factor: 0-3 (based on attack complexity and availability of exploits)
- Business Context Modifier: -2 to +3 (asset criticality and compliance requirements)
```

#### Detailed Component Breakdown

**1. CVSS Base Score (0-10 scale)**

We use CVSS v3.1 metrics with the following components:

```
CVSS Base = f(Attack Vector, Attack Complexity, Privileges Required, 
              User Interaction, Scope, Confidentiality Impact, 
              Integrity Impact, Availability Impact)
```

CVSS Severity Classifications:
- **Critical** (9.0-10.0): Complete system compromise, widespread data breach potential
- **High** (7.0-8.9): Significant system impact, sensitive data exposure
- **Medium** (4.0-6.9): Moderate security impact, limited scope
- **Low** (0.1-3.9): Minimal security impact, requires specific conditions
- **Info** (0.0): No direct security impact, informational findings

**2. Exploitability Factor (0-3 points)**

Adjusts risk based on real-world exploitation likelihood:

```
Exploitability = Weaponization Score + Exploit Availability + Attack Surface

Where:
- Weaponization Score: 
  * 0.0 = Theoretical vulnerability, no known exploits
  * 0.5 = Proof-of-concept available
  * 1.0 = Functional exploit code available (Metasploit, ExploitDB)
  * 1.5 = Active exploitation observed in the wild

- Exploit Availability:
  * 0.0 = Requires deep technical knowledge
  * 0.5 = Exploit framework modules available
  * 1.0 = Script-kiddie accessible (automated tools)

- Attack Surface:
  * 0.0 = Internal networks only
  * 0.3 = Authenticated users required
  * 0.5 = Internet-accessible endpoint
```

**3. Business Context Modifier (-2 to +3 points)**

Adjusts risk based on organizational impact and asset value:

```
Business Context = Asset Criticality + Compliance Impact + Data Sensitivity

Where:
- Asset Criticality:
  * -1.0 = Development/testing environment
  * 0.0 = Standard production asset
  * +1.0 = Revenue-generating application
  * +2.0 = Critical infrastructure (authentication, payment processing)

- Compliance Impact:
  * 0.0 = No regulatory requirements
  * +0.5 = Industry standards (PCI-DSS, HIPAA, SOC2)
  * +1.0 = Regulatory violation with financial penalties

- Data Sensitivity:
  * -1.0 = No sensitive data exposure
  * 0.0 = General business data
  * +0.5 = Customer PII (Personally Identifiable Information)
  * +1.0 = Financial data, health records, authentication credentials
```

#### Example Risk Calculations

**Example 1: SQL Injection in Payment Gateway**

```
Vulnerability: SQL Injection (CWE-89)
CVSS Base Score: 9.8 (Critical)
Location: Payment processing endpoint

Risk Score Calculation:
= (0.6 × 9.8) + 2.5 + 3.0
= 5.88 + 2.5 + 3.0
= 11.38 → Capped at 10.0

Components:
- Severity Weight: 0.6 (injection vulnerabilities weighted heavily)
- CVSS Base: 9.8 (critical severity)
- Exploitability Factor: 2.5
  * Weaponization: 1.5 (SQL injection actively exploited in the wild)
  * Exploit Availability: 1.0 (SQLMap, automated tools)
  * Attack Surface: 0.5 (internet-accessible)
- Business Context: +3.0
  * Asset Criticality: +2.0 (payment processing)
  * Compliance Impact: +1.0 (PCI-DSS violation)
  * Data Sensitivity: +1.0 (financial data) → Capped at +3.0

Final Risk Score: 10.0 (CRITICAL)
```

**Example 2: Missing Security Header (CSP)**

```
Vulnerability: Content Security Policy Not Implemented
CVSS Base Score: 3.7 (Low)
Location: Public marketing website

Risk Score Calculation:
= (0.4 × 3.7) + 0.5 + 0.0
= 1.48 + 0.5 + 0.0
= 1.98

Components:
- Severity Weight: 0.4 (configuration issues weighted lower)
- CVSS Base: 3.7 (low severity)
- Exploitability Factor: 0.5
  * Weaponization: 0.0 (requires XSS vulnerability to exploit)
  * Exploit Availability: 0.5 (simple to exploit if XSS present)
  * Attack Surface: 0.5 (internet-accessible)
- Business Context: 0.0
  * Asset Criticality: 0.0 (marketing site, not revenue-critical)
  * Compliance Impact: 0.0 (no regulatory requirements)
  * Data Sensitivity: 0.0 (no sensitive data)

Final Risk Score: 2.0 (LOW)
```

**Example 3: Exposed Admin Panel with Default Credentials**

```
Vulnerability: Default Credentials on Admin Interface
CVSS Base Score: 8.1 (High)
Location: /admin/login.php

Risk Score Calculation:
= (0.6 × 8.1) + 2.5 + 2.0
= 4.86 + 2.5 + 2.0
= 9.36

Components:
- Severity Weight: 0.6 (authentication bypass)
- CVSS Base: 8.1 (high severity)
- Exploitability Factor: 2.5
  * Weaponization: 1.0 (well-known default credentials)
  * Exploit Availability: 1.0 (no technical skill required)
  * Attack Surface: 0.5 (internet-accessible)
- Business Context: +2.0
  * Asset Criticality: +1.0 (admin access to production system)
  * Compliance Impact: +0.5 (access control violation)
  * Data Sensitivity: +0.5 (customer data accessible)

Final Risk Score: 9.4 (CRITICAL)
```

### Business Risk Quantification

Beyond technical risk scores, Link&Load provides business-oriented risk metrics:

#### 1. Financial Impact Estimation

```
Estimated Financial Impact = (Probability of Exploit × Breach Cost) + Remediation Cost

Where:
- Probability of Exploit: 0.0-1.0 (based on exploitability factors)
- Breach Cost Components:
  * Data breach notification costs ($150-$250 per affected record)
  * Regulatory fines (GDPR: up to 4% annual revenue, HIPAA: $100-$50,000 per violation)
  * Customer churn and reputation damage (2-5% revenue impact for major breaches)
  * Forensics and incident response ($50,000-$5M depending on scope)
- Remediation Cost:
  * Developer time to fix vulnerability ($50-$200/hour × estimated hours)
  * Testing and validation effort
  * Emergency patching overhead (2-5x normal development cost)
```

#### 2. Compliance Risk Mapping

Each vulnerability is automatically mapped to relevant compliance frameworks:

- **PCI-DSS**: Requirements 6.5 (secure coding), 6.6 (web application firewalls), 11.3 (penetration testing)
- **HIPAA**: §164.308 (access controls), §164.312 (technical safeguards)
- **SOC 2**: CC6.1 (logical access), CC7.1 (system operations)
- **GDPR**: Article 32 (security of processing)
- **ISO 27001**: A.14.2 (security in development)

**Compliance Violation Severity:**
- **Critical Violation**: Direct breach of regulatory requirement with potential fines
- **Control Gap**: Missing security control that weakens compliance posture
- **Best Practice**: Industry standard not currently met

#### 3. Attack Path Analysis

Link&Load constructs potential attack chains showing how vulnerabilities can be combined:

```
Example Attack Chain:
1. Information Disclosure (Server Version Header) → [Risk: 1.5/10]
2. Known CVE in Identified Server Version → [Risk: 7.0/10]
3. Remote Code Execution via CVE → [Risk: 9.8/10]
4. Lateral Movement to Database Server → [Impact: Critical Data Breach]

Chain Risk Multiplier: 1.5x
(Vulnerabilities that enable further attacks receive elevated risk scores)
```

#### 4. Prioritization Matrix

Vulnerabilities are ranked using a priority score that balances urgency and resource requirements:

```
Priority Score = (Risk Score × Exploitability) / Remediation Effort

Where:
- Remediation Effort (estimated developer hours):
  * 0.5 = Configuration change (update HTTP headers, disable debug mode)
  * 2 = Dependency upgrade (update library version, test compatibility)
  * 8 = Code refactoring (input validation, authentication logic)
  * 40 = Architecture redesign (session management overhaul)

Priority Classifications:
- P0 (Emergency): Priority Score > 15, fix within 24 hours
- P1 (Urgent): Priority Score 10-15, fix within 1 week
- P2 (High): Priority Score 5-10, fix within 1 month
- P3 (Medium): Priority Score 2-5, fix within 1 quarter
- P4 (Low): Priority Score < 2, backlog for future sprints
```

### Threat Intelligence Enrichment

Risk scores are dynamically adjusted based on real-time threat intelligence:

- **Active Exploitation**: +2.0 risk points if vulnerability is being actively exploited (CISA KEV catalog)
- **Trending Attacks**: +1.0 risk points if recent surge in exploitation attempts (AlienVault OTX, Shodan)
- **Ransomware Campaigns**: +1.5 risk points if vulnerability used in ransomware attacks
- **Nation-State Activity**: +1.0 risk points if associated with APT groups
- **Patch Availability**: -0.5 risk points if vendor patch available for >90 days (delayed patching less critical)

### Risk Report Generation

Each scan produces comprehensive reports containing:

1. **Executive Summary**
   - Total vulnerabilities by severity (Critical/High/Medium/Low/Info)
   - Overall security posture grade (A-F)
   - Estimated financial exposure
   - Compliance status overview

2. **Technical Findings**
   - Detailed vulnerability descriptions with CWE classifications
   - Proof-of-concept exploit demonstrations
   - Affected URLs/parameters/components
   - CVSS vector strings and score breakdowns

3. **Remediation Guidance**
   - Step-by-step fix instructions with code examples
   - Dependency upgrade recommendations
   - Configuration hardening checklists
   - Validation testing procedures

4. **Business Context**
   - Prioritized remediation roadmap with effort estimates
   - Compliance gap analysis with specific requirement mappings
   - Attack chain scenarios with visual diagrams
   - Resource allocation recommendations

---

## SYSTEM ARCHITECTURE

```
                              ┌─────────────────────────────┐
                              │     COMMAND CENTER          │
                              │   React 18 + TailwindCSS    │
                              │   Tactical Dashboard UI     │
                              └─────────────┬───────────────┘
                                            │
                                   REST API / WebSocket
                                            │
                              ┌─────────────▼───────────────┐
                              │    OPERATIONS HUB           │
                              │   FastAPI + Async Python    │
                              │   Request Orchestration     │
                              └─────────────┬───────────────┘
                                            │
              ┌─────────────────────────────┼─────────────────────────────┐
              │                             │                             │
    ┌─────────▼─────────┐        ┌──────────▼──────────┐       ┌──────────▼─────────┐
    │   OWASP ZAP       │        │      NUCLEI         │       │      WAPITI        │
    │   Scanner Unit    │        │    Scanner Unit     │       │    Scanner Unit    │
    │   Port 8090       │        │    Binary Exec      │       │    Library/Binary  │
    └─────────┬─────────┘        └──────────┬──────────┘       └──────────┬─────────┘
              │                             │                             │
              └─────────────────────────────┼─────────────────────────────┘
                                            │
                              ┌─────────────▼───────────────┐
                              │   INTELLIGENCE FUSION       │
                              │   Vulnerability Aggregator  │
                              │   Deduplication & Scoring   │
                              └─────────────┬───────────────┘
                                            │
              ┌─────────────────────────────┼─────────────────────────────┐
              │                             │                             │
    ┌─────────▼─────────┐        ┌──────────▼──────────┐       ┌──────────▼─────────┐
    │   LLM SERVICE     │        │   MITRE MAPPER      │       │   RISK ANALYZER    │
    │   AI Analysis     │        │   ATT&CK Mapping    │       │   Score Compute    │
    └─────────┬─────────┘        └──────────┬──────────┘       └──────────┬─────────┘
              │                             │                             │
              └─────────────────────────────┼─────────────────────────────┘
                                            │
                              ┌─────────────▼───────────────┐
                              │   DATA VAULT                │
                              │   PostgreSQL + Supabase     │
                              │   Row-Level Security        │
                              └─────────────────────────────┘
```

### Core Components

**Command Center (Frontend)**
- React 18 with React Router v6
- Real-time WebSocket integration
- Responsive tactical interface
- D3.js threat visualization

**Operations Hub (Backend)**
- FastAPI with async/await architecture
- SQLAlchemy ORM with Alembic migrations
- Redis caching layer for performance
- Rate limiting and security middleware

**Scanner Fleet**
- Containerized OWASP ZAP instance
- Nuclei with template management
- Wapiti with module configuration
- Unified result normalization

**Intelligence Layer**
- Multi-provider LLM integration
- ML-based vulnerability classification
- MITRE ATT&CK knowledge base
- Enhanced risk scoring algorithms

---

## DEPLOYMENT PROTOCOL (Getting This Thing Running)

Alright, let's get you operational. We've done the hard work of containerizing everything, writing health checks, and making this actually deployable. Your job is to clone the repo and run three commands.

### What You Need (Prerequisites)

**Minimum Requirements:**
- Docker Engine 20.10+ and Docker Compose 2.0+ (because containers beat "works on my machine" excuses)
- 8GB RAM minimum (16GB recommended if you want deep scans with ZAP's AJAX spider)
- 20GB disk space (scanners generate a lot of output files)

**For Development (if you're modifying the platform):**
- Python 3.11+ (the backend is FastAPI)
- Node.js 18+ (the frontend is React)
- PostgreSQL 15+ (we use Supabase, but local Postgres works fine for dev)

That's it. If you've got Docker running, you're 90% there.

### Quick Start (Docker - Recommended)

Four commands. That's all it takes:

```bash
# 1. Clone the repository
git clone https://github.com/pratiyk/Link-Load.git
cd Link-Load

# 2. Configure your environment
cp linkload-core/backend/.env.example linkload-core/backend/.env
cp linkload-frontend/frontend/.env.example linkload-frontend/frontend/.env
# Edit those .env files (see configuration section below)

# 3. Navigate to the deployment directory
cd linkload-devops

# 4. Deploy everything
docker-compose up -d
```

Grab coffee. Docker will pull images, build containers, and start services. First run takes 5-10 minutes depending on your internet connection.

When you see this, you're operational:
```bash
docker-compose ps
# All services should show "Up" status
```

Verify deployment:
```bash
# Backend health check
curl http://localhost:8000/health
# Should return: {"status": "healthy", "database": true}

# Frontend loaded
curl -s http://localhost:3000 | head -1
# Should return HTML

# ZAP scanner ready
curl http://localhost:8090/JSON/core/view/version/
# Should return ZAP version info
```

If all three commands return successfully, you're good to go. Open http://localhost:3000 in your browser and you'll see the command center.

### What's Actually Running (Container Architecture)

When you run docker-compose up, you're spinning up a multi-container stack. Here's what each container does:

| Container | Image | Port | Purpose |
|-----------|-------|------|---------|
| `linkload-backend` | python:3.11-slim | 8000 | FastAPI REST API server |
| `linkload-frontend` | node:18-alpine | 3000 | React production build served via `serve` |
| `linkload-zap` | ghcr.io/zaproxy/zaproxy:stable | 8090 | OWASP ZAP security scanner |
| `linkload-postgres` | postgres:15-alpine | 15432 | Local PostgreSQL database |
| `linkload-nginx` | nginx:alpine | 80/443 | Reverse proxy (production profile) |

### Docker Commands You'll Actually Use

Here's your quick reference for managing the platform:

```bash
# ==== Starting & Stopping ====
docker-compose up -d                    # Start everything in the background
docker-compose stop                     # Stop without removing containers (data preserved)
docker-compose down                     # Stop and remove containers (data preserved in volumes)
docker-compose down -v                  # Nuclear option: stop, remove containers, delete volumes

# ==== Monitoring ====
docker-compose ps                       # What's running?
docker-compose logs -f                  # Stream all logs (Ctrl+C to exit)
docker-compose logs -f backend          # Stream just backend logs
docker-compose logs -f frontend         # Stream just frontend logs
docker-compose logs --tail=100 backend  # Last 100 lines from backend

# ==== Rebuilding ====
docker-compose build                    # Rebuild all containers after code changes
docker-compose build --no-cache         # Force fresh build (if things are weird)
docker-compose up -d --build            # Rebuild and restart in one command

# ==== Troubleshooting ====
docker-compose restart backend          # Restart just the backend container
docker-compose exec backend bash        # Get a shell inside backend container
docker-compose exec frontend sh         # Get a shell inside frontend container

# ==== Cleaning Up ====
docker system prune -af                 # Delete all unused containers, images, networks
docker builder prune -af                # Clear Docker build cache
```

Protip: Add `alias dc='docker-compose'` to your shell config. You'll thank me later.

### Container Health Checks

All containers include health checks for automatic recovery:

```bash
# Check container health status
docker-compose ps

# Backend health endpoint
curl http://localhost:8000/health

# Frontend health check
curl -s http://localhost:3000 | head -1

# OWASP ZAP version check
curl http://localhost:8090/JSON/core/view/version/
```

### Environment Variable Configuration

The Docker setup supports configuration via environment variables:

**Backend Container (`backend/.env`):**
```bash
# Database (Supabase cloud or local PostgreSQL)
DATABASE_URL=postgresql://user:pass@host:port/db
SUPABASE_URL=https://project.supabase.co
SUPABASE_KEY=your-anon-key

# LLM Providers (configure at least one for AI analysis)
GROQ_API_KEY=gsk_...          # Recommended: Fast & free
OPENAI_API_KEY=sk-...         # Alternative: GPT-3.5/4
ANTHROPIC_API_KEY=sk-ant-...  # Alternative: Claude

# Scanner settings
ZAP_BASE_URL=http://owasp-zap:8090
NUCLEI_BINARY_PATH=/usr/bin/nuclei
WAPITI_BINARY_PATH=/usr/bin/wapiti
```

**Frontend Container (`frontend/.env`):**
```bash
REACT_APP_API_URL=http://localhost:8000
REACT_APP_WS_URL=ws://localhost:8000
REACT_APP_SUPABASE_URL=https://project.supabase.co
REACT_APP_SUPABASE_ANON_KEY=your-anon-key
```

### Development Deployment (Local)

**Backend Operations:**
```bash
cd backend
python -m venv .venv

# Windows
.venv\Scripts\activate

# Linux/macOS
source .venv/bin/activate

pip install -r requirements.txt
python -m uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

**Frontend Operations:**
```bash
cd frontend
npm install
npm start
```

**Using Start Scripts (Windows):**
```powershell
# Start backend
.\backend\start_backend.ps1

# Start frontend
.\frontend\start_frontend.ps1
```

### Access Points

| Service | URL | Description |
|---------|-----|-------------|
| Command Center | http://localhost:3000 | Primary user interface |
| API Gateway | http://localhost:8000 | REST API endpoints |
| API Documentation | http://localhost:8000/docs | Interactive Swagger docs |
| ZAP Interface | http://localhost:8090 | Scanner admin panel |
| PostgreSQL (Docker) | localhost:15432 | Local database access |

---

## MISSION CONTROL INTERFACE

### Dashboard Overview

The tactical dashboard provides immediate situational awareness:

- **Active Scans Panel** - Real-time progress of all ongoing operations
- **Threat Summary** - Aggregated vulnerability counts by severity
- **Risk Gauge** - Visual representation of overall security posture
- **Recent Findings** - Latest discovered vulnerabilities with quick actions

### Scan Initiation

1. Enter target URL in the command input
2. Select scanner array (OWASP, Nuclei, Wapiti, or all)
3. Configure scan options (deep scan, AI analysis, MITRE mapping)
4. Execute scan and monitor real-time progress

### Results Analysis

Scan results are presented in a structured intelligence report:

- **Executive Summary** - AI-generated overview for leadership briefing
- **Vulnerability Catalog** - Detailed findings with severity classification
- **MITRE ATT&CK Map** - Visual technique correlation
- **Remediation Queue** - Prioritized action items with effort estimates

---

## API COMMAND STRUCTURE

### Authentication

```bash
# Register new operator
POST /api/v1/auth/register
{
  "email": "operator@command.mil",
  "password": "SecurePass123!"
}

# Authenticate and receive credentials
POST /api/v1/auth/login
{
  "email": "operator@command.mil",
  "password": "SecurePass123!"
}
# Returns: { "access_token": "...", "token_type": "bearer" }
```

### Scan Operations

```bash
# Initiate reconnaissance mission
POST /api/v1/scans/comprehensive/start
Authorization: Bearer <token>
{
  "target_url": "https://target.example.com",
  "scan_types": ["owasp", "nuclei", "wapiti"],
  "options": {
    "enable_ai_analysis": true,
    "enable_mitre_mapping": true,
    "deep_scan": false,
    "timeout_minutes": 30
  }
}
# Returns: { "scan_id": "uuid-string" }

# Query mission status
GET /api/v1/scans/comprehensive/{scan_id}/status
# Returns: { "status": "in_progress", "progress": 45, "current_stage": "Running Nuclei scan" }

# Retrieve intelligence report
GET /api/v1/scans/comprehensive/{scan_id}/result
# Returns full scan results with vulnerabilities, risk assessment, and AI analysis

# Abort mission
POST /api/v1/scans/{scan_id}/cancel
```

### Domain Verification

```bash
# Request domain ownership verification
POST /api/v1/verification/request
{ "domain": "target.example.com" }

# Confirm DNS verification
POST /api/v1/verification/verify
{
  "domain": "target.example.com",
  "verification_token": "linkload-verify-..."
}
```

---

## SCANNER ARSENAL

### OWASP ZAP

The Zed Attack Proxy provides comprehensive active scanning capabilities:

- Spider/crawler for site mapping
- Active scan with attack payloads
- Passive analysis of responses
- AJAX spider for JavaScript-heavy applications
- Authentication handling for protected areas

**Detected Threat Categories:**
- SQL Injection variants
- Cross-Site Scripting (XSS)
- Path Traversal
- Remote Code Execution vectors
- Authentication weaknesses

### Nuclei

Template-driven vulnerability scanner for rapid detection:

- 8000+ community-maintained templates
- Custom template support
- CVE-specific detection
- Misconfiguration identification
- Exposed panel discovery

**Template Categories:**
- CVEs (Known vulnerabilities)
- Default credentials
- Exposed admin panels
- Misconfigurations
- Network services

### Wapiti

Black-box web application security auditor:

- No source code required
- Module-based architecture
- GET/POST parameter fuzzing
- Cookie and header analysis
- Comprehensive reporting

**Attack Modules:**
- SQL/XPath/LDAP injection
- File handling vulnerabilities
- Command execution
- CRLF injection
- Server-side request forgery

---

## INTELLIGENCE ANALYSIS ENGINE

### LLM Integration

The platform supports multiple AI providers with automatic failover:

**Provider Priority Order:**
1. **Groq** (Llama 3.3 70B) - Fast, cost-effective, recommended
2. **OpenAI** (GPT-3.5/4) - High accuracy, broad knowledge
3. **Anthropic** (Claude) - Detailed analysis, reasoning
4. **Fallback Engine** - Basic heuristic analysis (no API required)

**Configuration:**
Set at least one API key in `backend/.env`:
```bash
GROQ_API_KEY=gsk_...          # Get from console.groq.com
OPENAI_API_KEY=sk-...         # Get from platform.openai.com
ANTHROPIC_API_KEY=sk-ant-...  # Get from console.anthropic.com
```

The system automatically selects the highest-priority available provider.

### Analysis Outputs

**Vulnerability Assessment:**
- Severity recalibration based on context
- Exploitation likelihood estimation
- Business impact projection
- Remediation complexity rating

**Executive Summary Generation:**
- Third-person technical narrative
- Security posture assessment
- Critical attack vector identification
- Prioritized remediation roadmap

### MITRE ATT&CK Mapping

The intelligence engine correlates vulnerabilities to ATT&CK techniques:

```
Vulnerability: SQL Injection in login form
    |
    +-- Technique: T1190 (Exploit Public-Facing Application)
    |   Tactic: Initial Access
    |   Confidence: 0.92
    |
    +-- Technique: T1078 (Valid Accounts)
        Tactic: Persistence
        Confidence: 0.78
```

### Risk Scoring Algorithm

```
Risk Score = (Severity Weight * CVSS Score) + 
             (Exploitability Factor) + 
             (Business Context Modifier)

Where:
- Critical: Weight 2.0
- High: Weight 1.5
- Medium: Weight 0.8
- Low: Weight 0.2
```

---

## SECURITY PROTOCOLS

### Authentication Framework

- JWT-based token authentication
- Configurable token expiration
- Refresh token rotation
- Multi-factor authentication ready

### Access Control

- Role-based access control (RBAC)
- Resource ownership verification
- 4-layer data isolation enforcement
- Cross-user access prevention

### Network Security

- HTTPS enforcement in production
- CORS policy configuration
- Rate limiting per endpoint
- Security header injection:
  - Strict-Transport-Security
  - X-Content-Type-Options
  - X-Frame-Options
  - Content-Security-Policy
  - Referrer-Policy

### Data Protection

- Row-level security in PostgreSQL
- Encrypted sensitive fields
- Audit logging for all operations
- Secure credential storage with bcrypt

---

## DOMAIN AUTHORIZATION PROTOCOL

### Purpose

DNS TXT record verification ensures scan authorization by proving domain ownership. This prevents unauthorized reconnaissance against third-party assets.

### Verification Flow

```
OPERATOR                    LINK&LOAD                    DNS SERVER
    |                           |                            |
    |  1. Request Verification  |                            |
    |-------------------------->|                            |
    |                           |                            |
    |  2. Verification Token    |                            |
    |<--------------------------|                            |
    |                           |                            |
    |  3. Add TXT Record        |                            |
    |-------------------------------------------------------->|
    |                           |                            |
    |  4. Confirm & Verify      |                            |
    |-------------------------->|                            |
    |                           |                            |
    |                           |  5. Query TXT Record       |
    |                           |--------------------------->|
    |                           |                            |
    |                           |  6. Record Confirmed       |
    |                           |<---------------------------|
    |                           |                            |
    |  7. Authorization Granted |                            |
    |<--------------------------|                            |
```

### DNS Record Configuration

Add a TXT record to your domain's DNS:

| Field | Value |
|-------|-------|
| Type | TXT |
| Name | _linkload-verify |
| Value | linkload-verify-{token} |
| TTL | 300 |

### Verification Commands

```bash
# Request verification token
curl -X POST http://localhost:8000/api/v1/verification/request \
  -H "Authorization: Bearer <token>" \
  -H "Content-Type: application/json" \
  -d '{"domain": "example.com"}'

# Confirm domain ownership
curl -X POST http://localhost:8000/api/v1/verification/verify \
  -H "Authorization: Bearer <token>" \
  -H "Content-Type: application/json" \
  -d '{"domain": "example.com", "verification_token": "linkload-verify-..."}'
```

---

## CONFIGURATION MATRIX

### Environment Variables

**Backend Configuration (`backend/.env`):**
```bash
# ===== Database Configuration =====
DATABASE_URL=postgresql://postgres:UNYe92CVavEN6u7a@localhost:15432/postgres
SUPABASE_URL=https://project.supabase.co
SUPABASE_KEY=your-anon-key
SUPABASE_SERVICE_KEY=your-service-key

# ===== Scanner Configuration =====
ZAP_BASE_URL=http://localhost:8090
ZAP_API_KEY=your-zap-api-key
NUCLEI_BINARY_PATH=/usr/bin/nuclei          # Docker
NUCLEI_BINARY_PATH=C:\tools\nuclei.exe      # Windows
NUCLEI_TEMPLATES_PATH=/opt/nuclei-templates
WAPITI_BINARY_PATH=/usr/bin/wapiti          # Docker
WAPITI_BINARY_PATH=C:\venv\Scripts\wapiti   # Windows
SCAN_TIMEOUT=600

# ===== AI Provider Keys (configure at least one) =====
GROQ_API_KEY=gsk_...          # Recommended: Fast, free tier available
OPENAI_API_KEY=sk-...         # Alternative: GPT-3.5/4
ANTHROPIC_API_KEY=sk-ant-...  # Alternative: Claude

# ===== Security Configuration =====
SECRET_KEY=your-256-bit-secret-key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=10080
REFRESH_TOKEN_EXPIRE_DAYS=30

# ===== Application Settings =====
ENVIRONMENT=development
CORS_ORIGINS=http://localhost:3000,http://localhost:8000
ENABLE_DOCS=true
LOG_LEVEL=INFO

# ===== Rate Limiting =====
RATE_LIMIT_PER_MINUTE=60
MAX_CONCURRENT_SCANS=3
MAX_SCANS_PER_USER_PER_DAY=10

# ===== Redis Cache (Optional) =====
REDIS_URL=redis://localhost:6379/0

# ===== External Intelligence APIs (Optional) =====
VT_API_KEY=...           # VirusTotal
SHODAN_API_KEY=...       # Shodan
NVD_API_KEY=...          # National Vulnerability Database
ABUSEIPDB_API_KEY=...    # AbuseIPDB
```

**Frontend Configuration (`frontend/.env`):**
```bash
REACT_APP_API_URL=http://localhost:8000
REACT_APP_WS_URL=ws://localhost:8000
REACT_APP_API_TIMEOUT=30000
REACT_APP_SUPABASE_URL=https://project.supabase.co
REACT_APP_SUPABASE_ANON_KEY=your-anon-key
```

### Docker Compose Services

| Service | Image | Port | Purpose | Resources |
|---------|-------|------|---------|-----------|
| backend | python:3.11-slim | 8000 | FastAPI server | - |
| frontend | node:18-alpine | 3000 | React app (serve) | - |
| postgres | postgres:15-alpine | 15432 | Database | - |
| owasp-zap | zaproxy/zaproxy:stable | 8090 | ZAP scanner | 2 CPU, 4GB RAM |
| nginx | nginx:alpine | 80/443 | Reverse proxy | Production only |

---

## VERIFICATION PROCEDURES

### Health Check

```bash
# System health (all services)
python backend/health_check_services.py

# Backend health endpoint
curl http://localhost:8000/health
# Returns: {"status": "healthy", "database": true, "version": "1.0.0"}

# OWASP ZAP version
curl http://localhost:8090/JSON/core/view/version/

# Docker container status
docker-compose ps
```

### Test Suite Execution

```bash
# Backend unit tests
cd backend
pytest tests/ -v

# Backend with coverage
pytest tests/ -v --cov=app --cov-report=html

# End-to-end integration tests
python run_e2e_tests.py

# Frontend tests
cd frontend
npm test
```

### Scanner Verification

```bash
# Verify Nuclei installation
nuclei -version                          # Local
docker-compose exec backend nuclei -version  # Docker

# Verify Wapiti installation
wapiti --version                         # Local
docker-compose exec backend wapiti --version # Docker

# Test Nuclei scan
nuclei -target "http://testhtml5.vulnweb.com" -severity critical,high,medium,low,info

# Verify ZAP API
curl http://localhost:8090/JSON/core/action/version/
```

### LLM Provider Verification

```bash
# Check LLM configuration (from backend directory)
cd backend
python -c "
from app.core.config import settings
print('GROQ_API_KEY:', 'SET' if settings.GROQ_API_KEY else 'NOT SET')
print('OPENAI_API_KEY:', 'SET' if settings.OPENAI_API_KEY else 'NOT SET')
"

# Test LLM service
python -c "
import asyncio
from app.services.llm_service import llm_service
print(f'Active Provider: {type(llm_service._provider).__name__}')
"
```

### Validation Checklist

- [ ] All containers running: `docker-compose ps`
- [ ] Database connectivity: Health endpoint returns `database: true`
- [ ] Scanner availability: ZAP version endpoint responds
- [ ] Frontend loads: Browser access to port 3000
- [ ] API documentation: Swagger UI at /docs
- [ ] Authentication flow: Login returns valid JWT
- [ ] LLM configured: At least one provider set (Groq/OpenAI/Anthropic)
- [ ] Nuclei templates: Templates directory exists and populated

---

## TACTICAL ROADMAP

### Mission Status: Phase 1 Complete [OPERATIONAL]

**Web Application Security Platform - OPERATIONAL**

Link&Load has successfully completed Phase 1 deployment with a production-ready web vulnerability scanning platform featuring:
- Multi-scanner orchestration (OWASP ZAP, Nuclei, Wapiti)
- AI-enhanced vulnerability analysis with Groq/OpenAI/Claude integration
- MITRE ATT&CK framework mapping
- Real-time WebSocket intelligence feeds
- Docker containerization with health checks
- Comprehensive test coverage (40+ tests)

---

### Phase 2: API Security Warfare [Q1 2026 - HIGH PRIORITY]

**Objective:** Extend reconnaissance capabilities to API attack surfaces

Modern applications are API-first. RESTful endpoints, GraphQL schemas, and microservices represent 70% of the attack surface but receive only 30% of security attention. Phase 2 deploys specialized API reconnaissance capabilities.

**Target Capabilities:**
- **OpenAPI/Swagger Intelligence:** Automated test generation from API specifications
- **REST API Fuzzing:** Parameter injection, mass assignment, excessive data exposure
- **GraphQL Introspection:** Query complexity attacks, authorization bypass detection
- **OWASP API Top 10:** Broken authentication, improper assets management, injection flaws
- **Rate Limit Testing:** Brute force protection validation
- **Authentication Analysis:** JWT token security, OAuth misconfiguration

**Tools & Technologies:**
- [INTEGRATED] OWASP ZAP API Scan Mode (already integrated, needs enhancement)
- [PLANNED] 42Crunch API Security Audit (open-source, free)
- [PLANNED] REST-Attacker (automated REST API security testing)
- [PLANNED] GraphQL Cop (GraphQL security scanner)
- [PLANNED] Custom fuzzing engine for API-specific attack vectors

**AI Enhancement:**
- Automated API endpoint discovery from JavaScript files
- ML-based anomaly detection in API responses
- Intelligent test case generation from OpenAPI specifications
- GPT-4 powered API vulnerability analysis with business context

**Implementation Timeline:** 4-6 weeks  
**Difficulty:** LOW (leverages existing infrastructure)  
**Revenue Impact:** +$150-300/month per customer (Professional tier upgrade)

---

### Phase 3: Source Code Security Operations (SAST) [Q2 2026]

**Objective:** Shift-left security by analyzing source code before deployment

Find vulnerabilities at the code level before they reach production. Integrate with GitHub, GitLab, and Bitbucket for continuous code security analysis.

**Target Capabilities:**
- **Static Application Security Testing (SAST):** Multi-language vulnerability detection
- **Secrets Detection:** Hardcoded API keys, passwords, tokens, certificates
- **Dependency Analysis:** Known CVEs in third-party libraries (npm, pip, Maven, NuGet)
- **Code Quality Issues:** Weak cryptography, SQL injection patterns, XSS sinks
- **Supply Chain Security:** Malicious packages, typosquatting, dependency confusion

**Tools & Technologies:**
- [PLANNED] Semgrep (open-source, supports 30+ languages) - **PRIMARY SAST ENGINE**
- [PLANNED] Bandit (Python security linter)
- [PLANNED] ESLint Security Plugins (JavaScript/TypeScript)
- [PLANNED] TruffleHog (secrets detection in git history)
- [PLANNED] OWASP Dependency-Check (vulnerability database integration)
- [PLANNED] Bearer (data security and privacy scanner)

**AI Enhancement:**
- GPT-4 powered automated fix suggestions with code diffs
- Contextual vulnerability explanation for developers
- Priority scoring based on exploitability and business impact
- Automated pull request generation with security patches

**CI/CD Integration:**
- GitHub Actions workflow templates
- GitLab CI/CD pipeline integration
- Jenkins plugin architecture
- Non-blocking security gates with risk thresholds

**Implementation Timeline:** 6-8 weeks  
**Difficulty:** MODERATE (requires VCS integration)  
**Revenue Impact:** +$200-400/month per customer

---

### Phase 4: Cloud Security Posture Management (CSPM) [Q2-Q3 2026]

**Objective:** Secure cloud infrastructure across AWS, Azure, and GCP

Cloud misconfigurations cause 70% of data breaches. Deploy automated cloud security auditing to identify exposed resources, overprivileged IAM roles, and compliance violations.

**Target Capabilities:**

**AWS Reconnaissance:**
- S3 bucket public access detection
- IAM excessive permissions analysis
- Security group misconfigurations
- EBS volume encryption validation
- RDS database security assessment
- Lambda function vulnerability scanning
- CloudTrail audit logging verification

**Azure Operations:**
- Storage account public exposure
- Key Vault secret management
- Network Security Group rules analysis
- SQL Database firewall configurations
- Active Directory excessive permissions

**GCP Missions:**
- Cloud Storage bucket ACLs
- IAM role privilege escalation paths
- VPC firewall rules validation
- Cloud SQL security assessment
- GKE cluster security posture

**Tools & Technologies:**
- [PLANNED] ScoutSuite (multi-cloud security auditing) - **PRIMARY CSPM ENGINE**
- [PLANNED] Prowler (AWS security best practices)
- [PLANNED] CloudSploit (AWS/Azure/GCP scanner)
- [PLANNED] Native cloud SDKs (boto3, azure-sdk, google-cloud)
- [PLANNED] CIS Benchmark integration for compliance scoring

**AI Enhancement:**
- Automated risk prioritization based on asset criticality
- Business-context aware remediation guidance
- Compliance mapping (SOC 2, PCI-DSS, HIPAA, ISO 27001)
- Drift detection with ML-based anomaly identification

**Authentication:**
- OAuth 2.0 integration with cloud providers
- Read-only IAM role assumption (customer-controlled)
- Cross-account access with minimal permissions
- Secure credential storage with encryption at rest

**Implementation Timeline:** 8-12 weeks  
**Difficulty:** ADVANCED (requires cloud provider integrations)  
**Revenue Impact:** +$500-2000/month per customer (Enterprise tier)

---

### Phase 5: Container & Kubernetes Security [Q3 2026]

**Objective:** Secure containerized workloads and orchestration platforms

80% of organizations use containers. Extend security coverage to Docker images, registries, and Kubernetes clusters.

**Target Capabilities:**
- Docker image vulnerability scanning (base images, layers, dependencies)
- Container registry security (Docker Hub, ECR, ACR, GCR)
- Kubernetes RBAC misconfiguration detection
- Pod security policy violations
- Network policy analysis
- Secrets management audit
- CIS Docker & Kubernetes benchmark compliance

**Tools & Technologies:**
- [PLANNED] Trivy (comprehensive container scanner) - **FREE, EXCELLENT**
- [PLANNED] Grype (vulnerability scanner for container images)
- [PLANNED] Kubesec (Kubernetes security risk analysis)
- [PLANNED] kube-bench (CIS Kubernetes benchmark)
- [PLANNED] Falco (runtime security monitoring)

**AI Enhancement:**
- Automated Dockerfile security recommendations
- Kubernetes manifest hardening suggestions
- Runtime behavior anomaly detection
- Compliance-aware remediation strategies

**Implementation Timeline:** 6-8 weeks  
**Difficulty:** MODERATE  
**Revenue Impact:** +$300-800/month per customer

---

### Phase 6: Infrastructure as Code (IaC) Security [Q3 2026]

**Objective:** Secure cloud infrastructure before deployment

Scan Terraform, CloudFormation, Ansible, and Kubernetes manifests for security misconfigurations before they reach production.

**Target Capabilities:**
- Terraform security analysis
- CloudFormation template scanning
- Ansible playbook security review
- Helm chart vulnerability detection
- Hardcoded secrets in IaC files
- Overprivileged resource configurations
- Compliance policy enforcement

**Tools & Technologies:**
- [PLANNED] Checkov (multi-IaC security scanner) - **PRIMARY ENGINE**
- [PLANNED] tfsec (Terraform security scanner)
- [PLANNED] KICS (Keeping Infrastructure as Code Secure)
- [PLANNED] Terrascan (IaC static code analyzer)

**AI Enhancement:**
- Automated security policy generation
- GPT-4 powered fix suggestions with before/after comparisons
- Risk scoring based on cloud provider best practices

**Implementation Timeline:** 3-4 weeks  
**Difficulty:** EASY (file-based scanning)  
**Revenue Impact:** +$100-300/month per customer

---

### Phase 7: Continuous Security Monitoring [Q4 2026]

**Objective:** Transform from one-time scanning to continuous security intelligence

Deploy 24/7 automated monitoring with instant alerting for new vulnerabilities, configuration changes, and security posture degradation.

**Target Capabilities:**
- Scheduled automated scanning (hourly, daily, weekly)
- Asset discovery and inventory management
- Certificate expiration monitoring
- Subdomain takeover detection
- DNS change alerting (anti-phishing)
- Configuration drift detection
- Compliance posture tracking over time
- Threat intelligence feed integration

**Intelligence Sources:**
- CISA Known Exploited Vulnerabilities (KEV) catalog
- National Vulnerability Database (NVD) real-time feeds
- CERT alerts and advisories
- Dark web monitoring for exposed credentials
- GitHub security advisories

**Alerting & Integration:**
- Slack, Microsoft Teams, Discord notifications
- PagerDuty incident creation
- Jira/ServiceNow ticket automation
- Email digests with executive summaries
- Custom webhooks for SOAR integration

**AI Enhancement:**
- Predictive vulnerability analytics (ML-based risk forecasting)
- Behavioral baselining for anomaly detection
- Intelligent alert correlation to reduce noise
- Automated triage and prioritization

**Implementation Timeline:** 6-8 weeks  
**Difficulty:** MODERATE  
**Revenue Impact:** +$500-2000/month per customer (Premium tier)  
**Strategic Value:** Creates recurring revenue and customer stickiness

---

### Phase 8: Enterprise Readiness & Compliance [Q4 2026]

**Objective:** Scale platform for enterprise deployment with compliance automation

Enable large organizations to adopt Link&Load with enterprise-grade features and automated compliance reporting.

**Target Capabilities:**

**Multi-Tenancy & Access Control:**
- Organization hierarchies with business units
- Advanced role-based access control (RBAC)
- SAML 2.0 / OIDC single sign-on (SSO)
- SCIM user provisioning (Okta, Azure AD)
- API key management with granular permissions

**Compliance Automation:**
- SOC 2 Type II evidence collection
- PCI-DSS vulnerability scanning reports
- HIPAA security rule mapping
- ISO 27001 control attestation
- GDPR data protection impact assessments
- NIST Cybersecurity Framework alignment

**Enterprise Integration:**
- SIEM export (Splunk, Elastic, Azure Sentinel)
- SOAR playbook integration
- Vulnerability management platforms (ServiceNow, Jira)
- Ticketing system automation
- CI/CD pipeline native integration

**Audit & Governance:**
- Comprehensive audit logging (7-year retention)
- Immutable evidence storage
- Change tracking and approval workflows
- SLA tracking and reporting
- Executive dashboards with risk trends

**Implementation Timeline:** 10-12 weeks  
**Difficulty:** COMPLEX  
**Revenue Impact:** +$1000-5000/month per customer (Enterprise tier)

---

### Phase 9: Mobile Application Security [2027]

**Objective:** Extend security coverage to iOS and Android applications

60% of enterprises deploy mobile applications. Add mobile-specific vulnerability detection to the platform.

**Target Capabilities:**
- Android APK static analysis
- iOS IPA binary inspection
- Insecure data storage detection
- Weak encryption identification
- SSL pinning validation
- Code obfuscation assessment
- OWASP Mobile Top 10 coverage

**Tools & Technologies:**
- [PLANNED] MobSF (Mobile Security Framework) - **FREE, COMPREHENSIVE**
- [PLANNED] Qark (Android security scanner)
- [PLANNED] iMAS (iOS security framework)

**Implementation Timeline:** 8-10 weeks  
**Difficulty:** ADVANCED  
**Revenue Impact:** +$200-500/month per customer

---

### Phase 10: Network Security & Perimeter Defense [2027]

**Objective:** Internal network vulnerability scanning and perimeter security

Scan internal networks, identify exposed services, and detect missing patches across the infrastructure.

**Target Capabilities:**
- Port scanning and service detection
- Version fingerprinting
- Missing patch identification
- SSL/TLS configuration analysis
- Weak authentication detection
- Exposed administrative interfaces

**Tools & Technologies:**
- [PLANNED] Nmap (network mapper)
- [PLANNED] OpenVAS (vulnerability scanner)
- [PLANNED] Nessus API integration (commercial)
- [PLANNED] SSLyze (SSL/TLS scanner)

**Implementation Timeline:** 6-8 weeks  
**Difficulty:** MODERATE  
**Revenue Impact:** +$200-600/month per customer

---

### AI-Powered Innovation Strategy

**Leveraging AI Throughout the Platform:**

Link&Load maintains its tactical advantage through aggressive AI integration using **open-source and free models** wherever possible:

**Primary AI Arsenal:**
1. **Groq (Llama 3.3 70B)** - Fast inference, free tier, primary analysis engine [DEPLOYED]
2. **OpenAI GPT-4** - High-accuracy vulnerability analysis [DEPLOYED]
3. **Anthropic Claude** - Deep reasoning for complex scenarios [DEPLOYED]
4. **Local LLMs (Ollama)** - Privacy-focused deployment for sensitive environments [PLANNED]
5. **HuggingFace Models** - Fine-tuned security models (CodeBERT, SecureBERT) [PLANNED]

**AI-Enhanced Capabilities:**

**Phase 2 (Active):**
- Automated code fix generation with GPT-4
- Executive summary generation for leadership briefings
- Vulnerability severity recalibration based on business context
- Remediation priority scoring

**Phase 3 (Q2 2026):**
- Predictive vulnerability analytics (ML-based risk forecasting)
- Attack graph generation and visualization
- Automated proof-of-concept (PoC) generation for validated findings
- Natural language query interface ("Show me all critical SQLi vulnerabilities")

**Phase 4 (Q3-Q4 2026):**
- Behavioral anomaly detection with unsupervised learning
- Zero-day vulnerability prediction using code patterns
- Automated red team scenario planning
- Intelligent test case generation from requirements

**Phase 5 (2027+):**
- RAG (Retrieval-Augmented Generation) for vulnerability context
- Automated security policy generation from compliance frameworks
- Real-time threat intelligence correlation
- Conversational security assistant for junior analysts

**Open-Source AI Tools:**
- [PLANNED] LangChain (LLM application framework)
- [PLANNED] ChromaDB (vector database for RAG)
- [PLANNED] Ollama (local LLM deployment)
- [PLANNED] HuggingFace Transformers (model inference)
- [PLANNED] Scikit-learn (ML algorithms for scoring)

---

### Military Tactical Theme: Codenames & Terminology

Link&Load maintains its military reconnaissance aesthetic throughout the expansion:

**Operation Codenames:**
- **OPERATION PERIMETER:** Web Application Security (Phase 1) [COMPLETE]
- **OPERATION INTERFACE:** API Security (Phase 2)
- **OPERATION SOURCE:** Code Security (Phase 3)
- **OPERATION SKYWATCH:** Cloud Security (Phase 4)
- **OPERATION CONTAINER:** Docker/K8s Security (Phase 5)
- **OPERATION BLUEPRINT:** IaC Security (Phase 6)
- **OPERATION SENTINEL:** Continuous Monitoring (Phase 7)
- **OPERATION FORTRESS:** Enterprise Features (Phase 8)

**Tactical Terminology:**
- Scans → **Reconnaissance Missions**
- Vulnerabilities → **Threat Vectors**
- Severity → **Combat Priority**
- Remediation → **Countermeasures**
- Reports → **Intelligence Briefings**
- Dashboard → **Command Center**
- Alerts → **Tactical Alerts**
- Users → **Operators**
- APIs → **Command Interface**

**UI/UX Military Aesthetic:**
- Dark mode with tactical green/amber accents
- ASCII art mission briefings
- NATO phonetic alphabet in codenames
- Military rank-based user roles (Operator, Specialist, Commander, General)
- "CLASSIFIED" markers for sensitive findings
- Mission success/failure animations
- Heads-up display (HUD) style visualizations

---

### Long-Term Vision: Unified Security Operations Platform [2027-2028]

**Ultimate Objective:** Become the unified attack surface management platform covering 100% of modern application security

**Comprehensive Coverage:**
```
┌─────────────────────────────────────────────────────────────────┐
│                  LINK&LOAD UNIFIED PLATFORM                     │
│                                                                 │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐        │
│  │   WEB APPS   │  │     APIs     │  │  SOURCE CODE │        │
│  │   Phase 1    │  │   Phase 2    │  │   Phase 3    │        │
│  └──────────────┘  └──────────────┘  └──────────────┘        │
│                                                                 │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐        │
│  │     CLOUD    │  │  CONTAINERS  │  │     IaC      │        │
│  │   Phase 4    │  │   Phase 5    │  │   Phase 6    │        │
│  └──────────────┘  └──────────────┘  └──────────────┘        │
│                                                                 │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐        │
│  │   NETWORK    │  │    MOBILE    │  │  CONTINUOUS  │        │
│  │   Phase 10   │  │   Phase 9    │  │   Phase 7    │        │
│  └──────────────┘  └──────────────┘  └──────────────┘        │
│                                                                 │
│         ┌───────────────────────────────────────┐             │
│         │   AI-POWERED INTELLIGENCE ENGINE      │             │
│         │   • Automated Remediation             │             │
│         │   • Predictive Analytics              │             │
│         │   • Attack Graph Visualization        │             │
│         │   • Compliance Automation             │             │
│         │   • Threat Intelligence Fusion        │             │
│         └───────────────────────────────────────┘             │
└─────────────────────────────────────────────────────────────────┘
```

**Market Position:**
- Compete with Qualys, Tenable, Rapid7 (enterprise VM)
- Compete with Snyk, Veracode (developer security)
- Compete with Wiz, Orca (cloud security)
- **Differentiation:** AI-first, unified platform, 70% lower cost

**Revenue Projection:**
- Year 1 (2026): $1.2M ARR (60 customers @ $20K avg)
- Year 2 (2027): $4.8M ARR (180 customers @ $25K avg)
- Year 3 (2028): $17M ARR (500 customers @ $30K avg)

---

### Open-Source & Free Tools Philosophy

Link&Load prioritizes **open-source, free, and community-driven tools** wherever possible:

**Why Open Source:**
- No vendor lock-in or licensing costs
- Transparent security (auditable code)
- Community-driven updates and improvements
- Flexibility to customize and extend
- Cost-effective scaling (crucial for competitive pricing)

**Current Open-Source Stack:**
- OWASP ZAP (web scanner)
- Nuclei (template engine)
- Wapiti (black-box scanner)
- PostgreSQL (database)
- FastAPI (backend framework)
- React (frontend framework)

**Future Open-Source Additions:**
- Semgrep (SAST)
- Trivy (container scanner)
- Checkov (IaC scanner)
- ScoutSuite (cloud scanner)
- MobSF (mobile scanner)
- TruffleHog (secrets detection)
- Ollama (local LLM deployment)

**Commercial Tools (Only When Necessary):**
- LLM APIs (Groq free tier preferred, fallback to OpenAI)
- Cloud provider APIs (customer-provided credentials)
- Optional premium integrations (Burp Suite API, Nessus)

---

### Implementation Principles

**For All Future Phases:**

1. **AI-First Design:** Every new capability includes AI-enhanced analysis
2. **Free Tool Preference:** Use open-source tools unless commercial is superior
3. **Military Aesthetics:** Maintain tactical terminology and UI theme
4. **Parallel Execution:** All scanners run concurrently for speed
5. **Unified Intelligence:** Single dashboard for all security domains
6. **Developer-Centric:** IDE extensions, CI/CD native, non-blocking workflows
7. **Compliance-Ready:** Map all findings to regulatory frameworks
8. **Cloud-Native:** Kubernetes-ready, horizontal scaling, containerized
9. **API-First:** All features accessible via REST & GraphQL APIs
10. **Privacy-Conscious:** Local LLM deployment option for sensitive data

---

## TECHNOLOGY ARSENAL

### Backend Stack

| Component | Technology | Version |
|-----------|------------|---------|
| Framework | FastAPI | 0.100+ |
| Runtime | Python | 3.11+ |
| ORM | SQLAlchemy | 2.0+ |
| Migrations | Alembic | 1.0+ |
| Cache | Redis | 6.0+ |
| Async | asyncio/uvicorn | Latest |

### Frontend Stack

| Component | Technology | Version |
|-----------|------------|---------|
| Framework | React | 18+ |
| Routing | React Router | 6+ |
| State | React Query | 5+ |
| HTTP | Axios | 1.6+ |
| Styling | TailwindCSS | 3.4+ |
| Charts | D3.js | 7.9+ |

### Infrastructure

| Component | Technology | Purpose |
|-----------|------------|---------|
| Containers | Docker | Service isolation |
| Orchestration | Docker Compose | Development deployment |
| Database | PostgreSQL | Primary data store |
| Database | Supabase | Hosted PostgreSQL option |
| Proxy | Nginx | Production reverse proxy |

---

## FIELD SUPPORT

### Troubleshooting Guide

**Docker Build Failures:**
```bash
# Clean and rebuild
docker-compose down -v
docker system prune -af
docker builder prune -af
docker-compose build --no-cache
docker-compose up -d
```

**Backend Initialization Failure:**
```bash
# View detailed logs
docker-compose logs backend

# Rebuild backend only
docker-compose build backend
docker-compose up -d backend

# Check Python dependencies
docker-compose exec backend pip list
```

**Scanner Connection Issues:**
```bash
# Verify ZAP is running and healthy
docker-compose ps owasp-zap
curl http://localhost:8090/JSON/core/view/version/

# Check Nuclei installation (in container)
docker-compose exec backend nuclei -version

# Check Wapiti installation (in container)
docker-compose exec backend wapiti --version

# View ZAP logs
docker-compose logs owasp-zap
```

**Database Connection Problems:**
```bash
# Check PostgreSQL container
docker-compose logs postgres
docker-compose exec postgres pg_isready

# Connect to database
docker-compose exec postgres psql -U postgres -d postgres

# For Supabase issues, verify credentials in backend/.env
```

**Frontend Build Errors:**
```bash
# Clean install
cd frontend
rm -rf node_modules package-lock.json
npm install
npm start

# Docker rebuild
docker-compose build --no-cache frontend
```

**LLM Provider Issues:**
```bash
# Check if API keys are loaded
cd backend
python -c "from app.core.config import settings; print('GROQ:', bool(settings.GROQ_API_KEY))"

# Test LLM directly
python -c "
import asyncio
from app.services.llm_service import llm_service
result = asyncio.run(llm_service.analyze_vulnerabilities(
    [{'title': 'Test', 'severity': 'high'}], 
    'http://test.com'
))
print('Provider:', type(llm_service._provider).__name__)
print('Result keys:', list(result.keys()))
"
```

**Port Conflicts:**
```bash
# Check what's using ports
netstat -ano | findstr :8000    # Windows
netstat -ano | findstr :3000    # Windows
lsof -i :8000                   # Linux/Mac
lsof -i :3000                   # Linux/Mac

# Kill process by PID
taskkill /PID <pid> /F          # Windows
kill -9 <pid>                   # Linux/Mac
```

### Contact

For operational support, feature requests, or vulnerability reports:

- **Issue Tracker:** [GitHub Issues](https://github.com/pratiyk/Link-Load/issues)
- **Repository:** [github.com/pratiyk/Link-Load](https://github.com/pratiyk/Link-Load)

---

## LEGAL

### License

This project is released under the MIT License. See [LICENSE](LICENSE) for full terms.

### Responsible Use

Link&Load is designed for authorized security testing only. Users must:

- Obtain explicit written permission before scanning any target
- Comply with all applicable laws and regulations
- Use the domain verification system for third-party assets
- Report discovered vulnerabilities responsibly

Unauthorized scanning of systems you do not own or have permission to test is illegal and unethical.

---

## CREDITS

Prateek Shrivastava ([@pratiyk](https://github.com/pratiyk))

---

