# Warmaksan IT Security Project

### --
## Overview
This repository contains a full IT security assessment and improvement plan for **Warmaksan**.  
It covers critical assets, risk analysis, countermeasures, policies, and alignment with **CIA principles** and **ISO 31000 risk management** standards.  

Prepared by **Farouq Hassan**  
Supervised by **Dr. Safaa Hriez**:contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}

### --
## Features
- **Asset Inventory & CIA Mapping** – endpoints, servers, storage, cloud, applications, data, and networking:contentReference[oaicite:2]{index=2}  
- **Risk Register** – likelihood vs. consequence matrix with prioritized risks:contentReference[oaicite:3]{index=3}  
- **Countermeasures** – proposed security controls for each asset:contentReference[oaicite:4]{index=4}  
- **Improvement Plan** – access control, encryption, DR/BCP, network segmentation, IDS/IPS:contentReference[oaicite:5]{index=5}  
- **Audit Analysis** – misconfigurations, weak password policy, lack of segmentation, physical exposure:contentReference[oaicite:6]{index=6}  
- **Security Policies** – Backup (GFS), Remote Access, Firewall/VPN, Third-Party, GDPR, Clean Desk, Password Policy:contentReference[oaicite:7]{index=7}  
- **Physical & Virtual Security Benefits** – CCTV surveillance and VPN-secured remote access:contentReference[oaicite:8]{index=8}

### --
## Security
**Critical Assets**:
- Endpoints, servers, storage, and cloud infrastructure  
- Applications, operating systems, security software, backup/recovery tools  
- Data (customer information, on-disk storage)  
- Networking (subnets, internet, web apps, VPN):contentReference[oaicite:9]{index=9}

**Threats & Vulnerabilities**:
- Malware, phishing, and physical theft  
- Misconfigured firewalls/VPNs  
- Weak passwords and outdated software  
- Unencrypted storage and data in transit  
- Data center physical exposure:contentReference[oaicite:10]{index=10}

**Controls & Countermeasures**:
- Strong passwords, MFA, and RBAC:contentReference[oaicite:11]{index=11}  
- Encryption (AES/RSA) for data at rest and in transit:contentReference[oaicite:12]{index=12}  
- Secure configuration and patch management:contentReference[oaicite:13]{index=13}  
- Backup & recovery drills using **GFS method**:contentReference[oaicite:14]{index=14}  
- CCTV, locks, biometrics for physical access:contentReference[oaicite:15]{index=15}:contentReference[oaicite:16]{index=16}

### --
## Project Structure
```text
warmaksan-security/
├─ docs/
│  ├─ assets-cia-analysis.md
│  ├─ risk-register.md
│  ├─ countermeasures.md
│  ├─ audit-findings.md
│  └─ improvement-plan.md
├─ policies/
│  ├─ backup-policy.md
│  ├─ remote-access-policy.md
│  ├─ firewall-vpn-policy.md
│  ├─ third-party-policy.md
│  ├─ gdpr-compliance.md
│  ├─ clean-desk-policy.md
│  └─ password-policy.md
└─ README.md
--
Installation
This project is documentation-focused. To use it locally:

# Clone the repo
git clone https://github.com/<org>/warmaksan-security.git
cd warmaksan-security

# (Optional) Install linting tools
npm install -g markdownlint-cli
markdownlint "**/*.md"
--
Testing
Validation is procedural, not automated:

Tabletop exercises: incident response & DR simulationsSecurity Final Project

Backup recovery drills: GFS restore testingSecurity Final Project

Access reviews: VPN and third-party account auditsSecurity Final Project

Configuration checks: firewalls, VPN ciphers, segmentationSecurity Final Project

Awareness training: phishing tests, password enforcementSecurity Final Project

--
Documentation & Analysis
Assets & CIA Principles: Confidentiality, Integrity, Availability analysis for hardware, software, data, and networksSecurity Final Project

Risk Assessment: Ranked risks from Extreme (e.g., customer data breach, data center exposure) to Low (VPN/Internet connection)Security Final Project

Audit Findings: password weaknesses, flat network design, unsecured data center accessSecurity Final Project

ISO 31000 Alignment: structured risk identification, analysis, treatment, monitoringSecurity Final Project

Security Benefits:

Monitoring systems: faster troubleshooting, anomaly detection, capacity planningSecurity

CCTV: surveillance and employee safetySecurity

VPN: secure remote accessSecurity

--
Technologies Used
Cryptography: AES, RSA encryptionSecurity Final Project

Network Security: Firewalls, VPN, IDS/IPS, segmentationSecurity Final Project

Backup: GFS method with offsite rotationSecurity Final Project

Physical Security: CCTV, locks, biometricsSecuritySecurity Final Project

Risk Management: ISO 31000 frameworkSecurity Final Project

Compliance: GDPR requirements (DPO, breach reporting, data subject rights)Security Final Project

--
License
This repository is for educational and organizational purposes.
For public release, apply an open license (MIT, CC BY-SA, etc.) based on organizational policy.

Prepared by: Farouq Hassan
Supervised by: Dr. Safaa Hriez
SecuritySecurity Final Project
