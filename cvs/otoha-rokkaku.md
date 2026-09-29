# Otoha Rokkaku
Senior QA Engineer / SDET — Tokyo, Japan (hybrid)
otoha.rokkaku@example.com | +81 90-XXXX-XXXX | linkedin.com/in/otoharokkaku | github.com/orokkaku

## Summary
8 yrs total in test eng, mostly automation-focused, Python heavy, Playwright the last 4ish years after we migrated off Selenium (long story). Like building frameworks people actually use not ones that just look good in a demo. Comfortable owning quality end to end - test strategy, CI pipelines, flaky test triage (a lot of that unfortunately), mentoring. Hybrid in Tokyo, work with teams across JP/SG/US timezones so used to async everything.

## Skills
- **Automation:** Python (pytest, unittest), Playwright (Python + some TS when the FE team needed help), Selenium (legacy, still maintain some), Appium (a bit, mobile smoke only
- **CI/CD:** GitHub Actions, Jenkins (old job), GitLab CI - pipeline design, parallelization, test sharding
- API testing: requests, pytest fixtures, contract testing w/ Pact (limited exposure)
- Perf/load: Locust, k6 (basic)
- Other: Docker, SQL (postgres mostly), some Bash scripting, Jira/TestRail/Xray for test mgmt
- Languages: Japanese (native), English (business fluent)

## Experience

### Senior SDET — Kanmuri Systems K.K. (Tokyo) — 2022–Present
- Rebuilt the entire E2E suite in Playwright/Python after Selenium suite became unmaintainable (300+ tests, ~40% flaky before) — got flake rate under 5%
- Own the test architecture for 3 product squads, page object model + fixture layer shared across teams
- introduced parallel test execution in CI, cut regression run from ~2.5hrs to 35min
- mentor 2 junior QAs, one promoted to mid-level this year
- built internal dashboard (Python/Flask, quick and dirty) for test result trends, leadership actually uses it now which was a surprise
- work directly with PMs on acceptance criteria, catch a lot of ambiguity before dev even starts

### QA Automation Engineer — Hikari Digital Labs (Tokyo, some remote) — 2019–2022
- primary Selenium->Playwright transition driver, wrote migration guide still referenced by other teams apparently
- built API test suite in pytest covering ~150 endpoints, integrated into PR gating
- reduced release-blocking bugs found in prod by ~30% (rough estimate, no perfect tracking back then)
- on-call rotation for test infra issues
- worked with an outsourced QA team in Vietnam, coordination was rough at first, improved once we standardized test data setup

### QA Engineer — Nagisa Software Partners (Tokyo) — 2018–2019
- manual + early automation hybrid role, wrote first Selenium scripts here honestly kind of embarrassing looking back
- regression testing for e-commerce platform, high traffic during sales events so had to test under load too (informally, not proper perf testing)
- bug triage, wrote most of the test cases from scratch since there wasn't much documentation

## Education
**B.Eng, Information Engineering** — Tokyo University of Science, 2014–2018
(thesis was on automated UI testing tools, kind of set the whole career path honestly)

## Certifications
- ISTQB Foundation Level (2019)
- some internal Playwright workshops / conference talks, nothing formal beyond that
