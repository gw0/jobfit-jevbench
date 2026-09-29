# Sylvia Adeyemi
San Francisco, CA (On-site) | sylvia.adeyemi@example.com | 415-555-0192 | linkedin.com/in/sylviaadeyemi

## Summary
16 yrs security engineering, last 9 as principal-level. AppSec lead, threat modeling (STRIDE/PASTA both used depending on team maturity), and hands on Go for building internal security tooling -- not just a "policy person", i still ship code. Comfortable being the only security eng in the room and also scaling a security culture across 40+ eng teams. Some people call me the "threat model whisperer" idk if thats a compliment

## Skills
- AppSec: SAST/DAST tuning, SDL integration, secure code review (Go, Python, some Java legacy stuff), dependency risk (SBOM/SCA)
- Threat Modeling: STRIDE, attack trees, data flow diagram facilitation, ran 200+ TM sessions
- Go: gRPC services, middleware/auth interceptors, fuzz testing (go-fuzz + native fuzzing), building internal scanners
- Cloud/Infra: AWS (IAM hardening, KMS), Terraform for security guardrails, container security (basic k8s policies)
- Other: incident response, vuln mgmt programs, security champions programs, vendor risk

## Experience

### Principal Security Engineer -- Northgate Ledger Systems (San Francisco, CA)
*2019 - Present*
- Built the company's first centralized threat modeling program from scratch -- went from 0 to mandatory-for-tier1-services in 14 months
- Wrote a Go-based internal tool ("tripwire") that auto-flags risky diffs touching auth/crypto code paths before merge, cut auth-related incidents by roughly 40% (self reported metric, take w grain of salt)
- led appsec review for the payments platform migration, found a critical IDOR that wouldve exposed cross-tenant ledger data pre-launch
- mentor to 3 senior engineers, 2 got promoted since
- owns the vuln management SLA program, 98% on time remediation for criticals last 2 years running

### Senior Security Engineer -- Redcliff Analytics Inc
*2014 - 2019, San Francisco / hybrid before hybrid was a thing*
- Rebuilt threat modeling process after a bad pentest cycle (3 crits found that shouldve been caught earlier) -- new process caught similar classes of bugs in design phase going forward
- wrote Go microservice for internal secrets rotation, integrated w Vault
- ran the bug bounty program, triaged 500+ reports over tenure
- Did NOT enjoy the SOC2 audits but got us through 4 of them clean

### Security Engineer II -- Bramwell & Voss Technologies
*2010 - 2014*
- appsec reviews for the flagship web app (Rails at the time, ironic given im a Go person now)
- introduced static analysis into CI, was resisted heavily at first, eventually became standard
- some pentesting work, mostly internal facing tools
- was the youngest person on the security team for like 3 years straight

### Junior Security Analyst -- Marrow Point Data Co (first job out of school)
*2010, ~8 months, contract-to-hire that didnt convert (budget cuts not performance)*
- log review, basic vuln scanning, learned the fundamentals here honestly

## Education
**B.S. Computer Science** -- University of California, Santa Cruz, 2009
- minor in applied math, thesis loosely related to network intrusion detection heuristics

## Certifications
- OSCP (2013, lapsed but did the work)
- some cloud security cert from a while back, name escapes me, was AWS specific
