---
company: Vapi
title: Member of Technical Staff, Infrastructure
location: San Francisco
url: https://jobs.ashbyhq.com/vapi/295f5269-1bb5-4740-81fa-9716adc32ad5
posted_at: 2026-05-21
---

**Vapi (/ˈVɑːpi/):**

* Voice AI that resolves, not transfers
* Powering 1 billion calls for companies like Amazon Ring, Intuit, ServiceTitan, and New York Life
* Trusted by 1 million developers building the future of voice agents
* Backed by Peak XV, Bessemer, Kleiner Perkins, M12, Y Combinator, and more with $72M raised
* [Try talking to Vapi now!](https://vapi.ai/)

**Why We’re Hiring This Role:**
-------------------------------

* Vapi runs live phone calls — when something breaks, callers hear it. We’re building cell-based, multi-region infrastructure to drive 99.99% call completion, and this hire owns the foundation: multi-cluster Kubernetes on EKS, a stateful data plane (Postgres, Redis, Kafka, Temporal, ClickHouse), Envoy/Cilium networking, and multi-region Kafka on MSK across EU and ANZ.
* You’ll write Go for control-plane services like cluster-manager, traffic-control-plane, and environment-manager, and you’ll set the bar for how Vapi runs stateful workloads at scale.

**What You’ll Do:**
-------------------

* **30 Day**: Ramp on the cell-based architecture, the regional EKS clusters (backend / networking / persistence / monitoring / models / kafka), and the Pulumi stacks. Shadow oncall, walk recent incidents (Envoy response flags, conntrack drops, cross-zone LB target resets), and own a first scoped infra change end-to-end.
* **60 Day**: Take ownership of one core domain — e.g., multi-region MSK (regional topic naming, Pulumi drift, compliance constraints), the Postgres/Neon consolidation path, or programmatic cluster creation via Cluster API. Ship a control-plane improvement in Go and drive a measurable reliability or capacity win.
* **90 Day**: Lead a roadmap pillar of the cell-based build-out: a new region, a stateful workload migration, or unblocking the SIP gateway SPOF. Operate as the infra owner other teams pull in for design reviews, and set the standards (runbooks, failure-domain modeling, capacity targets) the next infra hires inherit.

**Who You Are:**
----------------

* You’ve run multi-cluster Kubernetes on EKS in production — backend, networking, persistence, monitoring, models, and kafka clusters per region — and you’ve used Cluster API or similar for programmatic cluster creation.
* You’ve operated a stateful data plane (Postgres, Redis, Kafka, Temporal, etcd, ClickHouse) at scale — you’ve sharded it, migrated data between instances, and lived with the consequences.
* You’re fluent in Envoy and Cilium/eBPF. You’re comfortable debugging Envoy response flags, conntrack drops, and cross-zone LB behavior. VPC/NAT/Cloudflare alone isn’t enough.
* You’ve run multi-region Kafka on MSK in production — not just Kafka. You’ve dealt with regional topic naming, MSK Pulumi drift, and compliance constraints.
* You write Go for control-plane services. Vapi’s cluster-manager, traffic-control-plane, and environment-manager are all Go, and you’re comfortable owning code in that stack.
* Bonus: SIP / RTP / telephony background. The Nov 7 SIP gateway SPOF is still unsolved, and a telephony-savvy infra hire unblocks that roadmap item.
* Bonus: cell-based / shard architecture experience — Shopify pods, AWS cell-based reference arch, Slack shards, or equivalent. Microservices experience alone isn’t the same.
* You likely come from one of: a company that ran cell-based in prod (Shopify, AWS service teams, Slack); a distributed systems shop (Cockroach, MongoDB, Confluent, Temporal, Redpanda, ClickHouse Inc.); a voice/video/CPaaS company (Twilio, Plivo, Bandwidth, Vonage, LiveKit, [Daily.co](http://Daily.co), Dialpad); an Envoy/service-mesh org (Lyft, Stripe, Airbnb, Pinterest, Isovalent/Cilium); or a streaming-infra team (Confluent, Uber, LinkedIn, Datadog) that ran MSK/Kafka multi-region.

**Why Vapi:**
-------------

* **Generational impact**: Build the human interface for every business
* **Ownership culture**: 70% of the company are previous founders
* **Kind team**: The founders, Jordan and Nikhil, are Canadians
* **Tier-1 Investors**: YC, KP seed, Bessemer Series A

**What We Offer:**
------------------

* **Real stake**: We offer a competitive salary and excellent equity ownership
* **Comprehensive health coverage**: medical, dental, and vision plans
* **Team love**: We love hanging out, and we do quarterly off-sites
* **Flexible time off**: take what you need
* **More**: catered meals, transportation, gym, and a $10k annual L&D budget
