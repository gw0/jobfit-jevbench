# Viktoria Adamczyk
Security Engineer (AppSec / Threat Modeling) — Warsaw, PL (remote ok)
viktoria.adamczyk@example.com | +48 6XX XXX XXX | github.com/vadamczyk-sec | linkedin.com/in/viktoria-adamczyk

## Summary
Security engineer, ~4 yrs, mix of appsec review + threat modeling + writing Go tooling to actually fix the stuff findings point at. not just a report-writer - I ship patches, build scanners, and sit in design reviews before code exists so we don't retrofit security later (expensive, everyone hates it). Comfortable in both attacker mindset and building defensive tooling/infra. Warsaw based, worked remote with EU + US teams, ok with CET-heavy overlap.

## Skills
- **AppSec:** SAST/DAST (Semgrep, custom rules, ZAP), secure code review, dependency/SCA triage, secrets scanning, SSRF/IDOR/auth bugs, API security (REST + gRPC)
- **Threat Modeling:** STRIDE, attack trees, data flow diagrams, ran TM workshops for eng teams (not just filled a template and left)
- **Go:** built internal CLIs + scanning services, some concurrency work (worker pools, context cancellation), Go for tooling glue >> for big services (not a Go purist)
- also: Python (scripting/automation), basic Terraform, Docker/k8s enough to be dangerous, CI/CD security (GitHub Actions hardening)
- OWASP Top10/ASVS, NIST-ish stuff, some cloud (AWS mostly, a little GCP)

## Experience

### Security Engineer — Norbrick Systems (Warsaw, remote) — 2023–present
- Owns appsec review pipeline for ~30 internal services, mix of Go and Python
- Wrote a Go-based internal scanner (wraps semgrep + custom AST checks for our auth patterns) - cut manual review time on PRs by a good chunk, teams actually run it pre-merge now
- Ran threat modeling sessions for 3 new product lines pre-launch, caught an IDOR class issue in the payments-adjacent flow before it ever hit staging (would've been bad)
- On-call for security incidents, triaged/coordinated 2 real incidents (nothing catastrophic, contained fast)
- pushed for STRIDE-lite as default in design docs template, mixed adoption but growing

### Application Security Engineer — Kolvatek sp. z o.o. — 2022–2023
- Joined as generalist eng, moved into security within ~6mo after finding + fixing a nasty SSRF in an internal admin tool
- Built dependency scanning into CI (Go + npm ecosystems), reduced known-vuln backlog significantly
- Did manual pentest-style reviews for 2 client-facing apps/yr, wrote reports devs would actually read (short, prioritized, PoC included)
- worked closely with infra team on secrets management rollout (Vault), migrated ~40 services off hardcoded creds

### Junior Software Engineer — Bristawa Digital — 2021–2022
- backend dev, mostly Go microservices, some Python
- got pulled into a security review of our own auth service, found bugs, got hooked, rest is history (see above)
- built internal tooling for log aggregation, nothing fancy

## Education
- **BSc, Computer Science** — Warsaw University of Technology (Politechnika Warszawska), 2017–2021
- some cert stuff: OSCP (in progress, not finished yet - being honest), completed a few TryHackMe/HTB paths for fun/practice
