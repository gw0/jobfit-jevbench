# Helio Ribeiro
São Paulo, Brazil (Remote) | helio.ribeiro@example.com | +55 11 9XXXX-XXXX | github.com/helioribeiro

## Summary
SRE w/ ~4y exp keeping prod alive across k8s clusters, terraform-managed cloud infra (AWS/GCP mixed), and go tooling for internal automation. On-call rotations, incident response, postmortems, cap planning. Comfortable in chaos, prefer boring reliable systems tho. Some exposure to observability stacks (Prometheus/Grafana/Loki) and CI/CD pipelines (GitHub Actions, ArgoCD).

## Skills
- **Orchestration:** Kubernetes (EKS, GKE, self-managed), Helm, Kustomize, operators (basic controller-runtime usage)
- **IaC:** Terraform (modules, workspaces, state mgmt w/ remote backends), some Pulumi exposure
- **Languages:** Go (primary - CLIs, controllers, small services), Python (scripting), Bash
- **Cloud:** AWS (EC2, RDS, S3, IAM, VPC), GCP (GKE, Cloud SQL) - AWS heavier
- **Observability:** Prometheus, Grafana, Loki, basic OpenTelemetry
- **CI/CD:** GitHub Actions, ArgoCD, Jenkins (legacy stuff)
- **Other:** Linux internals, networking fundamentals (DNS/LB/iptables), incident mgmt (PagerDuty), postmortem writing

## Work Experience

### Site Reliability Engineer — Vixarion Sistemas
*Mar 2023 - Present*
- own terraform modules for multi-region k8s cluster provisioning, cut new-env spin up time from ~2 days to under 3hrs
- wrote go-based custom k8s admission webhook to enforce resource limits/requests org-wide, reduced noisy-neighbor incidents significantly
- on-call rotation lead, wrote/maintained runbooks, ran blameless postmortems after major incidents (2 sev1s in 2024)
- migrated legacy jenkins pipelines to argo cd + github actions, improved deploy freq from weekly to daily-ish
- capacity planning for black friday traffic spikes (2023, 2024) - no major outages either year, some close calls tho

### DevOps/SRE Hybrid — Nortelis Tecnologia
*Jul 2021 - Feb 2023*
- built terraform modules from scratch for AWS infra (previously all manual console clicking, painful)
- introduced prometheus+grafana monitoring where there was basically nothing before, set up alerting rules
- helped containerize monolith app into ~15 microservices deployed on eks
- wrote internal go cli tool for automating db backup/restore workflows, still in use afaik
- participated in on-call, not lead but handled several incidents solo

### Junior Systems Administrator — GrupoBaraúna Serviços de TI
*Jan 2021 - Jun 2021*
- managed on-prem linux servers (centos/ubuntu mix), patching, basic hardening
- assisted senior team w/ early k8s POC (minikube -> small on-prem cluster)
- scripted routine maintenance tasks in bash/python, reduced manual toil hours weekly

## Education
- **B.Sc. Computer Engineering** — Universidade Presbiteriana Mackenzie, São Paulo (2016-2020)
- Certified Kubernetes Administrator (CKA) - 2022
- HashiCorp Certified: Terraform Associate - 2023
