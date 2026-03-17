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

My name is **Tamia Williams**. I am a CySA+ certified cybersecurity professional with a Master of Science in Cybersecurity and Information Assurance, actively pursuing roles in GRC, risk management, compliance, and security governance.

This repository contains completed GRC case studies demonstrating my ability to assess security environments, identify control gaps, apply federal and industry frameworks, and produce professional remediation documentation — the kind of work GRC analysts deliver during audits, compliance reviews, and risk assessments.

**Certifications:** ISC² Certified in Cybersecurity (CC) | CompTIA CySA+ | CompTIA PenTest+

> *All scenarios are based on simulated organizations for portfolio demonstration purposes. No real organizational data is represented.*

📧 Connect with me on [LinkedIn](https://www.linkedin.com/in/tamia-williams-b92304232)

---

## 📁 Portfolio Contents

| # | Case Study | Frameworks | Preview |
|---|-----------|------------|---------|
| 01 | Healthcare Security Evaluation & Remediation | NIST SP 800-53, FISMA, PCI DSS | [📄 View PDF](GRC_Portfolio_Security_Evaluation_Report.pdf) |
| 02 | Network Merger & Secure Design Plan | NIST SP 800-53, HIPAA, GDPR | [📄 View PDF](GRC_Portfolio_Network_Merger_Security_Plan.pdf) |
| 03 | Penetration Test Engagement Plan Review | NIST SP 800-115, HIPAA, PTES | [📄 View PDF](GRC_Portfolio_PenTest_Engagement_Review.pdf) |

---

## 📋 Case Study 01 — Healthcare Security Evaluation & Remediation

### Scenario
A mid-size healthcare organization engaged an external security consulting firm for a Security Assessment Report (SAR). As the GRC analyst, I reviewed the SAR findings, evaluated the organization's control posture against NIST SP 800-53 Rev. 5, assigned risk ratings to each finding, developed a prioritized remediation plan, and produced a PCI DSS-aligned security policy for their point-of-sale environment.

### Deliverables
| File | |
|------|-|
| [GRC_Portfolio_Security_Evaluation_Report.pdf](GRC_Portfolio_Security_Evaluation_Report.pdf) | 📄 View in browser |
| [GRC_Portfolio_Security_Evaluation_Report.docx](GRC_Portfolio_Security_Evaluation_Report.docx) | ⬇️ Download Word version |
| [GRC_POA&M_Tracker.xlsx](GRC_POA%26M_Tracker.xlsx) | ⬇️ Download POA&M workbook |

### What This Demonstrates
- Applied a 5×5 Likelihood × Impact risk scoring matrix to 7 identified findings
- Evaluated controls against NIST SP 800-53 Rev. 5 across six control families (AC, CA, IA, RA, SI)
- Used standard assessment language: *Other Than Satisfied / Satisfied / Not Applicable*
- Developed a structured POA&M with ownership, target dates, and resource requirements
- Authored a PCI DSS v4.0–aligned Point-of-Sale Security Policy (Requirements 1, 2, 5, 7, 8)
- Produced an executive summary written for non-technical leadership (CISO/board level)

### Frameworks Applied
`NIST SP 800-53 Rev. 5` `NIST SP 800-30` `NIST SP 800-137` `FISMA` `PCI DSS v4.0` `CIS Controls v8` `OMB Circular A-130`

### Key Findings

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

## 📋 Case Study 02 — Network Merger & Secure Design Implementation Plan

### Scenario
Two organizations — a financial services firm and a healthcare software vendor — are undergoing a corporate merger. As the security analyst, I evaluated both environments for vulnerabilities, designed a unified secure network topology, made hardware lifecycle decisions with cost justification, and ensured the merged infrastructure met HIPAA and GDPR requirements — all within a $50,000 budget constraint.

### Deliverables
| File | |
|------|-|
| [GRC_Portfolio_Network_Merger_Security_Plan.pdf](GRC_Portfolio_Network_Merger_Security_Plan.pdf) | 📄 View in browser |
| [GRC_Portfolio_Network_Merger_Security_Plan.docx](GRC_Portfolio_Network_Merger_Security_Plan.docx) | ⬇️ Download Word version |

### What This Demonstrates
- Identified and rated 9 vulnerabilities including Ghostcat (CVE-2020-1938), EOL systems, and open RDP/FTP ports
- Designed a defense-in-depth network topology with tiered firewall architecture (Fortinet NGF + Sophos XG)
- Mapped all components to OSI and TCP/IP layers
- Made hardware lifecycle decisions with cost justification; delivered under $50K budget with $9,573 reserve
- Planned Azure cloud migration to replace all EOL on-premise servers
- Addressed HIPAA and GDPR compliance requirements within the network design

### Frameworks Applied
`NIST SP 800-53` `HIPAA Security Rule` `GDPR` `CIS Controls v8` `Defense-in-Depth` `OSI Model`

### Key Findings

| ID | Org | Finding | Likelihood | Impact |
|----|-----|---------|-----------|--------|
| V-004 | Org A | Windows Server 2008 EOL | Medium | CRITICAL |
| V-006 | Org B | No MFA Enforcement | High | CRITICAL |
| V-007 | Org B | Ghostcat Exploit — Apache Tomcat (CVE-2020-1938) | High | CRITICAL |
| V-008 | Org B | Windows XP + Legacy Protocols (rlogin, rsh) | High | CRITICAL |
| V-001 | Org A | Open Ports 21 (FTP) & 3389 (RDP) Exposed | Medium-High | HIGH |
| V-009 | Org B | Local Admin Privileges Granted to All Users | High | HIGH |

---

## 📋 Case Study 03 — Penetration Test Engagement Plan Review

### Scenario
A regional medical center preparing to deploy a new patient records system hired a penetration testing firm to validate their security controls before go-live. As the reviewing analyst, I evaluated the proposed engagement plan against NIST SP 800-115, the HIPAA Security Rule, and PTES best practices — identifying where the plan created operational and compliance risk for the client, and delivering formal recommendations before testing began.

### Deliverables
| File | |
|------|-|
| [GRC_Portfolio_PenTest_Engagement_Review.pdf](GRC_Portfolio_PenTest_Engagement_Review.pdf) | 📄 View in browser |
| [GRC_Portfolio_PenTest_Engagement_Review.docx](GRC_Portfolio_PenTest_Engagement_Review.docx) | ⬇️ Download Word version |

### What This Demonstrates
- Critically evaluated a pen test plan against NIST SP 800-115, HIPAA, and PTES
- Identified 5 misalignment areas including 3 rated Critical or High severity
- Recognized missing Rules of Engagement, absent reporting phase, and uncontrolled ePHI exposure
- Delivered 2 formal recommendations with framework citations and remediation guidance
- Proposed controlled proof-of-concept testing and simulated credential capture solutions
- Applied CVSS scoring awareness and risk-based reporting methodology

### Frameworks Applied
`NIST SP 800-115` `HIPAA Security Rule` `PTES Technical Guidelines` `CVSS` `OWASP WSTG`

### Key Findings

| Area | Issue | Severity |
|------|-------|---------|
| IT Functions | Full system takeover of endpoint security server — no operational safeguards | 🔴 Critical |
| Organizational Objectives | No reporting deliverables, severity ratings, or CVSS scoring defined | 🔴 High |
| Processes | Real domain credentials collected with no handling or invalidation procedures | 🔴 High |
| Client Goals | Directory traversal targeting patient data conflicts with data protection goals | 🔴 High |
| Practices | Vishing lacks simulated capture, post-test notification, or awareness training | 🟠 Moderate |

---

## 🛠️ Skills Demonstrated Across Portfolio

```
Risk Assessment & Rating    │ NIST RMF              │ Control Assessment      │ POA&M Development
Network Security Design     │ Vulnerability Analysis │ Pen Test Methodology    │ Executive Reporting
Security Policy Writing     │ PCI DSS                │ HIPAA Compliance        │ Findings Register
Defense-in-Depth            │ OSI / TCP-IP           │ Rules of Engagement     │ ePHI Data Handling
```

---

## 📌 More Coming Soon

| Planned Case Study | Frameworks | Status |
|-------------------|------------|--------|
| 04 — Incident Response Plan | NIST SP 800-61, SANS IR Framework | 📋 Planned |
| 05 — Vendor / Third-Party Risk Assessment | NIST SP 800-161, SOC 2 | 📋 Planned |
| 06 — Cloud Security Gap Analysis | NIST CSF, CSA CCM | 📋 Planned |

---

*All scenarios in this portfolio are based on simulated organizations for portfolio demonstration purposes. No real organizational data is represented.*
