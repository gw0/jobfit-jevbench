# Rohan Jethwa
Toronto, ON (Remote) | rohan.jethwa@example.com | linkedin.com/in/rohanjethwa-ml

## SUMMARY
Principal ML Engineer, 16+ yrs building and shipping large-scale training systems and the infra around them. Started in classic ML/stats, moved into deep learning ~2013, spent the last 8 years mostly heads-down in distributed PyTorch training, model serving, and the MLOps glue that keeps it all from falling over. I like fixing pipelines more than most people like fixing pipelines. Comfortable owning things end to end - data, training, eval, deploy, on-call.

## Skills
- PyTorch (incl. FSDP, DDP, custom autograd), TensorFlow (legacy, don't ask)
- Distributed training - multi-node, multi-GPU, Slurm & Kubernetes based clusters
- MLOps: MLflow, Weights & Biases, Kubeflow, Airflow, custom CI/CD for model artifacts
- Python, Go (for infra bits), some Rust
- Feature stores, vector DBs (FAISS, pgvector), Ray, Dask
- Docker/K8s, Terraform, AWS + GCP
- Mentoring, roadmap ownership, cross-team technical leadership

## Experience

### Principal ML Engineer — Northfield Analytics (Toronto, remote) — 2021–Present
- Rebuilt the entire training platform from a pile of cron jobs into a proper orchestrated system (Kubeflow + Argo), cut model iteration time from ~9 days to under 36 hrs
- own the training infra roadmap for a team of 14 engineers across 3 timezones
- Introduced FSDP for our largest models (>20B params) - reduced GPU-hours per training run by ~40%
- built internal eval harness that's now used company wide, prevented at least 2 bad prod pushes that I know of
- Regularly on-call, wrote the on-call runbook because there wasn't one

### Staff ML Engineer, Cascadia Robotics — 2016 - 2021 (Vancouver -> remote from Toronto starting 2019)
- Led perception model training for warehouse robotics (object detection + tracking), PyTorch + TensorRT for deployment
- Migrated legacy TF1 models to PyTorch, this took way longer than anyone budgeted for (18 months) but paid off
- Built the first MLflow-based experiment tracking setup, previously everyone just used spreadsheets
- managed 2 junior engineers, one now a staff eng elsewhere

### ML Engineer / Data Scientist — Bramwell Systems (Toronto) — 2010-2016
- Started here right out of grad school. Early years mostly classic ML (GBMs, SVMs) for fraud + risk scoring
- Transitioned team onto deep learning around 2013-14 as it became viable, championed early Torch/Theano adoption before PyTorch existed
- built + maintained batch scoring pipelines processing ~40M records/day

## Education
- M.Sc., Computer Science (Machine Learning focus) — University of Toronto, 2010
- B.Sc., Mathematics — Queen's University, 2008

## Other
Occasional conference talks (MLOps meetup Toronto, ~3x), reviewer for a couple of workshop tracks, nothing fancy. Open source: minor contributions to PyTorch distributed docs.
