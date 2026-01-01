# Uninstallation Runbook
## IA Compliance Core (ICC)

**Product:** IA Compliance Core (ICC)  
**Publisher:** (IO) Olsen Intelligence  
**Scope:** Clean uninstall procedure for enterprise and marketplace deployments  
**Version:** v1.0.0  

---

## 1. Purpose
This runbook describes the **safe and complete uninstallation** of IA Compliance Core (ICC) from a Kubernetes environment.

It is intended for:
- Enterprise operators  
- Auditors and compliance reviewers  
- Google Cloud Marketplace validation  

The objective is to ensure **no residual resources, secrets, identities, or data artifacts remain** after removal.

---

## 2. Scope & Assumptions
This procedure applies to:
- Google Kubernetes Engine (GKE Autopilot)  
- Kubernetes-based deployments (EKS / AKS)  
- Helm and Terraform-managed installations  

Customer-specific extensions, integrations, or private modules must be removed separately according to contractual agreements.

---

## 3. Pre-Uninstall Checklist
Before initiating uninstall:
- Export all required audit evidence and reports  
- Confirm no active compliance workflows or incidents  
- Notify internal stakeholders and operators  
- Verify operator permissions and access rights  

---

## 4. Application Removal

### 4.1 Helm Uninstall
Remove the ICC application from the cluster:

```bash
helm uninstall icc-core --namespace icc
 
