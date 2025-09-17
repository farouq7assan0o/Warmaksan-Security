## Overview

This repository contains a full **IT Security Assessment and Improvement Plan** for **Warmaksan**, prepared by **Farouq Hassan**. The project evaluates assets, risks, vulnerabilities, and existing controls against the **Confidentiality, Integrity, Availability (CIA)** triad. It recommends layered countermeasures, governance policies, and operational practices that align with **ISO 31000 risk management** and **GDPR compliance** requirements:contentReference[oaicite:0]{index=0}.

The work is based on a comprehensive written report and presentation that document:
- Risk registers and prioritization of vulnerabilities.
- Countermeasure design for hardware, software, networking, and data.
- Security and compliance policies tailored for Warmaksan.
- Physical and virtual security recommendations, including CCTV and VPN usage:contentReference[oaicite:1]{index=1}:contentReference[oaicite:2]{index=2}.

---

## Features

- **Asset-based CIA analysis:** Identifies endpoints, servers, storage, cloud, subnets, data centers, and applications as critical assets, and evaluates confidentiality, integrity, and availability impacts:contentReference[oaicite:3]{index=3}.
- **Risk Register:** Provides likelihood, consequence, and priority ratings for vulnerabilities (e.g., “Extreme” risk for servers, storage, customer data, and data center):contentReference[oaicite:4]{index=4}.
- **Controls & Countermeasures:** Suggests strong access controls, encryption, MFA, IDS/IPS, VPN, firewalls, segmentation, patching, and secure baselines:contentReference[oaicite:5]{index=5}.
- **Security Operations Improvements:** Incident response, disaster recovery, business continuity, and monitoring guidelines:contentReference[oaicite:6]{index=6}.
- **Physical & Virtual Security Measures:** CCTV for surveillance and employee safety, VPN for encrypted remote access:contentReference[oaicite:7]{index=7}.
- **Policy Suite:** Backup (Grandfather–Father–Son), Remote Access, Firewall & VPN, Third-Party Access, GDPR alignment, Clean Desk, Password policy:contentReference[oaicite:8]{index=8}.

---

## Security

### Key Risks
- **Data Center:** Weak physical controls create “doomsday” exposure. Recommended: biometric access, CCTV, locks, humidity/temperature monitoring:contentReference[oaicite:9]{index=9}.
- **Servers & Storage:** Extreme risks due to weak passwords and easy access. Recommended: hardening, patch SLAs, access controls, and encryption:contentReference[oaicite:10]{index=10}.
- **Customer Information:** Almost certain likelihood of compromise without encryption or role-based access. Recommended: MFA, RBAC, GDPR compliance:contentReference[oaicite:11]{index=11}.
- **Networking:** Single subnet across all stations increases attack surface. Recommended: segmentation, IDS/IPS, secure configurations:contentReference[oaicite:12]{index=12}.

### Core Security Themes
- **Identity & Access:** Strong passwords, MFA, RBAC/ABAC, credential rotation.
- **Data Protection:** AES/RSA encryption, tokenization, encrypted backups, restore testing.
- **Network & Endpoint:** Secure firewalls, VPNs, segmentation, device encryption, patch management.
- **Application Security:** Secure authentication, regular patching, vulnerability management.
- **Physical Controls:** CCTV monitoring, access logs, secured cabling and equipment:contentReference[oaicite:13]{index=13}:contentReference[oaicite:14]{index=14}.

---

## Testing

The project recommends continuous and structured testing:
- **Backup & Recovery Drills:** Validate Grandfather–Father–Son backup strategy and recovery time objectives:contentReference[oaicite:15]{index=15}.
- **Access Control Reviews:** Quarterly reviews of VPN, firewall, and privileged accounts.
- **Penetration Testing:** Simulated cyberattacks to identify weak points:contentReference[oaicite:16]{index=16}.
- **Social Engineering Tests:** Phishing and baiting simulations to test employee awareness:contentReference[oaicite:17]{index=17}.
- **Security Audits:** Regular audits to check policy alignment and regulatory compliance.
- **Environment Monitoring:** Test data center access and environmental controls:contentReference[oaicite:18]{index=18}.

---

## Documentation & Analysis

**Work Completed:**
- Conducted a **critical asset inventory** (hardware, software, data, networking) and mapped them against CIA:contentReference[oaicite:19]{index=19}.
- Built a **risk register** with threat/vulnerability analysis, likelihood, consequence, and prioritization:contentReference[oaicite:20]{index=20}.
- Proposed **countermeasures** for each asset type: access control, patching, encryption, segmentation, monitoring:contentReference[oaicite:21]{index=21}.
- Authored multiple **policies**: Backup, Remote Access, Firewall & VPN, Third-Party Access, GDPR compliance, Clean Desk, and Password Policy:contentReference[oaicite:22]{index=22}.
- Designed a **security audit & improvement process** to align IT security with organizational policies and compliance requirements:contentReference[oaicite:23]{index=23}.
- Recommended **ISO 31000 risk management methodology** for structured risk identification, treatment, and review:contentReference[oaicite:24]{index=24}.

---

## Technologies Used

- **Frameworks & Standards:** ISO 31000 Risk Management, GDPR compliance:contentReference[oaicite:25]{index=25}.
- **Security Tools:** Firewalls, VPN, IDS/IPS, MFA, AV/EDR, monitoring systems:contentReference[oaicite:26]{index=26}:contentReference[oaicite:27]{index=27}.
- **Encryption:** AES, RSA, TLS, secure backup systems:contentReference[oaicite:28]{index=28}.
- **Backup Strategy:** Grandfather–Father–Son method with offsite copies:contentReference[oaicite:29]{index=29}.
- **Testing Practices:** Penetration testing, vulnerability scanning, phishing simulations, social engineering tests:contentReference[oaicite:30]{index=30}.
- **Physical Security:** CCTV, biometric access, locks, controlled cabling:contentReference[oaicite:31]{index=31}:contentReference[oaicite:32]{index=32}.

---

## License

This project is shared under the **MIT License** for educational and professional reference.  
You may adapt it for your organization’s internal policies and compliance needs.

---
© Farouq Hassan — IT Security Assessment Project for Warmaksan:contentReference[oaicite:33]{index=33}:contentReference[oaicite:34]{index=34}
