# Gbenga Badmus
gbenga.badmus@example.com | Lagos, Nigeria (Remote) | +234 803 555 0192 | github.com/gbadmus-dev

## Summary
Backend Engineer, 4yrs exp. Django + PostgreSQL mostly, some Celery/Redis. Built and maintained APIs for fintech and logistics products used by thousands daily users. Comfortable owning a service end to end - models, migrations, endpoints, deployment. Like clean data models, hate flaky tests, still learning Kubernetes properly.

## Skills
- **Languages:** Python (primary), some Go, SQL, bash scripting
- **Frameworks:** Django, Django REST Framework, Flask (legacy stuff)
- Postgres (indexes, query tuning, replication basics), Redis for caching/queues
- Celery, RabbitMQ
- Docker, basic CI/CD (GitHub Actions, Gitlab CI)
- REST API design, some GraphQL (Graphene)
- AWS - EC2, RDS, S3, a little bit of Lambda
- Testing: pytest, unittest, factory_boy
- Git obviously. Linux server admin (nginx, gunicorn, systemd)

## Experience

### Backend Engineer - Kolapo Systems Ltd (Lagos, remote) 
*Jan 2023 - Present*
- Rebuilt core order-processing service from monolith Django app into separate service, cut avg response time from ~800ms to 210ms
- design + implementation of a webhook dispatch system for 3rd party integrations (retry logic, exponential backoff, idempotency keys) - this was a mess before I got there, no dedup at all
- Postgres: added partial indexes on high-traffic tables, query time down massively for the reporting dashboard queries
- Wrote internal docs for onboarding, nobody read them lol but they exist
- mentored 2 junior devs, code review, pairing sessions weekly
- migrated CI from Jenkins to Github actions, deploy time from ~40min to under 10

### Software Engineer - Adeyemi Logistics Group
*Jun 2021 - Dec 2022*
- Built REST APIs (DRF) for fleet tracking system, GPS ingestion pipeline handling ~50k events/day
- Integrated payment gateway (Paystack) for driver payouts
- Postgres schema design for multi-tenant setup (shared db, tenant_id column approach not schema-per-tenant, tradeoffs discussed with lead)
- Set up Celery for async tasks - SMS notifications, report generation, etc
- on-call rotation, incident response for prod outages (2 major ones I handled directly)
- Bug fixes, a LOT of bug fixes early on

### Junior Developer - Whitegate Softworks
*Aug 2020 - May 2021*
- first job. Django CRUD apps mostly for internal tools
- wrote unit tests (was not good at this initially, got better)
- basic Postgres queries, learned ORM the hard way (N+1 queries everywhere at first)
- helped migrate a PHP app's data into new Django/Postgres system - painful but learned a lot about data migration scripts

## Education
**B.Sc Computer Science** - University of Lagos
2016 - 2020

Some relevant coursework: Databases, Data Structures & Algorithms, Software Engineering. Final year project was a Django-based inventory system (basic but it's what got me into backend stuff tbh)

## Other
- Occasional contributor to small open source Django packages
- Comfortable working async/remote with distributed teams (all current + prior roles remote or hybrid)
