# Praise Tanimowo
Lagos, Nigeria (Remote) | praise.tanimowo@example.com | github.com/ptanimowo | linkedin.com/in/praise-tanimowo

## Summary
Junior security engineer, ~1yr exp. focused on appsec + threat modeling, also comfortable writing Go for tooling/automation. came into security from a backend dev background so i think about vulns in terms of how the code actually executes not just checklists. done a bit of everything - code review, STRIDE sessions, some Go services for internal scanning. still learning but move fast and not afraid to dig into logs/source when something looks off.

## Skills
- **AppSec:** secure code review (Go, JS), OWASP Top 10, dependency scanning (Trivy, npm audit), basic SAST/DAST (Semgrep, OWASP ZAP)
- **Threat Modeling:** STRIDE, attack trees, data flow diagrams, done ad-hoc sessions w/ eng teams pre-launch
- **Go:** net/http, goroutines/channels basics, wrote CLI tools + a couple small internal services
- Other: Linux, git, Docker (basic), Burp Suite (community), Postman, bash scripting
- Currently learning: Kubernetes security, more advanced Go concurrency patterns

## Experience

### Security Engineer (Junior) — Delta Ridge Systems
*Lagos, Nigeria — Mar 2025 to Present*
- run threat modeling sessions for 2 new product features, found a broken auth flow before it shipped (IDOR on an internal API, would've let any authenticated user pull other users' invoice data)
- wrote a Go-based internal tool to grep through nginx access logs for suspicious patterns (basically a poor man's WAF alert thing) — catches ~15 alert types now, still adding more
- did secure code reviews on ~30 PRs, mostly catching input validation gaps and a few hardcoded secrets that slipped past the pre-commit hook (which honestly needs fixing too, flagged it to platform team)
- helped set up dependency scanning in CI, reduced known-vuln deps from 40+ to under 10 in first month
- some on-call rotation for security incidents, nothing major yet just phishing triage mostly

### Backend Developer Intern — Okhai Digital Labs
*Remote — Jul 2024 to Feb 2025*
- built REST APIs in Go for an internal admin dashboard, this is actually where I got interested in security bc kept finding my own bugs
- found and reported a SQL injection in a legacy PHP endpoint that wasn't even part of my project, got it fixed within the week
- wrote unit + some integration tests, coverage went from basically 0 to ~55% on the modules I touched
- documented API endpoints (swagger), team said it was actually useful unlike most docs lol

## Education
**B.Sc. Computer Science** — University of Lagos
2020 – 2024
- final year project on lightweight intrusion detection using log anomaly patterns (not ML based, just statistical thresholds, worked ok for the scope)
- relevant coursework: networks, cryptography basics, software engineering

### Certifications / self-study
- currently working through OSCP material (not certified yet)
- TryHackMe - completed SOC Level 1 path
- various CTFs, mostly web + a bit of pwn, nothing competitive just for learning
