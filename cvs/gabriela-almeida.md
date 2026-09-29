# Gabriela Almeida
São Paulo, Brazil (Remote) | gabriela.almeida@example.com | github.com/gabrielaalmeida | linkedin.com/in/gabriela-almeida-ai

## Summary
Junior AI Research Engineer with ~1 year of experience designing and running large-scale LLM evaluation pipelines. Skilled in Python, distributed experiment orchestration, and building reproducible benchmarking harnesses for generative model quality, safety, and robustness. Comfortable working independently in a remote, cross-timezone research team.

## Skills
- **LLM Evaluation:** prompt-based benchmarking, rubric and pairwise judge design, hallucination/factuality scoring, regression suites for model releases
- **Programming:** Python (pandas, NumPy, asyncio), Bash scripting, Git
- **ML Tooling:** PyTorch (applied), Hugging Face Transformers & Datasets, vLLM for batched inference
- **Experiment Infrastructure:** SLURM job scheduling, Docker, Weights & Biases, distributed multi-GPU experiment runs
- **Data:** SQL, large-scale dataset curation and deduplication, statistical analysis of eval results
- **Other:** technical writing, experiment reproducibility practices, English (fluent), Portuguese (native)

## Work Experience

### AI Research Engineer, Junior — Tucano Cognitive Systems (Remote, São Paulo, Brazil)
*March 2025 – Present*
- Built and maintained an internal LLM evaluation framework used to benchmark 15+ candidate model checkpoints per release cycle across accuracy, factuality, and instruction-following axes
- Designed a pairwise preference judging pipeline using a secondary LLM-as-judge setup, improving inter-annotator agreement correlation from 0.61 to 0.78 against human ratings
- Ran large-scale batched inference experiments (up to 500K prompts per sweep) using vLLM on multi-GPU SLURM clusters, cutting evaluation turnaround time by 40%
- Automated results dashboards in Weights & Biases, giving the research team same-day visibility into regressions after each training run
- Collaborated with a distributed team across three time zones to prioritize evaluation coverage for high-risk model behaviors

### Research Intern, Machine Learning — Instituto Curupira de Dados (São Paulo, Brazil)
*July 2024 – February 2025*
- Assisted in curating and cleaning a 2M-document text corpus for downstream fine-tuning experiments, writing dedup and filtering scripts in Python
- Contributed test cases to an early internal benchmark suite for open-source LLM comparison
- Presented findings from a small-scale evaluation study on summarization faithfulness to the research group

## Education
**B.Sc. in Computer Science**
Universidade Federal de Itapemirim — São Paulo, Brazil
*2021 – 2024*
- Relevant coursework: Machine Learning, Natural Language Processing, Distributed Systems, Statistics
- Undergraduate thesis: "Evaluating Faithfulness in Automatically Generated Summaries"
