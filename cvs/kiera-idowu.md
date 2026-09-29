# Kiera Idowu
Austin, TX (Remote) | kiera.idowu@example.com | github.com/kidowu-dev | linkedin.com/in/kieraidowu

## Summary
Backend engineer, ~4 yrs, mostly Python/Django + Postgres. Comfortable owning services end to end - schema design, API work, deploys, on-call. Like fixing slow queries and untangling messy migrations. Remote since 2023, based Austin TX.

## Skills
- **Languages:** Python (primary), some Go, SQL obviously, bash scripts for everything
- Django, Django REST Framework, Celery, gunicorn
- PostgreSQL - indexing, query tuning, replication basics, pgbouncer
- Docker, docker-compose, basic Kubernetes (deployments/services, not cluster admin)
- Redis for caching/queues
- Git, CI via GitHub Actions
- pytest, factory_boy
- AWS (RDS, EC2, S3, some Lambda)
- Nice to have: Terraform (basic), Grafana/Prometheus dashboards

## Experience

### Backend Engineer — Marrowgate Systems (Remote) 
Mar 2023 - Present
- Rebuilt the billing service off a monolith Django app into its own app within same repo (not microservice, just decoupled) - cut deploy time ~40%
- Wrote and maintained ~30 Postgres migrations across 2 years, several involving backfills on tables w/ 40M+ rows without downtime (used batched updates + pt-osc-ish approach manually)
- Introduced Celery for async email/report generation, replaced old cron+script setup
- On-call rotation, reduced P1 incident MTTR by improving alerting (Grafana + Sentry)
- Mentored 2 junior engineers on Django ORM query optimization

### Software Engineer II — Hollowfield Data Co. 
Jun 2021 - Feb 2023, Austin TX (hybrid then remote)
- Built internal REST APIs (DRF) for reporting dashboard used by ~200 internal users
- Owned Postgres schema for core inventory tracking module, added proper indexing after diagnosing slow dashboard loads (14s -> under 1s p95)
- Worked closely w/ frontend (React) team on API contracts, wrote OpenAPI specs
- Set up staging environment w/ Docker Compose, previously everyone ran things locally in a mess

### Junior Developer — Bridgeport Analytics LLC
 Aug 2020 - May 2021
- First real job. Django CRUD apps, fixed bugs, wrote tests (coverage was low when I started, brought it from ~30% to 65% on modules I touched)
- Helped migrate from Django 2.2 to 3.1
- Basic Postgres work - views, some stored procs
- Also did some on-call support for a legacy PHP app during transition period (not fun)

## Education
**B.S. Computer Science** — University of Texas at Austin, 2020
- relevant coursework: databases, distributed systems, software engineering
- GPA 3.4, not that it matters at this point

## Other
- Contribute occasionally to a small open source Django package (rate limiting middleware)
- Comfortable in Linux env, prefer vim/neovim honestly
