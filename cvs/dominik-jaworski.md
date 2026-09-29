# Dominik Jaworski
Warsaw, Poland (remote) | dominik.jaworski@example.com | +48 601 223 998 | linkedin.com/in/dominikjaworski-ai

## Summary
Principal-level AI Research Engineer, 16y total, last ~7 focused almost entirely on LLM evaluation at scale -- building eval harnesses, benchmark suites, human+model-graded pipelines, statistical significance tooling for A/B'ing model checkpoints. Python everywhere. Comfortable owning eval infra from data collection through dashboards through the actual go/no-go recommendation to leadership. Also did a decade of more classical ML/NLP before the LLM stuff took over, so I have the pre-transformer scars too. Remote-first, based Warsaw, happy to overlap US or EU hours.

## Skills
- LLM evaluation (automatic + human-in-the-loop), rubric design, pairwise preference pipelines, contamination checks
- Python (16y), numpy/pandas/polars, pytest, asyncio for eval fan-out at scale
- large-scale experimentation - orchestration across thousands of GPU-hours, Slurm and k8s job queues
- statistics: bootstrap CIs, power analysis, Elo/Bradley-Terry for model ranking
- PyTorch, JAX (some), HF transformers/datasets/evaluate
- distributed data pipelines - Spark, Ray, Airflow
- prompt/response logging infra, PII scrubbing, eval dataset versioning (DVC)
- SQL, some Go for infra glue, bash
- earlier career: classic NLP (CRFs, topic models), C++ for perf-critical scoring code

## Experience

### Principal AI Research Engineer -- Fenrisdata Labs (Warsaw, remote) | 2021 - present
- built the company's central LLM eval harness from scratch, now run against every model checkpoint before release, ~40 benchmark suites incl. internal red-team sets
- led migration from single-machine eval scripts to a Ray-based distributed runner - cut a full eval sweep from ~30h to under 3h
- designed pairwise human-preference collection pipeline (crowdworkers + internal annotators), Bradley-Terry ranking, this became the primary signal for model promotion decisions
- caught a subtle contamination issue where held-out eval set had leaked into a pretraining crawl - saved what would've been a very embarrassing benchmark claim
- mentored 4 junior researchers, ran the eval guild (cross-team working group), wrote most of the internal eval style guide (still in use, occasionally ignored)

### Senior Research Engineer -- Kaskadion AI (Berlin, relocated then went remote) | 2016 - 2021
- large-scale experiments across ~200 model variants for a multilingual NLP product, mostly pre-transformer then transitioned team onto BERT-family models around 2019
- built the experiment tracking system before MLflow was good enough internally, later migrated onto MLflow once it caught up
- owned data pipeline for training corpora - dedup, language ID, quality filtering, this fed both training and later became basis for eval holdouts
- occasional on-call for the scoring service, latency SLA work, not glamorous but paid the bills

### ML Engineer -- Vironova Systems (Warsaw) | 2010 - 2016
- early years mostly CRF-based sequence tagging, topic models, feature engineering for a document classification product
- ported a chunk of scoring logic to C++ for a latency-sensitive path, ~8x speedup
- first exposure to "eval" in the informal sense - manually reviewing model outputs weekly, long before it was its own discipline

## Education
- MSc, Computer Science -- Warsaw University of Technology, 2010
- (some coursework toward a PhD, didn't finish - industry pulled harder)
