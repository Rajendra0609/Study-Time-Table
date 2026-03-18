
# AWS DevOps Engineer (3+ YoE) — 16‑Week Job Switch Tracker

**Owner:** DAGGUBATI Sri Rajendra‑Prasad
**Target Roles:** Linux + DevOps + AWS / Cloud DevOps / SRE (3–5 YoE)  
**Start:** 20 March 2026  
**Tracker File:** `DevOps_AWS_3YoE_Tracker_v7.xlsx`

---

## 👀 Overview
This repo contains a structured, **hands‑on 16‑week roadmap** to move into a strong AWS DevOps/SRE role. It doubles as a daily study journal, skills matrix, project portfolio planner, interview Q bank, applications tracker, and salary/negotiation playbook — all in a single Excel workbook.

**Principles**
- 60% Hands‑on • 30% Theory • 10% Interview prep  
- Build → Break → Fix → Document → Push to GitHub (evidence or it didn’t happen)  
- Automate everything (IaC, pipelines, scanning, cost checks, runbooks)

---

## 📦 What’s inside the Excel (sheets)
- **3YoE Profile** — your strengths, gaps, priorities, timeline.
- **Dashboard** — live progress and key milestones.
- **Roadmap** — week‑by‑week topics, labs, interview focus & resources.
- **Daily Timetable** — AM/PM plan + weekly assignment grid.
- **Study Tracker** — log hours, status, % complete, evidence links.
- **Skills Checklist** — target levels, current level, proof.
- **Projects** — 10 real‑world portfolio builds with deliverables.
- **Interview Prep** — senior‑level Q bank + STAR prompts.
- **Applications** — job pipeline, follow‑ups, target companies.
- **Salary Guide** — market ranges & negotiation playbook.
- **Certifications Tracker** — SAA → CKA → DOP path.

> Download the latest workbook (**v7**) and open in Excel/LibreOffice.  
> **File:** `DevOps_AWS_3YoE_Tracker_v7.xlsx`  

---

## 🆕 What’s new in **v7** (compared to v6)
**Roadmap additions (placed where they fit naturally):**
- **W2:** *Automation Add‑on — Ansible + AWS Systems Manager (SSM)*
- **W6:** *K8s Storage Add‑on — EFS CSI (RWX patterns, perf vs EBS)*
- **W7:** *Immutable Infra — Packer Golden AMIs (CI bake → Terraform)*
- **W8:** *Advanced VPC — VPC Endpoints, NACL vs SG, IPv6 (with ALB)*
- **W10:** *Containers on AWS — ECS/Fargate + CodeDeploy blue/green*
- **W10:** *Serverless Orchestration — EventBridge + Step Functions*
- **W11:** *Observability — Loki + Promtail (log‑based alerts, correlation)*
- **W12:** *Secrets Platform — Vault on K8s (dynamic DB creds, Agent/CSI)*
- **W12:** *K8s Backup/Restore — Velero (namespace + PV restore)*
- **W12:** *Supply‑chain Security — SBOM (Syft), cosign signing, SLSA*
- **W14:** *Org‑wide Access — IAM Identity Center (SSO)*
- **W15:** *DR Practice — AWS Backup plans + PITR restore runbook*

**Study Tracker:** dated rows added for all the above labs so daily logging stays in sync with the calendar.  
**Skills Checklist:** new skills appended (Ansible, Packer, SSM, ECS/Fargate, EventBridge/SFN, Vault, Velero, Loki/Promtail, EFS CSI, VPC Endpoints/NACL/IPv6, SSO, AWS Backup, Supply‑chain).  
**Projects:** added *#9 Golden Image Factory* and *#10 ECS Fargate Blue/Green*.  
**Cleanup:** fixed the duplicate AI‑tool ID (`46126`) issue.

---

