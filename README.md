# 🔐 GRC Portfolio — Tamia Williams

> Governance, Risk & Compliance | Cybersecurity & Information Assurance

[![Frameworks](https://img.shields.io/badge/NIST%20SP%20800--53-Rev.%205-1B3A5C?style=flat-square)](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
[![Frameworks](https://img.shields.io/badge/PCI%20DSS-v4.0-2C5F8A?style=flat-square)](https://www.pcisecuritystandards.org/)
[![Frameworks](https://img.shields.io/badge/FISMA-Compliant%20Controls-1E7B34?style=flat-square)](https://www.cisa.gov/federal-information-security-modernization-act)
[![Frameworks](https://img.shields.io/badge/CIS%20Controls-v8-D35400?style=flat-square)](https://www.cisecurity.org/controls)

---

## 👋 About This Portfolio

This repository showcases hands-on GRC work demonstrating my ability to assess, document, and remediate cybersecurity risks in alignment with federal and industry standards. Each artifact reflects real-world GRC deliverables — the kind produced by analysts, compliance specialists, and risk managers in enterprise environments.

I hold a background in **Cybersecurity and Information Assurance** and am actively pursuing roles in GRC, risk management, compliance, and security governance.

📧 Connect with me on [LinkedIn](#) *(add your link)*

---

## 📁 Repository Structure

```
grc-portfolio/
│
├── 01_healthcare-security-assessment/
│   ├── GRC_Portfolio_Security_Evaluation_Report.docx   ← Full assessment report
│   ├── GRC_POA&M_Tracker.xlsx                          ← POA&M tracking workbook
│   └── README.md                                       ← This file
│
└── (more assessments coming)
```

---

## 📋 Assessment 01 — Healthcare Security Evaluation & Remediation

### Overview
A comprehensive security evaluation for a mid-size healthcare organization following a third-party Security Assessment Report (SAR). This project simulates the full GRC analyst workflow: ingesting external findings, rating risks, writing remediation recommendations, and producing compliance-ready documentation.

### Deliverables

| File | Description |
|------|-------------|
| `GRC_Portfolio_Security_Evaluation_Report.docx` | Full 5-section assessment report |
| `GRC_POA&M_Tracker.xlsx` | 4-tab POA&M workbook with dashboard, risk matrix, and control reference |

### What This Demonstrates

**Risk Assessment & Analysis**
- Applied a 5×5 Likelihood × Impact risk scoring matrix to 7 identified findings
- Assigned risk ratings (Critical / High / Moderate / Low) with documented justification
- Used NIST SP 800-30 methodology to structure the assessment approach

**Control Assessment**
- Evaluated controls against NIST SP 800-53 Rev. 5 across six control families: AC, CA, IA, RA, SI
- Used standard assessment language: *Other Than Satisfied / Satisfied / Not Applicable*
- Mapped findings to specific control identifiers (AC-6, CA-7, RA-3, IA-2, SI-3, CA-5, RA-7)

**Remediation Planning**
- Developed a structured POA&M with ownership, target dates, and resource requirements
- Prioritized remediation actions by risk score
- Recommended RBAC/IAM implementation, SIEM deployment, and MFA enforcement

**Policy Development**
- Authored a PCI DSS v4.0–aligned Point-of-Sale Security Policy
- Covered Requirements 1, 2, 5, 7, and 8 with action items and role assignments

**Documentation & Reporting**
- Produced an executive summary written for non-technical leadership (CISO/board level)
- Structured findings in a professional findings register with evidence citations
- Delivered a POA&M tracker with live Excel formulas, conditional formatting, and a dashboard

### Frameworks & Standards Applied

| Framework | Application |
|-----------|-------------|
| NIST SP 800-53 Rev. 5 | Control selection, assessment, and remediation |
| NIST SP 800-30 Rev. 1 | Risk assessment methodology |
| NIST SP 800-137 | Continuous monitoring strategy |
| NIST SP 800-63 | MFA and identity assurance recommendations |
| FISMA | Federal compliance context and reporting obligations |
| PCI DSS v4.0 | POS security policy requirements |
| CIS Controls v8 | Supplemental hardening guidance |
| OMB Circular A-130 | POA&M and documentation obligations |

### Findings Summary

| ID | Control | Finding | Risk Score | Priority |
|----|---------|---------|-----------|---------|
| F-001 | AC-6 | Least Privilege Not Enforced | 20 — Critical | 🔴 Immediate |
| F-002 | IA-2 | No MFA on Remote/Privileged Access | 20 — Critical | 🔴 Immediate |
| F-003 | RA-3 | Risk Assessment Outdated / Missing | 15 — High | 🔴 Immediate |
| F-004 | CA-7 | No Continuous Monitoring / SIEM | 16 — High | 🟠 Q4 2025 |
| F-005 | SI-3 | Inadequate Endpoint Protection | 12 — High | 🟠 Q3 2025 |
| F-006 | CA-5 | No Formal POA&M Process | 9 — Moderate | 🟡 Q3 2025 |
| F-007 | RA-7 | Inconsistent Risk Response Decisions | 9 — Moderate | 🟡 Q4 2025 |

---

## 🛠️ Skills Demonstrated

```
Risk Management          │ NIST RMF  │ Control Assessment  │ POA&M Development
Security Policy Writing  │ PCI DSS   │ Findings Register   │ Executive Reporting
Continuous Monitoring    │ FISMA     │ Endpoint Security   │ Identity & Access Mgmt
```

---

## 📌 More Coming Soon

| Planned Assessment | Frameworks | Status |
|-------------------|------------|--------|
| 02 — Business Continuity & Disaster Recovery Plan | NIST SP 800-34, ISO 22301 | 🔄 In Progress |
| 03 — Vendor Risk Assessment | NIST SP 800-161, SOC 2 | 📋 Planned |
| 04 — Security Awareness Policy | NIST SP 800-50, CIS Control 14 | 📋 Planned |

---

*All scenarios in this portfolio are based on simulated organizations for educational and portfolio purposes. No real organizational data is represented.*
