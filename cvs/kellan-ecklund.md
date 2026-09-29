# Kellan Ecklund
Site Reliability Engineer | Austin, TX (Remote) | kellan.ecklund@example.com | github.com/kecklund | +1 (512) 555-0148

## Summary
SRE w/ ~4 yrs exp keeping distributed systems up at 2am and everyone else asleep. Heavy k8s (self-managed + EKS/GKE), IaC via Terraform, tooling/automation in Go. Comfortable owning on-call, writing the postmortem, then fixing the root cause not just the symptom. Like reducing toil more than adding dashboards nobody reads.

## Skills
- **Orchestration:** Kubernetes (EKS, GKE, kubeadm bare-metal), Helm, Kustomize, ArgoCD
- **IaC/Automation:** Terraform (modules, workspaces, state mgmt @ scale), Ansible, Ansible-lite scripts, Ansible for config drift cleanup
- **Languages:** Go (primary - controllers, CLIs, operators), Python (glue scripts), Bash
- **Observability:** Prometheus, Grafana, Loki, PagerDuty, OpenTelemetry (partial rollout)
- **Cloud:** AWS (EC2/EKS/RDS/S3/IAM mostly), some GCP
- **Other:** Docker, Linux internals, networking (BGP basics, iptables/eBPF exposure), CI/CD - GitHub Actions, some Jenkins legacy pain

## Experience

### SRE II — Fenwick Data Systems (Austin, TX / Remote)
*Mar 2023 - Present*
- Own on-call rotation for 40+ microservices running on EKS, cut P1 incident MTTR from ~55min to ~19min by rewriting alert routing + runbooks
- Migrated legacy CloudFormation stacks (huge mess honestly) to Terraform modules - reusable across 6 teams now, saved probably 15hrs/wk of copy-paste infra work
- Wrote a Go-based k8s operator for automated cert rotation, was manual before (someone forgot once and took down checkout for 40 min - not naming names)
- built internal CLI (Go) that wraps kubectl+terraform+vault workflows, adopted by 3 other teams
- Reduced cluster costs ~28% via node autoscaler tuning + spot instance strategy for stateless workloads

### Site Reliability Engineer — Cordyline Cloud Co.
*Jul 2021 - Feb 2023*
Austin TX, hybrid then went remote in 2022
- First SRE hire, built on-call + monitoring from scratch (Prometheus/Grafana/Alertmanager)
- Terraform for all new infra - VPCs, EKS clusters, RDS, IAM roles/policies. ~120 modules by time I left
- wrote Go tooling to auto-remediate common pod crash loops (OOMKilled mostly), reduced pages by 30%+
- Participated in / led several incident postmortems, pushed blameless culture (mostly succeeded)
- Helped migrate monolith off EC2 onto k8s, painful multi-quarter project but got it done

### Systems Engineer (Jr) — Halden Ridge Networks, Austin TX
2020 - 2021
- Started here right out of school, mostly bare-metal Linux admin + some early k8s exposure (kubeadm clusters, learned the hard way)
- Wrote bash/python automation for server provisioning, ansible playbooks for config mgmt
- Shadowed SRE team, picked up terraform + went from there

## Education
**B.S. Computer Science** — University of Texas at Austin, 2020
- Relevant coursework: Distributed Systems, Operating Systems, Networking

## Certifications
- CKA (Certified Kubernetes Administrator) - 2022
- HashiCorp Terraform Associate - 2023
