# Buyer Pack – IA Compliance Core (ICC)

**Product:** IA Compliance Core (ICC)  
**Publisher:** (IO) Olsen Intelligence  
**Category:** Security & Compliance  
**Distribution:** Google Cloud Marketplace (Deployable App)

---

## 🎯 Purpose
This Buyer Pack provides enterprise buyers, auditors, and marketplace reviewers with a clear and verifiable view of ICC’s scope, deployment model, pricing, and operational posture.

IA Compliance Core (ICC) enables **AI compliance readiness and governance workflows** by generating **auditable evidence** and structured controls.

ICC does **not** issue certifications, provide legal advice, or replace regulators and auditors.

---

## 📖 Overview
IA Compliance Core (ICC) is an enterprise SaaS designed to operationalize **AI governance and compliance readiness** in cloud-native environments.

ICC provides structured workflows for:
- AI system inventory and traceability
- Risk classification and control mapping
- Incident management and corrective actions
- Reproducible, audit-ready compliance evidence

ICC integrates seamlessly with Kubernetes (GKE Autopilot, EKS, AKS) and includes auditor-ready documentation and bilingual operational runbooks.

---

## 🧩 Key Features
- AI system inventory and traceability  
- Risk classification and control mapping  
- Incident and corrective action workflows  
- Immutable audit evidence and exportable reports (PDF / XLS)  
- Enterprise-grade security (RBAC, 2FA, Secret Manager, NetworkPolicies)  
- Marketplace-ready deployment on GKE Autopilot  

---

## 🏢 Target Customers
- Financial services (Banking, FinTech, Insurance)  
- Healthcare and health-tech organizations  
- Telecommunications and large digital operators  
- Public sector agencies (B2G)  
- GRC integrators, auditors, and enterprise consultancies  

---

## 💼 Commercial Model
- **Starter:** $149 / month → Regulated SMEs  
- **Pro:** $499 / month → Mid-enterprise deployments  
- **Enterprise + White-Label:** $8,000–$9,000 / year  
  - Private offers  
  - Custom branding  
  - Partner enablement  

- **Optional Deployment Services:** $5,000–$15,000 (scope-dependent)

---

## ☁️ Deployment Path (Golden GMP)
- **Cluster:** Google Kubernetes Engine (GKE Autopilot)  
- **Database:** Cloud SQL with private IP  
- **Identity:** Workload Identity (no static service account keys)  
- **Secrets:** Secret Manager via CSI (no plaintext secrets)  
- **TLS:** Managed Certificates  
- **Network:** Kubernetes NetworkPolicies (default-deny)  
- **Operations:** One-command install and clean uninstall  

---

## 🔐 Security Posture
- Authentication: 2FA supported  
- Authorization: RBAC with least-privilege enforcement  
- Secrets: Secret Manager (rotation-ready)  
- Data protection: encryption in transit, private access  
- Logs: immutable audit evidence  
- Hardening: non-root containers, read-only root filesystem  
- Network segmentation via Kubernetes NetworkPolicies  

---

## 🧠 Optional Enterprise Extensions (Private Offers Only)
Optional enterprise extensions may be offered **exclusively via private offers** and are **not included** in the default Google Cloud Marketplace deployment.

These extensions:
- Are **advisory only**
- Require **explicit human approval**
- Do **not** enforce compliance or issue certifications
- Do **not** change ICC’s core compliance posture

---

## 📦 Repository Contents
- `README.md` → Product overview, scope, architecture, disclaimers  
- `SECURITY.md` → Security posture and vulnerability disclosure  
- `COMPLIANCE.md` → Evidence index and traceability map  
- `listing-summary.md` → Executive summary for marketplaces and auditors  
- `srm-incident.md` → Incident Response Runbook (EN / ES)  
- `ICC_Uninstallation_Runbook.md` → Clean uninstall procedure (EN / ES)  
- `buyer-pack.md` → This document  

---

## ⚖️ Disclaimer
ICC supports compliance readiness and evidence workflows.

It does **not** issue certifications, enforce compliance, or replace regulators and auditors.

All compliance decisions remain **customer-owned and human-approved**.

---

## 📬 Contact / Private Offers
**Publisher:** (IO) Olsen Intelligence  
**Email:** olsencastillo@io-io.net  
**Private Offers:** Enterprise onboarding and white-label partnerships

