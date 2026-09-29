# Trevor Kincaid
Austin, TX (Remote) | trevor.kincaid@example.com | github.com/tkincaid-sec

## Summary
16 yrs security engineering, last 9 focused almost entirely on appsec + threat modeling for fintech/infra orgs. Principal-level - meaning I don't just review code, I set the bar for how teams THINK about security before they write it. Go is my main tool for tooling/automation but I've shipped Python and some rust when needed. Comfortable presenting to VPs and also comfortable being the person who finds the SSRF nobody else saw.

## Skills
- AppSec: SAST/DAST tuning, secure SDLC design, code review at scale, dependency risk
- Threat Modeling - STRIDE, PASTA, attack trees, have run 200+ sessions across product teams
- Go (primary), Python, some Rust; built internal security tooling in Go for 6+ years
- Cloud: AWS (heavy), GCP (some), IAM hardening, container/K8s security
- Other: fuzzing (go-fuzz, libFuzzer), crypto review (not a cryptographer but know when to call one), incident response, security champions programs

## Experience

### Principal Security Engineer — Nautex Cloud (Austin, remote) — 2019-Present
- Built and lead the appsec function from 2 people to 11, own threat modeling process org-wide
- Wrote a Go-based static analysis wrapper that cut false positive triage time by ~40%, still in use
- Ran threat models for every major service launch (60+), caught a pre-auth RCE path in payments before launch that would've been Very Bad
- reports to CISO, mentors 4 senior engineers, sit on architecture review board
- also did a stint owning vendor security reviews for ~8 months because headcount

### Senior Security Engineer, Meridian Financial Group — 2013-2019 (Austin)
* migrated legacy C++ auth service to Go, security review + rewrite combined, took 14 months
* Introduced threat modeling as a gate in the SDLC — was optional before, made it mandatory for anything touching PII
- built internal bug bounty triage pipeline (Go + some glue scripts), processed 3000+ submissions over tenure
* on-call for security incidents, handled 2 actual breaches (contained, no customer data loss in either)

### Security Engineer -> Sr. Security Engineer, Ironclad Systems (Austin) | 2009 - 2013
- Started as generalist appsec engineer, promoted after 18mo
- Pen tested internal apps (web mostly, some mobile) before we had a dedicated red team
- Wrote the company's first secure coding guidelines doc, still referenced years after I left apparently
- Go wasn't a thing yet when I started here so this was mostly python/java review

## Education
B.S. Computer Science — University of Texas at Austin, 2009
(minor in math, for what it's worth)

OSCP (2014), GWEB - lapsed now but had it 2016-2019
