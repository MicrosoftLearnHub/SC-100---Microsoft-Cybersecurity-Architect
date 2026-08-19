# Microsoft Certified: Cybersecurity Architect Expert (SC-100)

[![Microsoft Certification](https://img.shields.io/badge/Microsoft%20Certified-Cybersecurity%20Architect%20Expert-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Exam Code](https://img.shields.io/badge/Exam%20Code-SC-100-brightgreen?style=for-the-badge&logo=github)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Passing Score](https://img.shields.io/badge/Passing%20Score-700%2F1000-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Practice Materials](https://img.shields.io/badge/Practice%20Materials-SC-100-orange?style=for-the-badge)](https://www.certsclub.com/microsoft/)

---

## 📖 Table of Contents
1. [Exam Overview](#-exam-overview)
2. [How to Prepare](#-how-to-prepare)
3. [Exam Blueprint & Skills Measured](#-exam-blueprint--skills-measured)
4. [Practice & Preparation Materials](#-practice--preparation-materials)
5. [10 Realistic Demo Practice Questions & Answers](#-10-realistic-demo-practice-questions--answers)
6. [Community Discussion & Study Group](#-community-discussion--study-group)
7. [Detailed Topic Documentation Index](#-detailed-topic-documentation-index)
8. [Official Microsoft Learning Resources](#-official-microsoft-learning-resources)

---

## 🎯 Exam Overview

Exam SC-100 validates expert-level skills in designing a holistic cybersecurity strategy and architecture across identity, governance, infrastructure, security operations, applications, and data based on Zero Trust principles.

### Quick Facts
| Attribute | Specification |
| :--- | :--- |
| **Exam Code** | **SC-100** |
| **Certification Name** | **Microsoft Certified: Cybersecurity Architect Expert (SC-100)** |
| **Passing Score** | 700 / 1000 (Scaled Score) |
| **Official Portal** | [Microsoft Learn Credentials](https://learn.microsoft.com/en-us/credentials/certifications/) |

---

## 🚀 How to Prepare

- 🔗 **Review the Exam SC-100 page for exam registration and other details:**  
  Visit the [Official Microsoft Exam Registration Page](https://learn.microsoft.com/en-us/credentials/certifications/) to review scheduling options via Pearson VUE.
  
- 📚 **Explore the Official Study Guide:**  
  Review the official Microsoft study guide for an itemized breakdown of testable objectives.

- 👥 **Connect with Microsoft Training Services Partners:**  
  Find authorized training partners worldwide at the [Microsoft Training Services Partner Directory](https://learn.microsoft.com/en-us/credentials/support/help#training-services-partners).

---

## 📊 Exam Blueprint & Skills Measured

| Domain / Skill Area | Weighting |
| :--- | :---: |
| **Design a Zero Trust strategy and architecture** | **20–25%** |
| **Evaluate Governance Risk Compliance (GRC) and security operations** | **20–25%** |
| **Design security for infrastructure** | **20–25%** |
| **Design a strategy for data and applications** | **20–25%** |

---

## 💡 Practice & Preparation Materials

For comprehensive practice tests, high-yield scenario questions, and full-length exam simulations, explore the dedicated practice resources for [SC-100](https://www.certsclub.com/microsoft/).

---

## 📝 10 Realistic Demo Practice Questions & Answers

### Question 1 (Domain: Zero Trust Strategy)
**Scenario / Question:** You are architecting a Zero Trust strategy for an enterprise. You need to transition from the legacy tier-based administrative model to Microsoft's modern Enterprise Access Model. What are the three primary access planes defined in the Enterprise Access Model?
- A) Control Plane, Management Plane, and User Access Plane
- B) Privileged Access, Enterprise Access, and Specialized Access
- C) IaaS Plane, PaaS Plane, and SaaS Plane
- D) Front-end, Middle-tier, and Back-end
- **Correct Answer:** **B**
- **Detailed Explanation:** The Enterprise Access Model divides access into three tiers: Privileged Access (highest impact/admins), Specialized Access (developers, high-value business roles), and Enterprise Access (standard productivity users).

---
### Question 2 (Domain: Security Operations)
**Scenario / Question:** You need to architect an integrated Security Operations (SecOps) solution that correlates raw signal telemetry from endpoints, cloud identities, emails, SaaS applications, and infrastructure VMs into unified attack stories. Which integrated architecture should you design?
- A) Microsoft Sentinel unified with Microsoft Defender XDR
- B) Syslog server connected to Azure Storage
- C) Azure Network Watcher with Event Hubs
- D) Microsoft Intune with Azure Monitor
- **Correct Answer:** **A**
- **Detailed Explanation:** Integrating Microsoft Defender XDR (extended detection and response for domain workloads) with Microsoft Sentinel (SIEM/SOAR) provides full end-to-end visibility and unified incident correlation.

---
### Question 3 (Domain: Identity Architecture)
**Scenario / Question:** You are designing an identity security architecture. An authenticated user session experiences an immediate password revocation or elevated user risk event in Entra ID. You need the active session to be terminated within seconds rather than waiting for OAuth access token expiration (1 hour). What feature must you mandate?
- A) Continuous Access Evaluation (CAE)
- B) Standard Token Refresh
- C) Password Hash Synchronization
- D) Entra ID Application Proxy
- **Correct Answer:** **A**
- **Detailed Explanation:** Continuous Access Evaluation (CAE) enables near real-time revocation of active user sessions when critical security events (account disabled, password changed, IP risk) occur.

---
### Question 4 (Domain: Data Security)
**Scenario / Question:** You need to design a comprehensive data governance strategy that automatically classifies sensitive intellectual property stored across Azure SQL, Amazon S3 buckets, on-premises file shares, and Microsoft 365. Which solution provides unified cross-cloud data map and classification?
- A) Microsoft Purview Data Map and Information Protection
- B) Azure Key Vault
- C) Microsoft Defender for Endpoint
- D) Azure Application Gateway
- **Correct Answer:** **A**
- **Detailed Explanation:** Microsoft Purview provides automated data discovery, scanning, and sensitive data classification across multi-cloud and on-premises data stores.

