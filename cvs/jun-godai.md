## Jun Godai
Tokyo, Japan (hybrid) | jun.godai@example.com | +81-90-xxxx-xxxx

**Staff SRE** - 12+ yrs infra/reliability, k8s+terraform+go mainly, also did a lot of on-call / incident stuff over the years. Based Tokyo, open to hybrid only (3 days office roughly).

### Summary
Reliability engineer, staff level, ~12 yrs total across telecom-adjacent, fintech-ish, and logistics platforms. Built and ran k8s clusters (bare metal AND managed, multi region), wrote a LOT of terraform (probably 200k+ lines across orgs at this point lol), and go for tooling / controllers / operators. Like owning things end to end - paging, SLOs, capacity, the works. Not a fan of ticket-only SRE roles, want hands on infra.

### Skills
- Kubernetes (CKA, admission controllers, custom operators, multi-cluster fleet mgmt, Karpenter, Cilium)
- Terraform (modules, workspaces, drift detection, Terragrunt, some Pulumi exposure)
- Go (controllers/operators via controller-runtime, CLI tooling, gRPC services)
- Observability: Prometheus/Thanos, Grafana, OpenTelemetry, Datadog (prev role)
- CI/CD: ArgoCD, Github Actions, Spinnaker (old job)
- Cloud: AWS (primary), GCP (secondary), some on-prem/VMware
- incident mgmt, postmortems, SLO design, capacity planning
- Japanese (business level), English (fluent)

### Experience

**Staff SRE, Kestrel Mesh K.K.** - Tokyo | 2021-present
- led migration off single-region EKS to 3-region active-active setup, cut regional outage blast radius by a lot (customers barely noticed the last 2 incidents)
- wrote custom go operator for canary rollouts tied into internal metrics pipeline, replaced a flaky bash+jenkins thing that nobody understood
- terraform: consolidated ~40 repos worth of hand-rolled IAM/network configs into shared modules, onboarding new services now takes hours not weeks
- owns SLO framework for 30+ services, quarterly reliability reviews w/ exec staff
- mentors 4 mid-level SREs, runs the on-call rotation redesign (moved from 1wk to follow-the-sun w/ Singapore team)

**Senior SRE / Infra Lead, Orbital Freight Systems** - Tokyo (some remote to Osaka office) | 2017-2021
- built first k8s platform for the company from literally nothing, prev was all EC2 + chef, painful
- Terraform adoption company wide, was resisted at first (people liked clicking console) but eventually became the standard
- go tooling for internal deploy CLI, still in use today apparently (heard from former coworker)
- handled 2am pages for a national logistics tracking outage during a peak shopping period, wrote the postmortem that changed how we did capacity forecasting afterward
- interviewed/hired 6 engineers for the platform team

**SRE, Nagai Cloud Partners** - Tokyo | 2014-2017
- early career, mostly ansible + puppet then transitioned to more cloud native stuff towards the end
- on-call, dashboarding (early grafana/graphite era), some python automation (before I mostly moved to go)
- helped with datacenter to AWS migration project, learned a ton about networking the hard way

### Education
- B.Eng, Information Engineering - Tokyo Institute of Technology (fictional dept name ok? just regular CS/infra coursework), 2010-2014
- CKA certified (2019, renewed 2022)
- various internal certs / vendor training, not gonna list all of them here
