# Fumiko Langford
Tokyo, Japan (Hybrid) · fumiko.langford@example.com · linkedin.com/in/fumiko-langford

## Summary
Principal Backend Engineer with 16 years of experience designing, scaling, and operating high-throughput Python/Django services backed by PostgreSQL. Specializes in domain-driven service architecture, query and schema optimization, and mentoring engineering teams through complex platform migrations. Based in Tokyo, working hybrid across distributed teams in APAC and EMEA.

## Skills
- **Languages:** Python (16 yrs), SQL, Go (working proficiency)
- **Frameworks:** Django, Django REST Framework, Celery, FastAPI
- **Databases:** PostgreSQL (replication, partitioning, query planning), Redis, Elasticsearch
- **Infrastructure:** Docker, Kubernetes, AWS (RDS, ECS, SQS), Terraform, GitHub Actions
- **Practices:** Domain-driven design, event-driven architecture, API design, TDD, on-call/incident leadership
- **Leadership:** Technical mentoring, architecture review, cross-team roadmap planning

## Work Experience

### Principal Backend Engineer — Kurogane Systems K.K. | Tokyo, Japan (Hybrid)
*April 2019 – Present*
- Led the re-architecture of a monolithic Django billing platform into eight bounded-context services, cutting P95 API latency by 62% and enabling independent team deployments.
- Designed a PostgreSQL sharding and partitioning strategy for a 40M-row transactions table, reducing nightly batch processing time from 5 hours to 40 minutes.
- Established the org's backend architecture review process, now used by 6 teams before any schema or service-boundary change ships.
- Mentored 5 mid-level engineers into senior roles over three years through structured pairing and design-review coaching.

### Senior Backend Engineer — Amaterasu Cloud Labs | Tokyo, Japan
*June 2013 – March 2019*
- Built and owned a multi-tenant Django/PostgreSQL platform serving 200+ enterprise clients, maintaining 99.95% uptime across four years.
- Introduced Celery-based asynchronous processing for report generation, eliminating request timeouts on the platform's heaviest endpoints.
- Drove adoption of query performance budgets and `EXPLAIN ANALYZE` review in CI, reducing production slow-query incidents by 80%.
- Partnered with product to design a permissions and audit-logging subsystem that became a template reused across three later products.

### Backend Engineer — Nagisa Web Solutions | Osaka, Japan
*April 2010 – May 2013*
- Developed core Django modules for an e-commerce order-management system processing 15,000+ daily transactions.
- Migrated legacy MySQL data stores to PostgreSQL, including a zero-downtime cutover plan for production traffic.
- Built the company's first automated test suite, raising backend code coverage from under 10% to over 70%.

## Education
**B.Eng. in Computer Science**
Tokyo Institute of Technology — 2006 – 2010
