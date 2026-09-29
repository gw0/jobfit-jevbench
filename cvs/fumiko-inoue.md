# Fumiko Inoue
Security Engineer | Tokyo, Japan (hybrid) | fumiko.inoue@example.com | +81-90-XXXX-XXXX | linkedin.com/in/fumikoinoue-sec

## Summary
Security engineer, ~4 yrs, appsec-focused w/ heavy emphasis on threat modeling + secure Go development. Comfortable embedding w/ product teams to shift security left, also do incident triage when needed. Bilingual JP/EN, worked across fintech + logistics domains. Enjoy breaking things then fixing them properly not just patching symptoms.

## Skills
- **AppSec**: SAST/DAST (Semgrep, CodeQL, Burp Suite), secure code review, dependency scanning (Trivy, Snyk), OWASP ASVS
- **Threat Modeling**: STRIDE, attack trees, PASTA (some), data flow diagram facilitation w/ eng teams
- **Languages**: Go (primary, 3+ yrs), Python (tooling/scripts), some TypeScript
- **Infra/Cloud**: AWS (IAM hardening, GuardDuty), Docker, Kubernetes basics, Terraform (read mostly)
- Auth protocols - OAuth2, OIDC, JWT pitfalls
- Incident response basics, log analysis (Splunk)
- Japanese (native), English (business fluent)

## Experience

### Security Engineer — Kaien Systems K.K., Tokyo
*Apr 2023 – Present*
- Built internal Go-based static analysis wrapper that runs Semgrep + custom rules across ~40 microservices in CI, cut manual review time significantly
- Led threat modeling sessions (STRIDE) for new payments gateway rollout, found 6 high-sev issues pre-launch incl. a broken auth flow that wouldve let token replay
- Own vuln management program - triage, SLA tracking, vendor coordination for 3rd party libs
- wrote Go middleware for rate limiting + request signing used across API gateway, still in prod today
- partnered w/ infra team on IAM least-privilege cleanup, removed 200+ overprivileged roles

### Application Security Analyst — Renjo Cloud Solutions, Osaka (remote from Tokyo)
*Jul 2021 – Mar 2023*
- Performed manual pentests + code reviews for client web apps (mostly Go and Node backends)
- Introduced dependency scanning to CI pipelines, found and remediated critical CVEs in prod before they were flagged externally (avoided what couldve been a bad disclosure)
- Created threat model templates now used org-wide, adopted by 4 other teams
- Go: contributed to internal auth library, fixed a timing side-channel in password comparison func

### Junior Security Analyst — Hachiman Data Labs, Tokyo
*Sep 2020 – Jun 2021*
- Rotated through SOC + appsec functions, mostly log review and alert triage early on
- Assisted senior engineers with quarterly pentest engagements
- Automated recurring reporting task using Python, saved ~5hrs/week of manual work

## Education
**B.Eng, Information Security**
Tokyo Institute of Advanced Sciences — 2016–2020

- Relevant coursework: cryptography, network security, secure systems design
- Capstone project on fuzzing embedded Go services (early interest area, stuck w/ it)

## Certifications
- OSCP (2022)
- AWS Certified Security – Specialty (2023)
