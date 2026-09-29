# Yusra Ibarra
Sydney, NSW (hybrid) | yusra.ibarra@example.com | +61 4XX XXX XXX | linkedin.com/in/yusraibarra

## Summary
Staff-level Data Engineer, 12+ yrs, builds + owns large scale batch/streaming pipelines - Spark heavy, orchestration in Airflow, transformation layer standardised on dbt. done everything from greenfield lakehouse builds to untangling legacy warehouse spaghetti. comfortable being the tech lead on cross-team data platform initiatives, mentoring, on-call, cost optimisation, the lot. Sydney based, hybrid (2-3 days office), open to some travel.

## Skills
- **Big data / processing:** Spark (PySpark + Scala), Spark SQL, Databricks, EMR, Hadoop (legacy exposure), Kafka, Flink (basic)
- **Orchestration:** Airflow (DAG authoring, custom operators, Airflow 2.x TaskFlow, Astronomer), some Dagster exposure
- Transform/modelling: dbt (core + cloud), dimensional modelling, medallion architecture, data vault (partial)
- Cloud: AWS (S3, Redshift, Glue, EMR, Lambda), GCP (BigQuery, Dataproc) - mostly AWS in recent roles
- Languages: Python (primary), SQL (expert), Scala (intermediate), some Java
- Other: Terraform, Docker, CI/CD (GitHub Actions, Jenkins), Great Expectations / dbt tests, Snowflake, Kimball, git

## Experience

### Staff Data Engineer — Bindlewood Analytics (Sydney) | 2021 - Present
- lead the migration of ~40 legacy cron+bash ETL jobs onto Airflow, cut failure rate from ~15%/wk to <2%
- redesigned core Spark ingestion layer (was single giant job, 6hr runtime) into partitioned incremental jobs, runtime down to ~50 min, saved approx $18k/mo in cluster spend
- introduced dbt as the transform standard across analytics eng team - owns the dbt style guide, macros library, CI checks
- staff-level responsibilities: architecture review board, interviewing, on-call roster design, quarterly platform roadmap
- mentored 4 mid-level engineers, two promoted to senior since
- worked directly with Head of Data + exec stakeholders on data platform strategy

### Senior Data Engineer — Harrowgate Digital | 2017 - 2021
- built out streaming pipeline (Kafka -> Spark Structured Streaming -> Redshift) for near-real time fraud signals, sub 5 min latency
- owned Airflow deployment from scratch (was previously just cron jobs and prayers), ~120 DAGs by time I left
- drove adoption of dbt from nothing, migrated ~200 SQL transform scripts
- built internal data quality framework on top of Great Expectations, caught several exec-facing reporting errors before they shipped
- on call rotation lead for 2 yrs

### Data Engineer — Copperfield Logistics Group | 2014 - 2017
- built ETL pipelines (Python + SQL, later Spark) for logistics/warehouse data, moved from on-prem SQL Server to AWS
- wrote custom Airflow operators for internal file-transfer + SFTP ingestion patterns still in use today (as far as i know)
- supported BI team's Tableau reporting layer, dimensional modelling work
- early exposure to Hadoop/Hive cluster maintenance (not much fun, glad that era ended)

### Junior Data Engineer / BI Developer — Fenwick & Rourke Pty Ltd | 2013 - 2014
- first job out of uni, SQL Server ETL + SSRS reports, maintained nightly batch jobs
- picked up Python here, wrote scripts to replace manual Excel reporting processes

## Education
**Bachelor of Computer Science** — University of New South Wales (UNSW), Sydney — 2009-2013

## Certifications (misc, some may be lapsed)
- AWS Certified Data Analytics - Specialty (2019, prob needs renewal)
- Databricks Certified Data Engineer Associate