## 🚀 Quick start (how to use this tracker)
1) **Clone or download** this repo and open `DevOps_AWS_3YoE_Tracker_v7.xlsx`.
2) Go to **Study Tracker** and log time **every evening** (Actual Hrs, Status, %). Paste **GitHub links** as evidence.
3) Follow the **Roadmap** week by week. Each entry has: *Core Topics → Hands‑on Deliverables → Interview Focus → Resources*.
4) Build the **Projects** exactly as described (readme + diagrams). These are what land interviews.
5) Update **Skills Checklist** weekly (Current Level, % Done, Notes/Evidence).
6) On weekends: complete one **project sprint**, practice 15–20 **interview Qs**, and send 5–10 **applications**.

**Daily cadence** (from the Dashboard):
- **Morning (60–90m)** — theory/docs for one topic.  
- **Evening (90–120m)** — hands‑on lab + push to GitHub.  
- **Night (30m)** — notes + interview Q drill + update % complete.

---

## 🧪 Portfolio projects (10)
1. **Automated Infra Provisioner** — Terraform modules + remote state + Atlantis (VPC/EC2/RDS/ALB/ASG).  
2. **Full CI/CD Platform with GitOps** — GHA (OIDC) → SonarQube → Docker/ECR → ArgoCD + Rollouts canary.  
3. **Production EKS Platform** — IRSA, CA/Karpenter concept, LB Controller, ExternalDNS, Prom+Grafana, Falco, SLOs.  
4. **Event‑Driven Microservices on AWS** — API GW → Lambda → SQS → DynamoDB (+ X‑Ray & CloudWatch).  
5. **Security Hardening Baseline** — GuardDuty, Security Hub, WAF, KMS, Falco, SAST, IAM Access Analyzer.  
6. **Multi‑Account AWS Landing Zone** — Orgs, SCPs, Config rules, budgets, central logging.  
7. **Observability Stack from Scratch** — Prometheus, Grafana, Loki, Tempo, SLO alerts, runbooks.  
8. **Platform Engineering IDP (Backstage)** — catalog, scaffolder templates, TechDocs, RBAC.  
9. **Golden Image Factory (Packer + Ansible + Terraform)** — CI bake → AMI → ASG; faster/consistent rollouts.  
10. **ECS Fargate Blue/Green Deployments** — CodeDeploy canary + auto‑rollback; dashboards + runbook.

> Tip: Treat each project like a mini‑product — include a diagram, assumptions, trade‑offs, and benchmarks in its README.

---

## 🔐 Security & supply‑chain guardrails
- **Secrets:** Prefer OIDC to AWS (no long‑lived keys). Use **External Secrets** or **Vault** for apps, never plaintext.  
- **Images & IaC:** Scan Docker + Terraform on every PR. Generate **SBOM** and **cosign** sign images; verify in CI before deploy.  
- **K8s:** Enforce PSS, RBAC least‑privilege, NetworkPolicy default‑deny, admission policies (OPA/Gatekeeper).  
- **DR:** Use **Velero** for cluster backup/restore and **AWS Backup** for EBS/RDS/EFS; document RPO/RTO.

---

## 🛠 Customising the plan
- **Starting later than 20 Mar 2026?** Shift the dates in *Study Tracker* (the weekly theme still holds).  
- **Company‑specific focus:** Duplicate the *Roadmap* sheet and tweak the weeks to mirror the JD keywords.  
- **Evidence‑first:** Don’t mark any skill as *Advanced* without a public repo link or runbook.

---

## 📝 Versioning
- **v6 → v7:** Adds Ansible/SSM, ECS/Fargate, SSO, EFS CSI, EventBridge/SFN, Vault, Velero, Loki/Promtail, AWS Backup, and full supply‑chain steps. Also adds dated Study Tracker rows and two new projects.  
- Next: v7.1 could add a *changelog* sheet, resource links per new Roadmap item, and filter views for quick filtering.

---

## 🙌 Credits & license
Personal study and job‑switch accelerator by **renexter**. Use freely; attribution appreciated. No warranty — validate all cloud costs and security settings before deploying to production.

