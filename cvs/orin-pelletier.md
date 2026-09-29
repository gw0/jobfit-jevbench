# Orin Pelletier
toronto, ON (remote) | orin.pelletier@example.com | github.com/opelletier | +1 (416) 555-0192

## Summary
Backend eng, ~8yrs, mostly Django/Postgres shops. i build APIs that dont fall over. comfortable owning services end to end - schema design, migrations, on-call, the works. also done some AWS/infra stuff when nobody else would. looking for senior/staff-track roles, remote preferred but open to Toronto hybrid.

## Skills
- **Languages:** Python (8y), some Go, bash scripting, SQL obviously
- Django, DRF, Celery, gunicorn/uwsgi
- PostgreSQL (indexing, query tuning, replication) - this is basically my specialty at this point
- Docker, docker-compose, basic k8s
- AWS (RDS, EC2, S3, SQS) - not certified just experienced
- Redis, RabbitMQ
- git, CI/CD (github actions mostly, some jenkins in the old days)
- testing: pytest, factory_boy, tox
- REST APIs, some GraphQL exposure

## Experience

### Senior Backend Engineer - Northbridge Analytics Inc.
Toronto, ON (remote) | 2022 - present
- rebuilt the core billing service in Django from a legacy PHP monolith, cut invoice generation time from ~40min to under 3
- introduced connection pooling + query refactors on Postgres that dropped p95 latency on the reporting endpoints by 60%+
- mentored 2 junior engineers, ran the backend hiring loop for about a year
- on-call rotation lead, wrote the runbooks everyone still uses
- migrated from RQ to Celery, fixed a nasty memory leak in the worker pool that had been open as a ticket for over a year

### Backend Developer, Harrowgate Systems
2019-2022, Toronto
- built out multi-tenant architecture (schema-per-tenant in postgres) for a SaaS logistics product, scaled to 300+ tenants
- owned the Django REST Framework API layer, added rate limiting, API versioning
- wrote the disaster recovery plan for the DB layer (backups, point in time recovery testing) after a close call with a bad migration
- worked closely w/ frontend team (React) but mostly stayed backend
- reduced AWS spend ~25% by right-sizing RDS instances and cleaning up orphaned resources

### Software Engineer - Caldwell & Voss Digital
2017-2019
- first real backend job, joined as the 2nd engineer on a small team
- built internal tools in Django for ops team, inventory tracking mostly
- learned postgres the hard way (production incident w/ a missing index that took down search for 3hrs, never forgot it)
- some early exposure to AWS, deployed via fabric scripts (yes, fabric, it was a different time)

## Education
**B.Sc. Computer Science** - University of Waterloo, 2013-2017

## Other
- occasionally speak at local Toronto python meetups
- open source: minor contributions to a couple django ecosystem packages, nothing major
