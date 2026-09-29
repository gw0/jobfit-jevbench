# LAKSHMI PRABHAKARAN
Senior Data Engineer | Bangalore, India (on-site) | lakshmi.prabhakaran@example.com | +91-98452-XXXXX | linkedin.com/in/lakshmiprabhakaran-de

## Summary
Data engineer, 8 yrs, heavy focus on Spark/Airflow/dbt pipelines at scale, built and re-built ingestion + warehousing stacks from scratch twice. comfortable owning things end to end - infra, pipeline code, stakeholder reporting, on-call. Known for fixing other ppls broken DAGs at 2am. looking for senior/staff IC roles, NOT people management.

## Skills
- **Big data**: Apache Spark (PySpark mostly, some Scala), Hadoop/HDFS legacy exposure, Databricks
- Orchestration - Airflow (2.x, also old 1.10 experience), some Dagster poking around
- dbt (core + cloud), SQL (advanced - window fns, CTEs, query plans)
- Cloud: AWS (S3, EMR, Redshift, Glue), GCP BigQuery (basic), a little Azure
- Python (pandas, pyspark, some Go for tooling scripts), Java (old, rusty)
- Kafka, Kinesis for streaming bits; Docker/Kubernetes for deployment
- CI/CD - Jenkins, GitHub Actions
- Data modeling - kimball star schemas, also slowly-changing-dimension stuff, dbt tests/docs

## Experience

### Senior Data Engineer — Vellamora Technologies (Bangalore)
*Jun 2021 – Present*
- rebuilt entire batch ingestion layer using Spark on EMR, replaced legacy Sqoop jobs -> cut runtime from ~6hrs to 90 min
- Owns Airflow deployment for whole data platform (40+ DAGs), migrated from 1.10 to 2.x with zero downtime (mostly)
- introduced dbt for transformation layer, wrote 200+ models, added testing which basically didn't exist before
- mentoring 3 junior engineers, doing design reviews, also still write code myself daily
- reduced infra cost by ~30% by right-sizing EMR clusters and moving some jobs to spot instances

### Data Engineer — NimbusStack Analytics (Bangalore)
2018 - 2021
- built streaming pipeline using kafka + spark structured streaming for clickstream data, ~2M events/day
- Wrote airflow DAGs for daily/hourly batch jobs, orchestrating spark jobs + downstream reporting
- worked closely with analytics team to define metrics, built semantic layer (before dbt was cool here)
- did the on-call rotation, fixed prod incidents, wrote runbooks nobody read
- Migrated on-prem hadoop cluster workloads to AWS EMR - big project, ~8 months

### Software Engineer (Data) — Kredence Systems Pvt Ltd
*2016-2018*
- early career, worked on ETL scripts (python + cron, no orchestration framework lol)
- built internal reporting dashboards, some Tableau, mostly just sql views
- learned spark here on legacy hadoop cluster, self taught mostly
- also did general backend dev work - REST APIs in Django, not really data-specific but useful context

## Education
- B.E. in Computer Science, R.V. College of Engineering, Bangalore — 2016
- Certifications: Databricks Certified Data Engineer Associate (2022), AWS Certified Solutions Architect - Associate (2020, lapsed)

## Other
- speaks Kannada, Tamil, Hindi, English
- occasionally writes blog posts on medium about spark performance tuning, nobody reads them
