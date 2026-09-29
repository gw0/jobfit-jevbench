# Victoria Yusuf
Staff Data Engineer | Lagos, Nigeria (Remote) | victoria.yusuf@example.com | +234 803 555 0192 | linkedin.com/in/victoriayusuf-de

## Summary
12 yrs data engineering, distributed systems, batch+streaming, lots of pipeline firefighting across fintech and logistics domains. Staff-level - mentoring, architecture review, on-call rotations, cost optimization projects, migrations (legacy Hadoop -> Spark on k8s), dbt adoption from scratch at 2 orgs. Comfortable owning ambiguity, dont need detailed specs, will figure it out and document after. Nigeria based, worked with distributed teams across EU/US timezones for 6+ yrs so async-first, calls kept minimal.

## Skills
- **Core**: Apache Spark (PySpark + Scala, batch & structured streaming), Airflow (2.x, custom operators, dynamic DAGs, KubernetesExecutor), dbt (Core + Cloud, macros, packages, exposures)
- Warehouses: Snowflake, BigQuery, Redshift (legacy)
- Languages: Python (primary), SQL, Scala (competent not expert), some Go for tooling
- Infra: Kubernetes, Terraform, Docker, AWS (EMR, MWAA, S3, Glue), GCP (Dataproc, Composer)
- Streaming: Kafka, Kinesis, Debezium/CDC
- Other: Great Expectations, dbt-tests, Monte Carlo (data obs), Github Actions/CI for data, cost governance/FinOps for data platforms
- Soft: mentoring juniors->seniors, incident postmortems, cross-team architecture reviews, stakeholder translation (exec <-> eng)

## Experience

### Staff Data Engineer, Baobab Freight Systems (remote, HQ Rotterdam) - 2021 - Present
Lead for the core data platform team (5 engineers, 2 direct reports). Migrated entire batch layer off cron+bash scripts onto Airflow/Spark, this was in bad shape when I joined honestly.
- rebuilt ingestion for 40+ source systems (ERP, telematics, 3rd party freight APIs) into a single Spark-based lakehouse, cut pipeline runtime from ~14h to under 3h
- introduced dbt for all transformation layer, ~600 models now, enforced testing + docs as part of PR gate, arguement with data science team initially but they came around
- designed on-call rotation + runbook system, reduced P1 pipeline incidents by 70% (measured over 2 yrs)
- owns cost governance for data platform, saved ~$380k/yr through spot instance usage + partition pruning + right-sizing EMR clusters
- mentored 3 mid-level engineers to senior

### Senior Data Engineer, Kestrel Pay (Lagos / remote) - 2017 - 2021
Fintech, payments settlement + fraud data pipelines. High stakes, regulator involved, had to be careful.
- built near-real-time fraud feature pipeline using Kafka + Spark Structured Streaming, sub-5-min latency for feature freshness
- Airflow adoption from zero - was previously all manual SQL scripts run by analysts (yes really)
- worked directly w/ compliance team on data lineage requirements for CBN reporting, built lineage tracking on top of dbt manifest
- on-call, some very late nights during 2019 settlement outage, learned a lot about idempotency the hard way

### Data Engineer, Savannah Analytics Ltd (Lagos) - 2014 - 2017
First "real" data role, small consultancy, worked across multiple client projects simultaneously.
- built ETL pipelines (mostly Python + SQL, pre-Spark days for me) for retail + telco clients
- introduced version control + basic CI to a team that had none, small thing but changed how we worked
- some Hadoop/Hive exposure here, legacy stuff, glad thats mostly gone now

## Education
- B.Sc. Computer Science, University of Lagos - 2010-2014
- various certs over the years - AWS Data Analytics Specialty, Databricks Spark cert, dbt Certified Developer (renewed 2024)

References available on request. Open to consulting/advisory work alongside FT role.
