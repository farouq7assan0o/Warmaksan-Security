## Overview

This repository contains a full **IT Security Assessment and Improvement Plan** for **Warmaksan**, prepared by **Farouq Hassan**. The project evaluates assets, risks, vulnerabilities, and existing controls against the **Confidentiality, Integrity, Availability (CIA)** triad. It recommends layered countermeasures, governance policies, and operational practices that align with **ISO 31000 risk management** and **GDPR compliance** requirements.

The work is based on a comprehensive written report and presentation that document:
- Risk registers and prioritization of vulnerabilities.
- Countermeasure design for hardware, software, networking, and data.
- Security and compliance policies tailored for Warmaksan.
- Physical and virtual security recommendations, including CCTV and VPN usage.

## Features

- **Asset-based CIA analysis:** Identifies endpoints, servers, storage, cloud, subnets, data centers, and applications as critical assets, and evaluates confidentiality, integrity, and availability impacts.
- **Risk Register:** Provides likelihood, consequence, and priority ratings for vulnerabilities (e.g., “Extreme” risk for servers, storage, customer data, and data center).
- **Controls & Countermeasures:** Suggests strong access controls, encryption, MFA, IDS/IPS, VPN, firewalls, segmentation, patching, and secure baselines.
- **Security Operations Improvements:** Incident response, disaster recovery, business continuity, and monitoring guidelines.
- **Physical & Virtual Security Measures:** CCTV for surveillance and employee safety, VPN for encrypted remote access.
- **Policy Suite:** Backup (Grandfather–Father–Son), Remote Access, Firewall & VPN, Third-Party Access, GDPR alignment, Clean Desk, Password policy.

## Security

### Key Risks
- **Data Center:** Weak physical controls create critical exposure. Recommended: biometric access, CCTV, locks, humidity/temperature monitoring.
- **Servers & Storage:** Extreme risks due to weak passwords and easy access. Recommended: hardening, patch SLAs, access controls, and encryption.
- **Customer Information:** Almost certain likelihood of compromise without encryption or role-based access. Recommended: MFA, RBAC, GDPR compliance.
- **Networking:** Single subnet across all stations increases attack surface. Recommended: segmentation, IDS/IPS, secure configurations.

### Core Security Themes
- **Identity & Access:** Strong passwords, MFA, RBAC/ABAC, credential rotation.
- **Data Protection:** AES/RSA encryption, tokenization, encrypted backups, restore testing.
- **Network & Endpoint:** Secure firewalls, VPNs, segmentation, device encryption, patch management.
- **Application Security:** Secure authentication, regular patching, vulnerability management.
- **Physical Controls:** CCTV monitoring, access logs, secured cabling and equipment.

## Testing

The project recommends continuous and structured testing:
- **Backup & Recovery Drills:** Validate Grandfather–Father–Son backup strategy and recovery time objectives.
- **Access Control Reviews:** Quarterly reviews of VPN, firewall, and privileged accounts.
- **Penetration Testing:** Simulated cyberattacks to identify weak points.
- **Social Engineering Tests:** Phishing and baiting simulations to test employee awareness.
- **Security Audits:** Regular audits to check policy alignment and regulatory compliance.
- **Environment Monitoring:** Test data center access and environmental controls.

## Documentation & Analysis

**Work Completed:**
- Conducted a **critical asset inventory** (hardware, software, data, networking) and mapped them against CIA.
- Built a **risk register** with threat/vulnerability analysis, likelihood, consequence, and prioritization.
- Proposed **countermeasures** for each asset type: access control, patching, encryption, segmentation, monitoring.
- Authored multiple **policies**: Backup, Remote Access, Firewall & VPN, Third-Party Access, GDPR compliance, Clean Desk, and Password Policy.
- Designed a **security audit & improvement process** to align IT security with organizational policies and compliance requirements.
- Recommended **ISO 31000 risk management methodology** for structured risk identification, treatment, and review.

## Technologies Used

- **Frameworks & Standards:** ISO 31000 Risk Management, GDPR compliance.
- **Security Tools:** Firewalls, VPN, IDS/IPS, MFA, AV/EDR, monitoring systems.
- **Encryption:** AES, RSA, TLS, secure backup systems.
- **Backup Strategy:** Grandfather–Father–Son method with offsite copies.
- **Testing Practices:** Penetration testing, vulnerability scanning, phishing simulations, social engineering tests.
- **Physical Security:** CCTV, biometric access, locks, controlled cabling.

## License

This project is shared under the **MIT License** for educational and professional reference.  
You may adapt it for your organization’s internal policies and compliance needs.

---
© Farouq Hassan — IT Security Assessment Project for Warmaksan
