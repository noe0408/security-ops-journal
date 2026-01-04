![logo](https://i.postimg.cc/5Nn01f7D/Journal.png)

<div align="center">

**Cloud Infrastructure Engineering • Defensive Security • Homelab Operations**

[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge&logo=activitypub)](./)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/alex-avina/)

<br />

> Portfolio-style documentation of secure infrastructure builds, hardening work, and detection/response engineering.

</div>

---

## Start Here
If you only have a few minutes:
1. **Capstone:** [CAPSTONE.md](./CAPSTONE.md) — design → deploy → monitor → respond  
2. **Featured Projects:** [01_projects](./01_projects) — production-style builds + docs  
3. **Detections & Runbooks:** [03_detection](./03_detection) + [04_runbooks](./04_runbooks) — operational security maturity  

---

## What I Build (Capabilities)
- Secure cloud infrastructure using **IaC** (Terraform modules, environment layouts, secure defaults)
- Identity-first security: **least privilege IAM**, federation patterns, access reviews, break-glass workflows
- Cloud telemetry and defense: **logging**, detection logic, tuning notes, and **incident response runbooks**
- Hardening and operations: Linux baselines, service segmentation, backups/DR procedures, postmortems

---

## Capstone (End-to-End Cloud Security Build)
A complete build with reproducible artifacts.

- **Overview:** [CAPSTONE.md](./CAPSTONE.md)
- **Architecture:** [Diagrams](./07_diagrams/capstone)
- **Threat Model:** [DFDs + risks](./07_diagrams/dfd) *(or link to your threat-model doc if you have one)*
- **Infrastructure-as-Code:** [Terraform](./01_projects/capstone/iac)
- **CI Security Gates:** [Pipelines](./01_projects/capstone/pipelines) *(SAST, dependency, IaC, container scan)*
- **Detections:** [Rules + test events](./01_projects/capstone/detections)
- **IR Runbooks:** [Playbooks + tabletop](./01_projects/capstone/runbooks)
- **Evidence:** [Sanitized validation](./01_projects/capstone/evidence)

<br>
<div align="center">
  <a href="./ROADMAP.md">
    <img src="https://img.shields.io/badge/VIEW_FULL_ROADMAP-000000?style=for-the-badge&logo=readthedocs&logoColor=white" alt="View Roadmap">
  </a>
  <br>
  <sub><i>Weekly learning plan, milestones, and upcoming work.</i></sub>
</div>

---

## Featured Engineering Projects
*Outcome-driven builds with architecture + validation.*

| Project | Stack | Security / Engineering Focus | Proof | Link |
| :--- | :--- | :--- | :--- | :--- |
| **Homelab Infrastructure** | `Coolify` `Docker` `Cloudflare` | Segmentation, secure access patterns, ops runbooks | diagrams • hardening notes • evidence | **[View](./01_projects/homelab)** |
| **Honeypot Network** | `T-Pot` `Elastic Stack` | Telemetry pipeline, attacker behavior analysis, dashboards | detections • dashboards • writeups | **[View](./01_projects/honeypot)** |
| **Custom Compiler** | `Python` `C` | Systems fundamentals, parsing discipline, safe coding patterns | tests • design notes | **[View](./01_projects/compiler)** |

> Each project folder includes: architecture, security notes, validation steps, and sanitized evidence where applicable.

---

## Repository Map
- **[01_projects](./01_projects)** — production-style builds (IaC, deployments, architecture, ops)
- **[02_labs](./02_labs)** — focused experiments (AWS, Linux, networking, AppSec, Kubernetes)
- **[03_detection](./03_detection)** — detections-as-code, test events, tuning notes
- **[04_runbooks](./04_runbooks)** — incident response + operational procedures
- **[05_study](./05_study)** — certification-aligned notes + concept deep dives
- **[06_writeups](./06_writeups)** — CTF/wargame writeups with defensive takeaways
- **[07_diagrams](./07_diagrams)** — architecture diagrams, DFDs, threat models
- **[08_scripts](./08_scripts)** — automation utilities (audits, log parsing, helpers)
- **[09_evidence](./09_evidence)** — validation artifacts (sanitized)

---

## Detection Engineering & Incident Response
- **Detections:** [03_detection](./03_detection) — rules, rationale, tuning, mappings
- **IR Runbooks:** [04_runbooks/incident-response](./04_runbooks/incident-response) — triage → containment → recovery
- **Ops Runbooks:** [04_runbooks/operations](./04_runbooks/operations) — backups/DR, access reviews, change control

---

## Knowledge Base
- **[CompTIA Security+ (SY0-701)](./05_study/security-plus)** — objective-mapped notes + mini-quizzes
- **[Cloud Security Concepts](./05_study/cloud-concepts)** — IAM, VPC patterns, KMS, governance
- **[Networking Internals](./05_study/networking)** — DNS, TCP/IP, subnetting, packet analysis

---

## Labs (Skill Proof)
- **[AWS](./02_labs/aws)** — IAM experiments, logging, secure S3/KMS patterns
- **[Linux Hardening](./02_labs/linux)** — baselines, audits, system logging
- **[AppSec](./02_labs/appsec)** — auth patterns, input validation, regression tests
- **[Containers & K8s](./02_labs/k8s)** — RBAC, network policies, admission controls
- **[Networking](./02_labs/networking)** — captures, troubleshooting, protocol behavior

---

## Current Focus
- [ ] Expand AWS detection pack (identity + persistence signals)
- [ ] Terraform module hardening + reusable secure defaults
- [ ] IR tabletop exercises and runbook iteration

---

## Documentation Standards
Every project/lab aims to include:
- Architecture diagram (where relevant)
- Threat model (DFD + top risks)
- Secure-by-default configuration (IaC or hardening steps)
- Validation evidence (tests, screenshots, commands, outputs)
- Lessons learned / postmortem notes

---

## Folder Structure

```text
.
├── 01_projects/        # Production-style builds (IaC, architecture, ops)
├── 02_labs/            # Focused experiments with validation steps
├── 03_detection/       # Detections-as-code + testing + tuning
├── 04_runbooks/        # IR + operational playbooks
├── 05_study/           # Certification and concept notes
├── 06_writeups/        # CTF/wargame writeups (defensive takeaways)
├── 07_diagrams/        # Diagrams (architecture, DFDs)
├── 08_scripts/         # Automation utilities
├── 09_evidence/        # Sanitized proof artifacts
├── CAPSTONE.md
├── ROADMAP.md
├── LICENSE
└── README.md
```
<br>

<div align="center">
  <a href="./FOLDER_STRUCTURE.md">
    <img src="https://img.shields.io/badge/VIEW_FULL_FOLDER_STRUCTURE-000000?style=for-the-badge&logo=files&logoColor=white" alt="View Full Folder Structure">
  </a>
  <br>
  <sub><i>Click to view the complete repository folder structure (expanded).</i></sub>
</div>

<br>
