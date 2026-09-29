---
company: Vapi
title: Member of Technical Staff, DevOps
location: San Francisco
url: https://jobs.ashbyhq.com/vapi/2d702840-a588-4273-8b98-49ed815c0c50
posted_at: 2026-06-03
---

**Vapi (/ˈVɑːpi/):**

* Voice AI that resolves, not transfers
* Powering 1 billion calls for companies like Amazon Ring, Intuit, ServiceTitan, and New York Life
* Trusted by 1 million developers building the future of voice agents
* Backed by Peak XV, Bessemer, Kleiner Perkins, M12, Y Combinator, and more with $72M raised
* [Try talking to Vapi now!](https://vapi.ai/)

**Why We’re Hiring This Role:**
-------------------------------

* Three of our worst recent incidents — Nov 29 config rollout, Dec 23 duplicate messages, Oct 13 egress proxy — were resolved by rollback. That’s the SDLC gap this role closes. Vapi engineers are your users, and the deploy pipeline, preview environments, cell-creation tooling, and oncall tooling are products with SLAs, docs, and feedback loops.
* You’ll own progressive delivery (canary, blue/green, automated rollback, soak periods), the GitOps story across multiple clusters and regions, and the on-demand environment tooling that’s on the Q3 roadmap. Success is measured by how fast every other team ships safely.

**What You’ll Do:**
-------------------

* **30 Day**: Get fluent in the Pulumi stacks, the ArgoCD setup, and GitHub Actions pipelines. Sit with engineers from agents and FDE teams to find the top 3 deploy pain points. Land a quality-of-life improvement to the deploy pipeline.
* **60 Day**: Own progressive delivery end-to-end — canary, automated rollback, soak — for at least one critical service path. Ship the first version of cell-creation tooling or preview environments. Make the deploy pipeline measurably faster (lead time, MTTR for failed deploys).
* **90 Day**: Roll out progressive delivery as the default across services. Establish SLAs and a feedback loop with engineering teams. Own the developer-platform roadmap and partner with Infra and SRE on cell creation, multi-region rollouts, and oncall tooling.

**Who You Are:**
----------------

***Must-haves***

* You have a platform-as-a-product mindset — you treat internal engineers as customers, with SLAs, docs, and feedback loops, not tickets and ad-hoc help.
* You’ve operated Pulumi (TypeScript) or Terraform at scale (40+ stacks, multi-region) and you’ve felt the pain when IaC sprawl gets ahead of you.
* You’ve run ArgoCD or equivalent GitOps for deploying applications across multiple clusters.
* You’ve built progressive delivery in production — canary, blue/green, automated rollback, soak periods. You can describe a real rollout that automated rollback caught.
* You’ve designed CI/CD pipelines (GitHub Actions preferred) for many services and Dockerfiles, not just one repo.
* You’ve built deploy tooling for on-demand environments — preview envs, dev deployments, or cell creation.

***Nice-to-haves***

* You’ve written Go for platform services (Vapi’s canary-manager is Go).
* You’ve operated developer platforms at a mid-stage infra-heavy company or a DevEx team at a larger shop.

***Tech stack you’ll work in***

* Languages: TypeScript (primary, for Pulumi and tooling), Go (for canary-manager and platform services), Bash.
* IaC: Pulumi (TypeScript) at scale (40+ stacks across regions), Terraform.
* GitOps and deploy: ArgoCD (multi-cluster), GitHub Actions, 15+ Dockerfiles.
* Progressive delivery: canary, blue/green, automated rollback, soak periods (canary-manager Go service).
* Orchestration: Kubernetes on EKS (multi-cluster, multi-region).
* Vapi services you’ll touch: canary-manager, cell-creation tooling, preview env tooling.

***Where you likely come from***

* Vercel, Render, Railway, Fly, Temporal, Cockroach (mid-stage infra-heavy), or DevEx/Platform teams at Stripe, Shopify, Airbnb, or Block.
* Weak fit: classic AWS sysadmin, or someone whose CI/CD experience is mostly Jenkins GUI-level.
