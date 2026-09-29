---
company: Fireworks AI
title: IT DevOps Engineer
location: San Mateo
url: https://jobs.ashbyhq.com/fireworks/a83a980e-9e31-489b-964c-abd6cd11dff2
posted_at: 2026-09-15
---

**About Us:**
-------------

Fireworks is the platform for specialized intelligence, enabling companies to build, train, and serve AI models tailored to their own data, workflows, and products. Founded by the team behind PyTorch and backed by AMD, Atreides, Benchmark Capital, Index Ventures, Lightspeed, NVIDIA, Sequoia Capital, and TCV, Fireworks powers production AI with hundreds of state-of-the-art open models across text, image, embedding, audio, and multimodal workloads. Today, Fireworks is a Series D company valued at $17.5 billion, bringing together an ambitious, collaborative team that's building the future of enterprise AI.

**About the Role**

Fireworks serves billions of API requests a day, and the work of getting a model from merged to serving still passes through too many hands. Deploys wait on someone to run a step. Alerts land in a channel and wait for a human to route them. Provisioning a customer means clicking through three systems in the right order. Every one of those is a workflow nobody has written down as code yet.

You will own the systems that close those gaps. That means running our CI/CD and infrastructure-as-code stack, and it also means building the automation layer above it — the orchestrated workflows, webhooks, and API integrations that connect model deployment to the internal systems around it. You will be the person the team asks about our API surface: how it authenticates, how it rate-limits, what breaks under load. You will spend as much time in n8n and Python as in Terraform and Kubernetes.

The role sits in IT and operates as a peer to Platform Engineering — you co-own the delivery path rather than filing requests against it, and you carry decisions on their merits rather than through an org chart. High autonomy, few templates, and the freedom to choose tools that earn their place.

**What You’ll Own**

**ORCHESTRATE THE AUTOMATION LAYER**

* **Workflow architecture.** Design, deploy, and maintain mission-critical workflows in n8n or an equivalent orchestrator, with real error-handling paths rather than happy-path scripts.
* **Operational automation.** Replace manual runbook steps — engineering alerts, product provisioning, routine ops — with event-driven workflows that route themselves.
* **Custom nodes and logic.** Build the custom nodes, webhooks, and functions the off-the-shelf integrations do not cover.

**OWN THE API SURFACE**

* **Integration design.** Design and secure internal and external integrations across REST, GraphQL, and webhooks, including OAuth2, mTLS, and API-key auth.
* **High-throughput data flows.** Handle rate limits, retries, backpressure, and payload validation so integrations degrade predictably instead of silently.
* **Contract testing.** Mock, test, and version APIs so a downstream change surfaces in CI rather than in production.

**CO-OWN DELIVERY INFRASTRUCTURE**

* **CI/CD for model deploys.** Co-own the deploy pipelines with Platform Engineering as a peer — tuned for fast AI model and infrastructure rollouts with zero downtime.
* **Infrastructure as code.** Provision multi-cloud environments in Terraform, OpenTofu, or Pulumi — reviewed, reproducible, no console drift.
* **Containers and Kubernetes.** Package and scale GPU and CPU workloads on EKS, GKE, or AKS with attention to utilization, not just uptime.

**MAKE FAILURE VISIBLE**

* **Observability.** Instrument pipelines and workflows with Prometheus, Grafana, or Datadog so a stalled automation pages someone before a customer notices.
* **Self-healing paths.** Build retry, fallback, and escalation logic into workflows so the common failures resolve without a human.
* **Documentation as infrastructure.** Keep the workflow map and runbooks current enough that someone else can debug your automation at 2am.

**What We’re Looking For**

* **Two languages, deep.** 6+ years building production systems, with strong Python plus JavaScript or TypeScript — clean, modular, async code, not glue scripts.
* **Workflow orchestration.** Hands-on expertise with n8n, Temporal, Make, or a comparable platform, including custom nodes and error-handling design.
* **API fluency.** You reason in payloads and endpoints: REST and GraphQL, webhooks, gateways, proxying, and the auth mechanisms behind them.
* **CI/CD ownership.** You have owned pipelines in GitHub Actions, GitLab CI, or Jenkins through real scale and real incidents.
* **Cloud and containers.** Production Kubernetes on AWS or GCP, with Terraform as your default way to change infrastructure.
* **Automation instinct.** Your reflex after fixing something twice is to make the third time impossible.
* **Standing across teams.** You have held technical ownership that crossed a team boundary, and earned it on judgment rather than reporting line.
* **Comfort with speed.** You enjoy that the tooling landscape in generative AI shifts every quarter, and you evaluate new tools without chasing them.

**Why Fireworks?**
------------------

* Solve Hard Problems: Tackle challenges at the forefront of AI infrastructure, from low-latency inference to scalable model serving.
* Build What’s Next: Work with bleeding-edge technology that impacts how businesses and developers harness AI globally.
* Ownership & Impact: Join a fast-growing, passionate team where your work directly shapes the future of AI—no bureaucracy, just results.
* Learn from the Best: Collaborate with world-class engineers and AI researchers who thrive on curiosity and innovation.

*Fireworks AI is an equal-opportunity employer. We celebrate diversity and are committed to creating an inclusive environment for all innovators.*
