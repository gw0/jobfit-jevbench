# Owen Lachance
Toronto, ON (Remote) | owen.lachance@example.com | github.com/olachance-sec | linkedin.com/in/owenlachance

## Summary
Junior security engineer, ~1yr hands-on. appsec + threat modeling focus, comfortable writing Go for tooling/automation. came up through a dev->sec pivot so I actually read the code before I flag it. looking for teams that ship fast but still want STRIDE done right, not just a checkbox.

## Skills
- **AppSec:** SAST/DAST triage, dependency scanning (Snyk, OWASP DC), secure code review, OWASP Top 10, basic pentesting
- Threat Modeling - STRIDE, attack trees, data flow diagrams (built several from scratch for internal APIs)
- **Go:** wrote internal CLI scanners + a couple of small security automation services, comfortable with net/http, goroutines for concurrent scans
- Python (scripting/glue), Bash
- Burp Suite, ZAP, Semgrep, gosec, trivy
- CI/CD security gates (GitHub Actions, some Jenkins exposure)
- Cloud: AWS (IAM mostly, some GuardDuty/Security Hub)
- Familiar w/ NIST CSF and a bit of ISO27001 from audits I sat in on

## Experience

### Security Engineer I — Northbridge Payments Inc. (Toronto, remote) 
Jan 2025 - Present
- Ran threat modeling sessions for 3 new microservices before launch, caught a broken auth flow in one that wouldve let token reuse across tenants
- built a Go-based internal scanner that wraps semgrep + gosec + custom rules, cut manual review time on PRs by ~40% (rough estimate, no hard baseline before)
- Triaged SAST/DAST findings from checkmarx output, closed out backlog from 400+ down to ~90 in first quarter
- wrote/updated 6 threat model docs, pushed for DFDs to be mandatory before design review sign-off
- on-call rotation support for sec incidents, nothing major, mostly phishing triage and one leaked-key rotation

### AppSec Intern — Caledon Ridge Software 
May 2024 - Dec 2024 (part-time -> converted)
- shadowed senior appsec eng, learned burp/zap workflows on staging environments
- Automated a dependency-check pipeline step in GH Actions, flagged vulnerable pkgs before merge
- Helped draft threat model for a new payments webhook feature - my first real STRIDE exercise
- found and reported an IDOR in an internal admin tool (low severity, still got a shoutout)

## Education
**B.Sc. Computer Science** — University of Toronto, 2024
- relevant coursework: Applied Cryptography, Software Security, Network Security
- capstone project: mini threat-modeling tool (Go backend) that auto-generates STRIDE checklists from a service's API spec — basically a rougher version of what I built later at Northbridge

## Certs / other
- CompTIA Security+ (2024)
- working on OSCP, not done yet
- occasional CTF player, mid-tier on a couple leaderboards, nothing to brag about really