---
### Question 5 (Domain: Cloud Security Posture)
**Scenario / Question:** You are designing security governance for an enterprise running workloads in Azure, AWS, and Google Cloud Platform (GCP). You need centralized Cloud Security Posture Management (CSPM) with regulatory compliance tracking across all three clouds in a single pane of glass. What should you architect?
- A) Microsoft Defender for Cloud with multi-cloud connectors for AWS and GCP
- B) Deploy separate SIEM tools in each cloud
- C) CloudWatch integrated with CloudTrail
- D) Azure Migrate only
- **Correct Answer:** **A**
- **Detailed Explanation:** Microsoft Defender for Cloud natively supports multi-cloud environments, assessing CSPM and CIS/NIST benchmarks across Azure, AWS, and GCP.

---
### Question 6 (Domain: DevSecOps)
**Scenario / Question:** You are designing a secure software development lifecycle (SSDLC) strategy for development teams using GitHub Enterprise. You need automated secret scanning, code dependency vulnerability scanning, and static code analysis (CodeQL) integrated into developer PR workflows. What should you recommend?
- A) GitHub Advanced Security (GHAS)
- B) Windows Defender Antivirus
- C) Azure Bastion
- D) Log Analytics Agent
- **Correct Answer:** **A**
- **Detailed Explanation:** GitHub Advanced Security delivers code scanning (CodeQL), secret scanning, and Dependabot dependency review natively within GitHub workflows.

---
### Question 7 (Domain: Infrastructure Security)
**Scenario / Question:** To mitigate lateral movement during an infrastructure breach, you need to design micro-segmentation for production workloads in Azure. Which combination of controls should be implemented?
- A) Hub-and-Spoke VNets, Network Security Groups (NSGs), Application Security Groups (ASGs), and Azure Firewall with IDPS
- B) Single flat VNet with /16 subnet and no NSGs
- C) Public IP addresses on every VM with port 3389 open
- D) DNS forwarding only
- **Correct Answer:** **A**
- **Detailed Explanation:** Zero Trust network micro-segmentation uses isolated spoke VNets, NSGs/ASGs for east-west boundary enforcement, and Azure Firewall with IDPS for north-south traffic inspection.

