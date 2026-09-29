# Hamish Fairbanks
Sydney, Australia (hybrid) | hamish.fairbanks@example.com | +61 4XX XXX XXX | linkedin.com/in/hamishfairbanks | github.com/hfairbanks

## Summary
Junior security engineer, ~1yr exp, appsec focus + some threat modeling work, also write Go for tooling. came from a dev background before moving into sec. comfortable doing code review for vulns, building small internal tools, and helping run threat modeling sessions w/ eng teams. still learning but move fast, curious, want to get into red team / detection eventually maybe.

## Skills
- **AppSec:** OWASP Top 10, SAST (Semgrep, CodeQL basics), dependency scanning (Snyk, Trivy), secure code review, basic pentesting w/ Burp Suite
- **Threat Modeling:** STRIDE, data flow diagrams, attack trees (done a handful for internal apps), Microsoft TMT tool
- **Go:** wrote CLI tools + small services, goroutines/channels, basic use of net/http, some gRPC
- Other: Python (scripting), Docker, git, Linux fundamentals, AWS (IAM mostly), Jira/Confluence
- **Certs:** Security+ (2025)

## Experience

### Security Engineer I — Bluegum Cyber Solutions (Sydney) — Feb 2025–Present
hybrid, 3 days in office
- do appsec reviews for ~4 product teams, mostly manual review + running Semgrep against PRs, catch stuff like SSRF, broken auth, insecure deserialization etc
- ran threat modeling workshops for 2 new features (payments-adjacent thing and an internal admin portal) using STRIDE, found a couple of IDOR issues before they shipped which was good
- built a small Go tool that pulls findings from our SAST + dependency scanners and dedupes/normalizes them into one Jira ticket format — saved the team a bunch of manual triage time, still maintaining it
- helped onboard 2 new starters onto our secure coding guidelines doc (which i also rewrote bc old one was outdated)
- occasionally get pulled into incident triage for low-sev stuff, mostly just log review

### Graduate Software Engineer — Wattlebank Digital — Nov 2023–Jan 2025
(this was before I moved into security properly)
- built internal CRUD services in Go + a bit of Node, nothing fancy
- picked up interest in security here after finding an auth bypass in a service I was maintaining, reported it, ended up leading a small remediation effort
- wrote unit + integration tests, worked in a scrum team of 6
- did on-call rotation for prod issues, mostly non-security

### Intern, IT Support — Kookaburra Health Networks — Jun 2023–Oct 2023
- helpdesk tickets, password resets, laptop imaging etc — basic stuff but gave me exposure to how orgs actually handle security hygiene (or don't)
- flagged a phishing campaign hitting staff inboxes, helped write the internal comms warning people

## Education
**Bachelor of Computer Science** — University of Technology Sydney (UTS) — 2020–2023
- minor in cybersecurity, thesis-ish capstone project was a threat model + mitigation plan for a uni-hosted web app (mock scenario)

## Other
- occasional CTF player (mostly web/appsec categories, TryHackMe + a couple local Sydney meetup CTFs)
- attended BSides Canberra 2025 as attendee, want to submit a talk next year maybe re: threat modeling for small teams
