# Buyer Pack – IA Compliance Core (ICC)

**Product:** IA Compliance Core (ICC)  
**Publisher:** (IO) Olsen Intelligence  
**Category:** Security & Compliance  
**Distribution:** Google Cloud Marketplace (Deployable App)

---

## 🎯 Purpose
This Buyer Pack provides prospective customers and auditors with a clear view of ICC’s value, deployment path, pricing, and support.  
ICC enables **compliance readiness and governance workflows** by generating auditable evidence.  
It does **not** issue certifications or legal opinions.

---

## 📖 Overview
IA Compliance Core (ICC) is an enterprise SaaS designed to operationalize **AI governance and compliance readiness** in cloud‑native environments.  
ICC provides structured workflows, risk classification, incident management, and reproducible audit evidence.  
It integrates seamlessly with Kubernetes (GKE Autopilot, EKS, AKS) and includes auditor‑ready documentation and runbooks.

---

## 🧩 Key Features
- AI system inventory and traceability  
- Risk classification and control mapping  
- Incident and corrective action workflows  
- Immutable audit evidence and exportable reports (PDF/XLS)  
- Enterprise‑grade security (RBAC, 2FA, Secret Manager, NetworkPolicies)  
- Marketplace‑ready deployment on GKE Autopilot  

---

## 🏢 Target Customers
- Financial services (Banking, FinTech, Insurance)  
- Healthcare and health‑tech companies  
- Telecommunications and large digital operators  
- Public sector agencies (B2G)  
- GRC integrators, auditors, and enterprise consultancies  

---

## 💼 Commercial Model
- **Starter:** $149 / month → SMEs in regulated sectors  
- **Pro:** $499 / month → mid‑enterprise deployments  
- **Enterprise + White‑Label:** $8,000–$9,000 / year → private offers, branding, partner enablement  
- **Optional Deployment Services:** $5,000–$15,000 depending on scope  

---

## ☁️ Deployment Path (Golden GMP)
- **Cluster:** GKE Autopilot (default)  
- **Database:** Cloud SQL with private IP  
- **Identity:** Workload Identity (no static service keys)  
- **Secrets:** Secret Manager via CSI (no plaintext secrets)  
- **TLS:** Managed Certificates  
- **Network:** NetworkPolicies (default deny)  
- **Scripts:** One‑command install (`deploy.sh`) and uninstall (`ICC_Uninstallation_Runbook.md`)  

---

## 🔐 Security Posture
- Authentication: 2FA supported  
- Authorization: RBAC, least privilege  
- Secrets: Secret Manager (rotation‑ready)  
- Data protection: encryption in transit, private access  
- Logs: immutable audit evidence  
- Hardening: non‑root containers, read‑only root filesystem  
- Network segmentation via Kubernetes NetworkPolicies  

---

## 📦 Repository Contents
- `README.md` → product overview, architecture, disclaimers  
- `SECURITY.md` → security policy and disclosure  
- `COMPLIANCE.md` → evidence index and traceability  
- `listing-summary.md` → executive summary for marketplaces and auditors  
- `srm-incident.md` → Incident Response Runbook (EN/ES)  
- `ICC_Uninstallation_Runbook.md` → uninstall procedure (EN/ES)  
- `buyer-pack.md` → this document  

---

## ⚖️ Disclaimer
ICC supports compliance readiness and evidence workflows.  
It does **not** issue certifications, enforce compliance, or replace regulators and auditors.  
All compliance decisions remain **customer‑owned and human‑approved**.