---
### Question 8 (Domain: Application Security)
**Scenario / Question:** You are designing security for enterprise SaaS applications. You must enforce real-time session controls that block file downloads on unmanaged personal devices when accessing corporate Salesforce and ServiceNow portals. What should you implement?
- A) Microsoft Defender for Cloud Apps Conditional Access App Control
- B) Azure ExpressRoute Direct
- C) Azure Virtual Network NAT
- D) Local Group Policy Object
- **Correct Answer:** **A**
- **Detailed Explanation:** Microsoft Defender for Cloud Apps Conditional Access App Control uses reverse proxy architecture to apply real-time session policies (e.g., block download) on unmanaged endpoints.

---
### Question 9 (Domain: Ransomware Defense)
**Scenario / Question:** An enterprise wants to protect its backup repositories from deletion or modification by compromised administrative credentials during a ransomware attack. Which architecture pattern should you design?
- A) Azure Backup with Immutable Vaults, Multi-User Authorization (MUA), and Soft Delete
- B) Standard file copy to an open SMB share
- C) Local disk backups with shared admin passwords
- D) Cloud Shell crontab
- **Correct Answer:** **A**
- **Detailed Explanation:** Immutable Backup Vaults combined with Multi-User Authorization (Resource Guard) and Soft Delete prevent ransomware actors from modifying or deleting backup points.

---
### Question 10 (Domain: Governance & Benchmarks)
**Scenario / Question:** Which security baseline from Microsoft provides prescriptive recommendations and guidance for securing cloud services, mapping directly to NIST, CIS, and PCI-DSS frameworks?
- A) Microsoft Cloud Security Benchmark (MCSB)
- B) Windows 95 Compatibility Guide
- C) Azure Pricing Calculator
- D) Microsoft Office User Guide
- **Correct Answer:** **A**
- **Detailed Explanation:** Microsoft Cloud Security Benchmark (MCSB) defines standardized, cloud-centric security recommendations mapped to major international compliance standards.

---

## 💬 Community Discussion & Study Group

Have questions regarding SC-100 concepts, study plans, or exam strategies?
- 💬 **Ask a question or start a topic:** [GitHub Discussions](https://github.com/MicrosoftLearnHub/SC-100---Microsoft-Cybersecurity-Architect/discussions)
- 🐛 **Report corrections or suggest updates:** [GitHub Issues](https://github.com/MicrosoftLearnHub/SC-100---Microsoft-Cybersecurity-Architect/issues)
- 🤝 **Contribute:** Open a Pull Request to share study notes, architecture diagrams, and review materials.

---

## 📂 Detailed Topic Documentation Index

- 📘 [01-zero-trust-strategy-and-architecture.md](./docs/01-zero-trust-strategy-and-architecture.md)
- 📘 [02-grc-and-secops-strategy.md](./docs/02-grc-and-secops-strategy.md)
- 📘 [03-infrastructure-security-design.md](./docs/03-infrastructure-security-design.md)
- 📘 [04-data-and-application-security.md](./docs/04-data-and-application-security.md)
- 📘 [05-ransomware-mitigation-and-business-resilience.md](./docs/05-ransomware-mitigation-and-business-resilience.md)
- 📘 [06-multi-cloud-and-hybrid-security.md](./docs/06-multi-cloud-and-hybrid-security.md)
- 📘 [07-official-resources-and-links.md](./docs/07-official-resources-and-links.md)

---

## 🌐 Official Microsoft Learning Resources

- 🌐 [Microsoft Learn Certification Directory](https://learn.microsoft.com/en-us/credentials/certifications/)
- 🌐 [Microsoft Learn Free Interactive Modules](https://learn.microsoft.com/en-us/training/)
- 🌐 [Find a Microsoft Training Services Partner](https://learn.microsoft.com/en-us/credentials/support/help#training-services-partners)

---

### 🛡️ Disclaimer
*This repository contains educational study notes, architecture summaries, and reference documentation compiled from publicly available official Microsoft Learn documentation. Microsoft, Azure, and Microsoft Entra are trademarks of the Microsoft group of companies.*
