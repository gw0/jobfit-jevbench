# Wiebke Voßkühler
Berlin, Germany (remote) | wiebke.vosskuhler@example.com | +49 176 5533 1042 | linkedin.com/in/wvosskuhler

## Summary
Principal AI Research Engineer, 16 yrs total (started in classic NLP/statistical MT before the deep learning wave, then speech, then -- since 2019 -- almost entirely LLM eval and large scale experiment infra). I care most about making eval numbers actually mean something -- have seen too many teams ship on a benchmark that was silently contaminated or just badly powered. Comfortable owning eval strategy end to end: harness design, statistical significance, dataset curation, and the Python/infra to run thousands of variants overnight. Remote-based in Berlin, have worked distributed for a decade, prefer async but will do CET-core-hours calls.

## Skills
- LLM evaluation (human + automatic, pairwise & pointwise, rubric design, contamination checks, statistical power analysis)
- Python (10+ yrs) -- pandas, numpy, asyncio for eval pipelines, some Rust for perf-critical bits when Python wasn't enough
- large-scale experimentation: A/B and multi-armed setups for model comparisons, distributed job orchestration (Ray, Slurm, also homegrown queueing when neither fit)
- prompt/response logging & analysis pipelines, embeddings-based clustering of failure modes
- PyTorch, some JAX (mostly reading not writing), HF transformers, vLLM for eval-time serving
- experiment tracking: W&B, MLflow, and a lot of just... spreadsheets when deadlines were tight, not proud of it but it's true
- SQL, decent at it, not an expert; Docker/K8s enough to not need to ask infra team every time
- people: mentored ~6 junior/mid researchers over the years, run reading groups, write internal eval postmortems that people actually read (or so I'm told)

## Work Experience

### Principal AI Research Engineer -- Moltrave Systems (Berlin, remote), 2021-present
- built the eval harness that is now used company-wide across 4 model lines, ~40k evals/week at peak during a release crunch
- caught a benchmark contamination issue (training data overlap with a widely used reasoning eval) that would've shipped a misleading model card -- flagged it, delayed launch by 9 days, was the right call
- designed statistical significance tooling (bootstrap + effect size, not just p-values) after watching a launch decision get made off n=40 samples, never again
- ran large-scale ablation sweeps (300+ configs) for a context-length scaling study, cut compute cost 35% by killing runs early via a custom early-stopping heuristic on eval curves
- mentoring: two direct reports promoted to senior in my time there

### Senior Research Engineer, NLP Eval -- Harkonnen Labs (remote, contractor then FTE), 2016-2021
Was hired originally for MT eval (BLEU/METEOR-era) and the team pivoted hard into neural + eventually LLM eval around 2019, whiplash but good whiplash.
- owned the human-eval vendor pipeline (annotator guidelines, IAA tracking, QC) for 3 years
- built internal tool for pairwise model comparison at scale, adopted by 5 other teams
- co-authored an internal paper (never published externally, IP reasons) on eval metric drift over model versions

### NLP Engineer -- Dunmore Analytics (Hamburg, on-site), 2010-2016
earlier career, less eval-specific, more general applied NLP
- built statistical MT and later early neural MT systems for a logistics client
- first exposure to large scale experiment infra here, cluster job scheduling before it was cool

## Education
- Dipl.-Ing. Computer Science, Technische Universität Hamburg-Harburg, 2004-2010 (diploma, pre-Bologna-conversion at that school)
- occasional coursework/certs since then (Coursera stats for ML stuff, doesn't feel worth listing individually)
