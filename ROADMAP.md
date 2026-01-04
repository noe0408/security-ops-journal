![logo](https://i.postimg.cc/jjbt75jH/roadmap.png)


Weeks 1–3 — Setup, baseline labs, DoD
- W1: Repo scaffold + CI skeleton; create DoD templates files. Start Linux VM + Docker.
- W2: AWS lab account prep (org, budget alerts, MFA); enable CloudTrail (trail to S3).
- W3: Local k8s + Windows VM; finalize Definition of Done and evidence folder naming.

Weeks 4–6 — Networking Foundations (Project: DNS + packet captures)
- W4: Study TCP/IP/DNS; create lab plan and DFD for DNS lab.
- W5: Implement lab: simulated DNS misconfig; capture pcap samples.
- W6: Validate: Wireshark exports sanitized; README + evidence; write 1 detection for suspicious DNS exfil pattern.

Weeks 7–9 — Linux Systems Engineering (Project: hardened host)
- W7: Baseline hardening playbook; build audit.sh.
- W8: Harden Linux VM; run audit; collect evidence.
- W9: Validate: produce hardening evidence, one IR runbook for host compromise.

Weeks 10–12 — Programming for Security Automation
- W10: Choose Python; build CLI skeleton + logging pattern.
- W11: Implement log_summarizer (CloudTrail-like).
- W12: Unit tests; integrate script into CI as check; README + evidence.

Weeks 13–15 — Security Fundamentals & Threat Modeling
- W13: Create DFD + STRIDE for an app (choose Capstone app).
- W14: Produce threat model writeup; map controls.
- W15: Review & add crypto/KMS notes; evidence files.

Weeks 16–18 — Web & API Security (Project: secure demo API)
- W16: Build minimal API with secure patterns.
- W17: Add SAST checks; write vuln-and-fix doc.
- W18: Validate: automated tests, CI gate passing, evidence.

Weeks 19–21 — Cloud Fundamentals + AWS Core (Identity + Networking)
- W19: IAM role library; implement at least 3 least-privilege roles.
- W20: VPC design + deploy secure S3 with KMS.
- W21: Validate logging (CloudTrail + VPC Flow); write detections for IAM changes.

Weeks 22–24 — DevSecOps & IaC security
- W22: CI pipelines: OIDC to AWS, secrets handling.
- W23: Integrate IaC scanning (Checkov/tfsec), SAST, dependency scanning.
- W24: Remote state + module design for Capstone; validate pipeline gates.

Weeks 25–27 — Containers & Kubernetes Security
- W25: Docker hardening + image scanning.
- W26: K8s RBAC + network policies; deploy sample app.
- W27: Admission control policies (OPA/Gatekeeper optional); evidence + detections.

Weeks 28–30 — Detection Engineering & IR
- W28: Build detection pack (IAM+assumeRole+key creation).
- W29: Test events generation; tune rules; produce tuning notes.
- W30: IR runbooks: credential compromise, public S3; tabletop exercise writeup.

Weeks 31–33 — GRC, CVE management, optional specializations
- W31: Map controls to NIST/CIS; build audit evidence checklist.
- W32: Add CVE tracking notes + vuln lifecycle process.
- W33: Pick 1–2 specializations and add one lab each.

Weeks 34–36 — Capstone (Design → Build → Prove → Publish)
- W34: Finalize architecture, DFD, threat model, IaC modules.
- W35: Deploy Capstone, enable logging, CI gates, detections.
- W36: Produce evidence pack, run tabletop, finalize CAPSTONE.md and portfolio checklist.
