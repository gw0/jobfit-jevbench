---
company: LawZero
title: Platform Engineer
location: Montreal
url: https://job-boards.greenhouse.io/lawzero/jobs/4385557009
posted_at: 2026-09-24
---

Founded by Yoshua Bengio, LawZero is a nonprofit organization focused on AI safety. In charge of technology, the IT department oversees Cybersecurity, End User support, and the management of the compute environment used to achieve our mission.

You will own the platform layer that sits between our people and the GPU infrastructure: CI/CD pipelines, Kubernetes clusters, cloud environments, and the standards that keep them consistent and secure. This is a hands-on role on a small IT team, with a wide surface area and a lot of room to shape how things are built.

**Key responsibilities**

* Design, deploy, and run Kubernetes clusters for research workloads, including autoscaling, network policies, and workload isolation, both on-premise and in the cloud.
* Define, communicate, and enforce best practices for CI/CD pipelines: automated builds, tests, container image creation, and deployments, with security scanning and provenance built into the pipeline rather than bolted on.
* Implement and manage internal services supporting our research and data teams, providing them with a reliable, secure platform. Examples include artifacts registry, Container registries, etc.
* Manage our cloud environments as code (Terraform or equivalent): accounts, networking, identity, secrets, and cost visibility.
* Define and champion platform standards. Base images, deployment patterns, environment promotion, so researchers and engineers ship without reinventing the plumbing each time.
* Work at the boundary between Kubernetes and our HPC cluster: containerized workflows that need to interface with the ones running on Slurm, shared storage access, and tooling that makes both environments feel coherent to a researcher.
* Build observability into the platform: metrics, logs, traces, and alerts that make failures obvious and debugging quick. We currently use Prometheus and Grafana.
* Embed security controls into everything above: least-privilege IAM, secrets management, supply-chain integrity for dependencies and images, network segmentation, and audit trails.
* Document what you build and automate what you repeat. Reduce the number of things that only work because one person remembers how.
* Participate in incident response for platform services, and in the post-incident work that keeps the same problem from recurring.

**Skills and qualifications**

* **Experience**

  + 3–5 years in platform engineering, DevOps, SRE, or a closely related infrastructure role.
  + Production experience with Kubernetes. Not just deploying to it, but operating it: upgrades, RBAC, networking, storage, troubleshooting a cluster that is misbehaving.
  + Solid CI/CD experience with a modern toolchain (GitHub Actions, GitLab CI, Jenkins, or similar), including building pipelines from scratch.
  + Experience architecting, deploying, and maintaining a GitOps workflow is an asset.
  + Hands-on experience with at least one major cloud provider (AWS, GCP, or Azure) and infrastructure as code. Familiarity with on-premise infrastructure is a plus.
  + Strong Linux fundamentals and comfort with a scripting or programming language such as Python, Go, or Bash.
  + Working knowledge of containers beyond the basics: image layering, registries, runtime security, minimal base images.
  + Fluency in written and spoken English, French is a strong asset.
  + Experience supporting ML or research workloads: GPU scheduling, distributed training, large datasets, high-throughput storage is an asset.

  **Security mindset**

  This matters as much as the technical checklist. We are looking for someone who:

  + Thinks about the blast radius of a change before making it, and about who could abuse an access path that was opened for convenience.
  + Treats secrets, credentials, and access as first-class design concerns rather than afterthoughts.
  + Understands supply-chain risk in a build pipeline: dependency provenance, image signing, artifact integrity, what a compromised runner could reach.
  + Applies least privilege by default and can explain to a researcher why a control exists, without being obstructive about it.
  + Has practical familiarity with identity and access management, network segmentation, and secure defaults in cloud environments.

  **Ways of working**

  + Comfortable being the person who owns a domain end to end in a small team, without a large org to hand things off to.
  + Able to work with researchers whose priorities are speed and flexibility, and find solutions that are both secure and genuinely usable.
  + Clear written communication. You will write documentation and design notes that others depend on.
  + Capable of managing multiple priorities and adjusting to a frequently changing environment.

**What we offer**

* The opportunity to contribute to a unique mission with a major impact
* Comprehensive health benefits
* A minimum of 20 days vacation per year upon start
* A minimum retirement savings employer contribution of 4%
* Generous flexible benefits designed to contribute to your well-being
* A team of passionate experts in their field
* A collaborative and inclusive work environment with offices in the heart of Little Italy, in the trendy Mile-Ex district, close to public transportation

**About LawZero**

LawZero is a non-profit organization committed to advancing research and creating technical solutions that enable safe-by-design AI systems. Its scientific direction is based on new research and methods proposed by Professor Yoshua Bengio, the most cited AI researcher in the world. Based in Montreal, LawZero’s research aims to build non-agentic AI that learns primarily to understand the world rather than to act in it, giving truthful answers to questions based on transparent and externalized probabilistic reasoning. Such AI systems could be used to accelerate scientific discovery, to provide oversight for agentic AI systems, and to advance the understanding of AI risks and how to avoid them. LawZero believes that AI should be cultivated as a global public good—developed and used safely towards human flourishing. For more information, visit [www.lawzero.org](https://www.lawzero.org/)

**You belong here**

At LawZero, diversity is important to us. We value a work environment that is fair, open and respectful of differences. We welcome applications from highly qualified individuals interested in working towards our mission in a respectful, inclusive and collaborative setting.

*Your personal information will be collected and processed by LawZero to evaluate your application for employment in compliance with our [Privacy Policy](https://lawzero.org/en/website-privacy-notice). Under privacy laws in force in your country of residence, you may have several privacy rights, such as to request access to your personal information or to request that your personal information be rectified or erased. Details on how you can exercise your rights can be found in our Privacy Policy.*
