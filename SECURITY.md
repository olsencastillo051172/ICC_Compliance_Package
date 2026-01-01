# Security Policy

This policy is part of the **ICC_Compliance_Package** and is intended for auditors, marketplace reviewers, and enterprise buyers.  
It is not applicable to private implementation repositories or customer-specific deployments.

This document defines the security posture and vulnerability disclosure process for **IA Compliance Core (ICC)**, covering only marketplace-facing assets and documentation published as part of this package.

---

## Reporting a Vulnerability

If you discover a security vulnerability in **IA Compliance Core (ICC)**, we request responsible disclosure.

- **Do not** open a public GitHub issue.
- Contact the security team directly at: **olsencastillo@io-io.net**
- Provide a clear description of the issue, steps to reproduce, and any relevant logs or artifacts.
- We encourage **encrypted communication (PGP/GPG)** for sensitive reports. Public keys are available upon request.

Reports are acknowledged within **72 hours**.  
Once triage is complete, **we commit to providing a remediation timeline**.

---

## Scope

This security policy applies **only** to artifacts published in the **ICC_Compliance_Package**, including:

- Public documentation
- Marketplace-facing descriptions
- Declared security posture, controls, and operational runbooks

This policy does **not** cover:

- Customer-specific deployments
- Customer-managed cloud infrastructure
- Private implementation repositories
- Operational environments under customer control

Customer-specific deployments are governed by **contractual SLAs** and **separate internal security policies**.

**Third-party dependencies** are managed under their respective **upstream security policies**.

---

## Supported Versions

Only the **latest published release** of ICC is supported for security disclosures.

- **Current supported version:** v1.0.0

Security patches are released on a **monthly cadence**, or sooner if required.  
**Critical CVEs are addressed within 14 days of disclosure.**

Security advisories are published in **release notes** and communicated to **marketplace customers** where applicable.

Older versions may not receive security updates.

---

## Disclosure Process

We follow responsible disclosure practices:

1. Acknowledgment within **72 hours**
2. Initial impact assessment and triage
3. Remediation planning with communicated timeline
4. Mitigation and verification
5. Documentation updates where applicable
6. Coordination with reporters to ensure **responsible public disclosure after remediation**

ICC does not offer bug bounties at this time.

---

## Safe Harbor

Security research conducted in good faith will not result in legal action, provided that the researcher:

- Does not access, modify, or exfiltrate customer data
- Does not disrupt service availability
- Respects system boundaries and applicable laws
- Reports findings responsibly and privately

Researchers acting in good faith are **encouraged to share findings that improve ICC’s security posture**, provided they respect customer data boundaries and service availability.
