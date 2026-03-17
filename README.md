# 🔐 GRC Portfolio — Tamia Williams

> Governance, Risk & Compliance | Cybersecurity & Information Assurance

[![Frameworks](https://img.shields.io/badge/NIST%20SP%20800--53-Rev.%205-1B3A5C?style=flat-square)](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
[![Frameworks](https://img.shields.io/badge/PCI%20DSS-v4.0-2C5F8A?style=flat-square)](https://www.pcisecuritystandards.org/)
[![Frameworks](https://img.shields.io/badge/FISMA-Compliant%20Controls-1E7B34?style=flat-square)](https://www.cisa.gov/federal-information-security-modernization-act)
[![Frameworks](https://img.shields.io/badge/CIS%20Controls-v8-D35400?style=flat-square)](https://www.cisecurity.org/controls)
[![Frameworks](https://img.shields.io/badge/NIST%20SP%20800--115-Pen%20Test-4A235A?style=flat-square)](https://csrc.nist.gov/publications/detail/sp/800-115/final)
[![Frameworks](https://img.shields.io/badge/HIPAA-Security%20Rule-C0392B?style=flat-square)](https://www.hhs.gov/hipaa)

---

## 👋 About This Portfolio

This repository showcases hands-on GRC work demonstrating my ability to assess, document, and remediate cybersecurity risks in alignment with federal and industry standards. Each artifact reflects real-world GRC deliverables — the kind produced by analysts, compliance specialists, and risk managers in enterprise environments.

I hold a background in **Cybersecurity and Information Assurance** and am actively pursuing roles in GRC, risk management, compliance, and security governance.

> *All scenarios in this portfolio are based on simulated organizations for portfolio demonstration purposes. No real organizational data is represented.*

📧 Connect with me on [LinkedIn](www.linkedin.com/in/tamia-williams-b92304232)

---

## 📁 Repository Structure

```
grc-portfolio/
│
├── GRC_Portfolio_Security_Evaluation_Report.docx       ← Assessment 01: Healthcare GRC
├── GRC_POA&M_Tracker.xlsx                              ← Assessment 01: POA&M workbook
├── GRC_Portfolio_Network_Merger_Security_Plan.docx     ← Assessment 02: Network security
├── GRC_Portfolio_PenTest_Engagement_Review.docx        ← Assessment 03: Pen test review
└── README.md
```

---

## 📋 Assessment 01 — Healthcare Security Evaluation & Remediation

### Overview
A comprehensive security evaluation for a simulated mid-size healthcare organization following a third-party Security Assessment Report (SAR). Covers the full GRC analyst workflow: ingesting external findings, rating risks, writing remediation recommendations, and producing compliance-ready documentation.

### Deliverables

| File | Description |
|------|-------------|
| `GRC_Portfolio_Security_Evaluation_Report.docx` | Full 5-section assessment report |
| `GRC_POA&M_Tracker.xlsx` | 4-tab POA&M workbook with dashboard, risk matrix, and control reference |

### What This Demonstrates

- Applied a 5×5 Likelihood × Impact risk scoring matrix to 7 identified findings
- Evaluated controls against NIST SP 800-53 Rev. 5 across six control families (AC, CA, IA, RA, SI)
- Used standard assessment language: *Other Than Satisfied / Satisfied / Not Applicable*
- Developed a structured POA&M with ownership, target dates, and resource requirements
- Authored a PCI DSS v4.0–aligned Point-of-Sale Security Policy (Requirements 1, 2, 5, 7, 8)
- Produced an executive summary written for non-technical leadership

### Frameworks Applied
`NIST SP 800-53 Rev. 5` `NIST SP 800-30` `NIST SP 800-137` `FISMA` `PCI DSS v4.0` `CIS Controls v8` `OMB Circular A-130`

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

## 📋 Assessment 02 — Network Merger & Secure Design Implementation Plan

### Overview
A network security evaluation and merger implementation plan for two simulated organizations undergoing consolidation — a financial services firm and a healthcare software vendor. Identifies nine vulnerabilities, proposes a unified secure network topology, and delivers a cost-justified implementation roadmap within a $50,000 budget constraint.

### Deliverables

| File | Description |
|------|-------------|
| `GRC_Portfolio_Network_Merger_Security_Plan.docx` | Full 7-section network security and merger plan |

### What This Demonstrates

- Identified and rated 9 vulnerabilities including Ghostcat (CVE-2020-1938), EOL systems, and open RDP/FTP ports
- Designed a defense-in-depth network topology with tiered firewall architecture (Fortinet NGF + Sophos XG)
- Mapped all components to OSI and TCP/IP layers
- Made hardware lifecycle decisions with cost justification; delivered under $50K budget with $9,573 reserve
- Planned Azure cloud migration to replace all EOL on-premise servers
- Addressed HIPAA and GDPR compliance requirements within the network design

### Frameworks Applied
`NIST SP 800-53` `HIPAA Security Rule` `GDPR` `CIS Controls v8` `Defense-in-Depth` `OSI Model`

### Vulnerability Summary

| ID | Org | Finding | Likelihood | Impact |
|----|-----|---------|-----------|--------|
| V-001 | Org A | Open Ports 21 (FTP) & 3389 (RDP) | Medium-High | HIGH |
| V-002 | Org A | Weak Password Policy | High | HIGH |
| V-003 | Org A | EOL Hardware & Mixed OS (Win 7/10/11) | Medium | HIGH |
| V-004 | Org A | Windows Server 2008 EOL | Medium | CRITICAL |
| V-005 | Org B | dRuby Remote Code Execution Risk | Medium | HIGH |
| V-006 | Org B | No MFA Enforcement | High | CRITICAL |
| V-007 | Org B | Ghostcat Exploit — Apache Tomcat | High | CRITICAL |
| V-008 | Org B | Windows XP + Legacy Protocols | High | CRITICAL |
| V-009 | Org B | Local Admin Privileges for All Users | High | HIGH |

---

## 📋 Assessment 03 — Penetration Test Engagement Plan Review

### Overview
An independent evaluation of a proposed penetration testing engagement plan for a simulated regional medical center. Identifies where the plan conflicts with operational goals and regulatory obligations, compares it against applicable frameworks, and delivers structured recommendations before testing begins.

### Deliverables

| File | Description |
|------|-------------|
| `GRC_Portfolio_PenTest_Engagement_Review.docx` | Full 6-section engagement review and advisory report |

### What This Demonstrates

- Critically evaluated a pen test plan against NIST SP 800-115, HIPAA, and PTES
- Identified 5 misalignment areas including 3 rated Critical or High severity
- Recognized missing Rules of Engagement, absent reporting phase, and uncontrolled ePHI exposure
- Delivered 2 formal recommendations with framework citations and remediation guidance
- Proposed controlled proof-of-concept testing and simulated credential capture solutions
- Applied CVSS scoring awareness and risk-based reporting methodology

### Frameworks Applied
`NIST SP 800-115` `HIPAA Security Rule` `PTES Technical Guidelines` `CVSS` `OWASP WSTG`

### Misalignment Summary

| Area | Issue | Severity |
|------|-------|---------|
| IT Functions | Full system takeover of endpoint security server — no safeguards | 🔴 Critical |
| Organizational Objectives | No reporting deliverables, severity ratings, or CVSS scoring | 🔴 High |
| Processes | Real credentials collected with no handling or invalidation procedures | 🔴 High |
| Client Goals | Directory traversal targeting patient data conflicts with protection goals | 🔴 High |
| Practices | Vishing lacks simulated capture, post-test notification, or awareness training | 🟠 Moderate |

---

## 🛠️ Skills Demonstrated

```
Risk Assessment & Rating    │ NIST RMF              │ Control Assessment      │ POA&M Development
Network Security Design     │ Vulnerability Analysis │ Pen Test Methodology    │ Executive Reporting
Security Policy Writing     │ PCI DSS                │ HIPAA Compliance        │ Findings Register
Defense-in-Depth            │ OSI / TCP-IP           │ Rules of Engagement     │ ePHI Data Handling
```

---

## 📌 More Coming Soon

| Planned Assessment | Frameworks | Status |
|-------------------|------------|--------|
| 04 — Incident Response Plan | NIST SP 800-61, SANS IR Framework | 📋 Planned |
| 05 — Vendor / Third-Party Risk Assessment | NIST SP 800-161, SOC 2 | 📋 Planned |
| 06 — Security Awareness Policy | NIST SP 800-50, CIS Control 14 | 📋 Planned |

---

*All scenarios in this portfolio are based on simulated organizations for portfolio demonstration purposes. No real organizational data is represented.*
