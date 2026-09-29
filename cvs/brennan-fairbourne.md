# Brennan Fairbourne
Staff Machine Learning Engineer — Austin, TX (Remote) | brennan.fairbourne@example.com | linkedin.com/in/bfairbourne | github.com/bfairbourne

## Summary
12 yrs building + shipping ML systems, last 6 as staff-level IC across training infra and MLOps. PyTorch everything - distributed training, custom loss/data pipelines, also own the tooling that gets models from notebook to prod w/o babysitting. Comfortable owning a system end to end (design, code review, on-call) and mentoring senior engineers along the way. Remote-first, been distributed teams since 2016, Austin based.

## Skills
- **Core:** PyTorch (incl. DDP, FSDP, torch.compile), CUDA basics, Python, some Go for infra glue
- **MLOps/Infra:** Kubernetes, Kubeflow, MLflow, Ray/Ray Train, Airflow, Terraform, Docker
- Model serving: TorchServe, Triton Inference Server, custom gRPC services
- Data: Spark, Parquet/Delta Lake, feature stores (Feast), large scale dataset curation
- Experiment tracking & eval harnesses, A/B infra for model rollouts
- Monitoring - Prometheus/Grafana, drift detection, custom eval dashboards
- Leadership: RFC writing, cross-team tech leadership, hiring panels, mentoring

## Experience

### Staff ML Engineer — Cormorant Analytics (Austin, TX / Remote)
*2021 - Present*
- led redesign of the internal training platform (PyTorch + Ray Train) cutting large-model training time ~40% via better data loading + mixed precision defaults
- built org-wide model registry & rollout tooling (canary + shadow eval) now used by 6 product teams, prevented at least 2 bad-model incidents pre-launch
- owns GPU capacity planning across 3 clusters, drove multi-tenant scheduling changes that reduced idle GPU-hours by ~30%
- mentored 4 mid/senior engineers, ran the ML infra on-call rotation redesign
- wrote the internal RFC standardizing experiment tracking (MLflow) org wide - adopted by 9 teams

### Senior ML Engineer — Halcyon Data Systems
*2017 - 2021*
- Migrated legacy TF1 training pipelines to PyTorch, saving considerable dev velocity, team went from ~2wk to ~3day iteration cycles
- built feature store + online/offline parity checks, cut training-serving skew bugs significantly
- shipped ranking model serving path handling ~15k qps, p99 latency under 40ms
- worked closely w/ data eng on Spark pipelines for label generation at scale (billions of rows)

### ML Engineer — Northgate Research Group
*2014 - 2017*
- built early recommendation models (gradient boosted trees + embeddings), first prod ML system for the company
- set up initial CI for model training jobs, basic model cards / documentation practice adopted later company wide
- collaborated with research scientists translating papers into working prototypes

## Education
**B.S. Computer Science** — University of Texas at Austin, 2014
- coursework emphasis: distributed systems, statistics

## Other
- occasional conference talks (internal + regional meetups) on training infra scaling
- open source: contributor to a couple small PyTorch ecosystem tooling projects (data loading utils)
