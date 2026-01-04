![logo](https://i.postimg.cc/QCPTq5B2/Folder-Structure.png)

> This document captures the repository layout and where key artifacts live.

```text
.
├── 01_projects/
│   ├── homelab/
│   │   ├── README.md
│   │   ├── architecture/
│   │   │   ├── diagram.png
│   │   │   └── decisions.md
│   │   ├── iac/
│   │   │   ├── terraform/
│   │   │   └── scripts/
│   │   ├── ops/
│   │   │   ├── backups.md
│   │   │   ├── patching.md
│   │   │   └── monitoring.md
│   │   ├── security/
│   │   │   ├── threat-model.md
│   │   │   ├── hardening.md
│   │   │   └── controls.md
│   │   └── evidence/
│   │       ├── screenshots/
│   │       └── validation.md
│   │
│   ├── honeypot/
│   │   ├── README.md
│   │   ├── architecture/
│   │   │   ├── diagram.png
│   │   │   └── decisions.md
│   │   ├── deployment/
│   │   ├── detections/
│   │   ├── analysis/
│   │   └── evidence/
│   │
│   ├── compiler/
│   │   ├── README.md
│   │   ├── design/
│   │   ├── src/
│   │   ├── tests/
│   │   └── evidence/
│   │
│   └── capstone/
│       ├── README.md
│       ├── architecture/
│       │   ├── diagram.png
│       │   ├── decisions.md
│       │   └── data-flow.png
│       ├── security/
│       │   ├── threat-model.md
│       │   ├── control-mapping.md
│       │   └── risk-register.md
│       ├── iac/
│       │   ├── modules/
│       │   └── environments/
│       ├── pipelines/
│       │   ├── github-actions/
│       │   └── docs/
│       ├── detections/
│       │   ├── rules/
│       │   ├── test-events/
│       │   └── tuning-notes/
│       ├── runbooks/
│       │   ├── incident-response/
│       │   └── operations/
│       └── evidence/
│           ├── screenshots/
│           └── validation.md
│
├── 02_labs/
│   ├── README.md
│   ├── aws/
│   │   ├── README.md
│   │   ├── iam/
│   │   ├── logging/
│   │   └── s3-kms/
│   ├── linux/
│   │   ├── README.md
│   │   ├── hardening/
│   │   └── auditing/
│   ├── networking/
│   │   ├── README.md
│   │   ├── wireshark/
│   │   └── subnetting/
│   ├── appsec/
│   │   ├── README.md
│   │   ├── auth/
│   │   └── input-validation/
│   └── k8s/
│       ├── README.md
│       ├── rbac/
│       ├── network-policies/
│       └── admission-controls/
│
├── 03_detection/
│   ├── README.md
│   ├── aws/
│   ├── sigma/
│   ├── splunk/
│   ├── elk/
│   ├── test-events/
│   └── tuning-notes/
│
├── 04_runbooks/
│   ├── incident-response/
│   ├── operations/
│   ├── access-reviews/
│   └── backups-dr/
│
├── 05_study/
│   ├── security-plus/
│   ├── cloud-concepts/
│   ├── networking/
│   └── glossary.md
│
├── 06_writeups/
│   ├── bandit/
│   └── hackthebox/
│
├── 07_diagrams/
│   ├── dfd/
│   ├── aws/
│   ├── network/
│   └── capstone/
│
├── 08_scripts/
│   ├── aws/
│   ├── linux/
│   └── parsing/
│
├── 09_evidence/
│   ├── screenshots/
│   ├── exports/
│   └── validation/
│
├── CAPSTONE.md
├── ROADMAP.md
├── LICENSE
└── README.md
