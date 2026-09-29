# Chidinma Oputa
chidinma.oputa@example.com | Lagos, Nigeria (Remote) | github.com/chidinmaoputa | linkedin.com/in/chidinma-oputa

## Summary
Staff AI Research Engineer, ~12 yrs, LLM evaluation + large-scale experiment infra. i build eval harnesses that actually catch regressions before prod does, not vanity benchmarks. comfortable owning eval strategy end to end -- data, metrics, infra, and the org politics of telling a VP their model regressed. python-first but not religious about it. led evals for multiple pretraining + RLHF cycles across 500M-70B param range. remote-based Lagos, worked with teams across US/EU timezones for 8+ yrs so timezone overlap is a non-issue.

## Skills
- **Eval**: harness design, contamination detection, human-eval pipelines, pairwise/Elo, rubric-based LLM-judges, statistical significance testing for noisy benchmarks, regression gating in CI
- **Python**: numpy/pandas/polars, asyncio for high-throughput inference calls, pytest, typing, packaging internal libs
- **Scale**: distributed eval runs (ray, slurm clusters, k8s jobs), sharding large datasets, cost/latency tradeoffs at 10k+ req/min
- **ML**: PyTorch, HF transformers/datasets, RLHF/DPO eval considerations, tokenizer quirks that break evals silently
- misc: SQL, bash, git, occasional Go for perf-critical eval tooling, some Rust dabbling (not production)

## Experience

### Staff Research Engineer -- Vantable AI (2022-Present)
remote, Lagos. small research org, ~40 eng, foundation model + agent evals
- built the eval harness used across all model releases -- covers ~40 internal benchmarks + external suites (MMLU-style, coding, agentic tasks), reduced eval turnaround from 3 days to under 6 hrs
- caught a silent tokenizer regression pre-launch that would've tanked non-English perf by ~15%, saved the launch
- designed LLM-judge rubrics w/ inter-rater reliability checks against human raters (kept judge-human agreement >0.85 kappa)
- scaled eval infra to run 200k+ generations/night across a ray cluster, cut infra cost ~35% via smarter batching
- mentored 4 junior researchers, none of them had eval background before, all shipped independent eval suites within 6mo

### Senior ML Engineer -- Brightloom Systems (2018-2022)
Hybrid, Lagos/London some years
- owned offline eval for recommendation + NLP models, moved team off ad-hoc notebooks to versioned eval pipelines
- built A/B test statistical framework, flagged several false-positive wins before they shipped
- worked closely w/ data eng on large-scale data pipelines (spark, airflow) feeding eval sets
- first at the company to introduce contamination checks between train/eval sets -- found ~8% overlap in a legacy benchmark, quietly fixed

### ML Engineer -- Kesari Analytics (2014-2018)
Lagos
- early career, general ML + some backend. built internal tooling for model monitoring
- python, some Java (legacy systems), SQL heavy
- not eval-focused yet but this is where the experiment rigor habit started, had a good mentor there

## Education
- B.Sc. Computer Science, University of Lagos (2010-2014)
- assorted online coursework / certs over the years (deep learning specializations etc) -- didn't keep careful track honestly, happy to discuss specifics if relevant
