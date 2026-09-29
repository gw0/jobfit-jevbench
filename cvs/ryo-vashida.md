# Ryo Vashida
Tokyo, Japan (Hybrid) | ryo.vashida@example.com | +81 90-XXXX-XXXX | linkedin.com/in/ryovashida

## Summary
QA/SDET, ~4 yrs exp, mostly Python + Playwright, some Selenium early on. Comfortable owning e2e test suites end to end (design, build, CI integration, flake triage). Worked hybrid teams JP/SG timezones, used to async handoffs. Like automating the boring stuff, also do a bit of manual exploratory when release crunch hits.

## Skills
- **Languages:** Python (primary), some TypeScript, bash scripting
- **Automation:** Playwright (Python + a little JS), pytest, pytest-bdd, Selenium (legacy projects)
- **CI/CD:** GitHub Actions, Jenkins (older job), Docker for test env isolation
- **API testing:** requests, Postman/Newman, contract testing basics (Pact - only touched once)
- Other: JIRA, TestRail, Grafana dashboards for test metrics, basic SQL for data validation, Git
- Soft: bilingual JP/EN (business level both), used to cross-team communication

## Experience

### SDET — Kurotani Systems, Tokyo (Apr 2023 – Present)
hybrid, 3 days office
- Rebuilt regression suite from Selenium -> Playwright, cut runtime ~40% (parallelization + trace-based debugging instead of screenshots only)
- Own ~600 e2e tests across 3 web apps, added tagging so PM can request smoke-only runs before demos
- Introduced flaky test quarantine process — auto-retry + report to dashboard, reduced false-fail noise significantly, team stopped ignoring CI red
- Mentor 2 junior QA on pytest fixtures / page object patterns, also wrote onboarding doc (internal wiki)
- Pairs with backend devs for API contract tests when new endpoints ship

### QA Engineer — Hachiman Digital Labs, Tokyo (Jul 2021 – Mar 2023)
- Wrote Python automation for internal admin tool (pytest + requests), replaced manual checklist that took ~2hrs/release
- Set up first CI pipeline for QA team (GitHub Actions) — nobody had this before, was just manual test runs on laptops
- Did load/perf smoke tests w/ locust for a couple projects, not deep expertise but enough to catch regressions
- Bug triage owner for 2 sprints during teammate's leave, kept backlog under control

### Junior Test Engineer — Nagatomo Web Solutions, Osaka (Sep 2020 – Jun 2021)
first job out of uni, mostly manual + some scripting
- Manual regression testing for e-commerce client sites, wrote test cases in Excel (yes, really)
- Learned Selenium WebDriver basics, automated login + checkout flow smoke tests
- Reported to QA lead, no direct reports

## Education
**B.Eng, Information Engineering** — Kansai Institute of Technology, Osaka (2016 – 2020)
- Thesis-adjacent project on automated UI testing tools, this is basically where the QA interest started tbh

## Certifications
- ISTQB Foundation Level (2021)
