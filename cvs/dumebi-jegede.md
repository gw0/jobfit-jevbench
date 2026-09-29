# Dumebi Jegede
Lagos, Nigeria (Remote) | dumebi.jegede@example.com | +234 803 xxx xxxx | github.com/dumebij

## Summary
Backend engineer, 8+ yrs now, mostly Django but touched Flask early on. i build systems that dont fall over -- payments, ledgers, high write APIs. comfortable owning a service end to end: schema design, query tuning, deploy, oncall. led small teams (2-4 devs) at last two roles. remote-first since 2021, worked across WAT/UTC/EST teams without issue.

## Skills
- **Languages:** Python (primary), some Go for a couple of internal tools, SQL obviously
- Django / DRF / Celery / Gunicorn
- PostgreSQL - indexing, partitioning, replication set up (streaming + logical), query plans, the works
- Redis (caching + queues), RabbitMQ a bit
- Docker, basic k8s (helm charts, not designing clusters), Terraform for the small stuff
- AWS (RDS, EC2, S3, SQS) -- GCP briefly at Fenwick
- git obviously. CI/CD - Github Actions mostly, some Jenkins in older jobs
- testing: pytest, factory_boy, also wrote a lot of load tests w/ locust

## Experience

### Senior Backend Engineer -- Vandermere Systems (remote, HQ Lagos/London) 
Mar 2022 - Present
- rebuilt the core ledger service off a monolith, moved to a Django app talking to a partitioned Postgres cluster (by tenant_id + month), cut p99 query time from ~1.8s to under 200ms
- own the payments reconciliation pipeline, processes ~40k transactions/day across 3 payment providers
- introduced idempotency keys across all write endpoints after a double-charge incident in Q3 2022 -- zero repeats since
- mentoring 2 mid level engineers, do most of the architecture review for new services
- on call rotation, wrote most of our current runbooks (were basically nonexistent before)

### Backend Engineer II -- Okonkwo-Reyes Digital Ltd
Jan 2019 - Feb 2022 (Lagos, hybrid then remote from 2020)
- built the initial API for their SME lending product, Django + DRF, integrated with 2 external credit bureaus
- designed the Postgres schema for loan applications + repayment schedules, still in use (as of last i heard)
- wrote a batch job system using Celery + Redis for nightly interest accrual calcs across ~150k active accounts
- reduced db load ~35% by fixing N+1s across the serializer layer (there were a LOT)
- helped migrate off a self-hosted Postgres box to RDS w/ minimal downtime (~4 min maintenance window)

### Junior/Mid Backend Developer -- Fenwick Analytics Group
June 2017 - Dec 2018
- first real backend job. worked on internal reporting tools, Flask + some Django later on
- built REST endpoints for dashboarding data pulled from Postgres + a bit of BigQuery (GCP)
- fixed a nasty race condition in the report-generation queue that was causing duplicate PDF exports
- general firefighting, this was a small team (4 engineers total) so did a bit of everything incl. some frontend (React, reluctantly)

## Education
**B.Sc. Computer Science** -- University of Lagos (UNILAG), 2013 - 2017

Also did a couple of PostgreSQL internals courses on the side (Citus Data's old blog posts + Percona training materials, self study, no cert)
