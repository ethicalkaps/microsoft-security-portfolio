# Microsoft Security Portfolio

Hands-on security configurations built in a Microsoft 365 E5 environment, demonstrating practical implementation of enterprise identity, endpoint, data protection, and incident response controls. Each project includes screenshots, compliance mappings to ISO 27001 and SOC 2, and implementation notes.

All configurations were performed in a personal M365 E5 trial environment for portfolio demonstration purposes. No production systems or employer data were used.

---

## Project 1 — Identity & Access Management Framework (Entra ID)

Complete IAM implementation from scratch — user provisioning, security groups, Conditional Access policies (MFA enforcement, legacy auth blocking, device compliance), automated quarterly access reviews, Privileged Identity Management, Named Locations, and Identity Protection monitoring.

**Compliance Mapping:** ISO 27001 A.9 (Access Control), SOC 2 CC6.1 (Logical Access), PCI DSS Req 7-8 (Access Control)

📄 [View Full Report](EntraID_IAM_Framework_Implementation_Report.pdf)

---

## Project 2 — Endpoint Compliance Program (Intune)
Complete endpoint compliance framework — tiered compliance policies (security baseline, firewall/AV enforcement, enhanced privileged device controls), security hardening configuration profiles, endpoint security management, and compliance monitoring. Demonstrates risk-based device management proportional to user privilege level.

**Compliance Mapping:** ISO 27001 A.8 (Asset Management), A.12 (Operations Security), SOC 2 CC6.1/CC6.6/CC6.8, PCI DSS Req 1, 3, 5, 6, 8

📄 [View Full Report](Intune_Endpoint_Compliance_Program_Report.pdf)

## Project 3 — Data Classification & DLP (Purview)
Complete data classification and DLP implementation — four-tier sensitivity label taxonomy (Public, Internal, Confidential, Highly Confidential), auto-labeling policies for credit card and PII detection, and DLP policies blocking unauthorized external sharing of classified content.

**Compliance Mapping:** ISO 27001 A.8.2/A.8.12 (Classification/DLP), SOC 2 Confidentiality, PCI DSS Req 3-4, HIPAA PHI Protection

📄 [View Full Report](Purview_Data_Classification_DLP_Report.pdf)

## Project 4 — Security Posture Assessment (Defender + Nessus)
*Coming soon*

## Project 5 — Incident Response Playbooks
*Coming soon*

---

**Built by** [Kapil Chaudhary](https://www.linkedin.com/in/kapil-chaudhary-cyber-security/) — GRC & Cybersecurity Professional | Ontario, Canada

**Companion project:** [NorthLink Cyber Risk Register](https://github.com/ethicalkaps/northlink-risk-register) — 20-risk assessment with Power BI dashboard and policy audit
