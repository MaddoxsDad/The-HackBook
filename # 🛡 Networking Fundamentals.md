# 🛡 Networking Fundamentals

## 📌 Overview
| **Switch** | Connects devices within a LAN, forwarding packets based on MAC addresses. |
| **Firewall** | Enforces security policies by filtering network traffic. |
| **IDS/IPS** | Monitors (IDS) or actively blocks (IPS) suspicious traffic. |
| **Load Balancer** | Distributes incoming network traffic across multiple servers. |

### **Networking Models**
- **OSI Model (7 Layers)**: Conceptual framework for data communication.
- **TCP/IP Model**: Practical implementation used in modern networking.
- **Zero Trust Architecture (ZTA)**: "Never trust, always verify" model.

---

## 🔹 **Common Network Threats**
| Attack Type | Description | Real-World Example |
|------------|-------------|--------------------|
| **Man-in-the-Middle (MITM)** | Intercepts and manipulates communications. | [NSA PRISM Program](https://en.wikipedia.org/wiki/PRISM_(surveillance_program)) |
| **Denial of Service (DoS)** | Floods a network/service to render it unusable. | [Dyn Cyberattack (2016)](https://en.wikipedia.org/wiki/2016_Dyn_cyberattack) |
| **DNS Spoofing** | Redirects users to malicious sites by altering DNS responses. | [Kaminsky DNS Exploit](https://en.wikipedia.org/wiki/Dan_Kaminsky) |
| **Session Hijacking** | Exploits active sessions to gain unauthorized access. | [Firesheep (2010)](https://en.wikipedia.org/wiki/Firesheep) |

---

# 🔐 Encryption & Cryptography

## 📌 Overview
Cryptography is essential to data confidentiality, integrity, and authentication. Its mathematical foundations secure communications, financial transactions, and authentication mechanisms.

## 🔹 **Types of Cryptographic Systems**
| Type | Description | Example Algorithms |
|------|------------|--------------------|
| **Symmetric Encryption** | Uses one key for both encryption & decryption. | AES, DES, Blowfish |
| **Asymmetric Encryption** | Uses a key pair (public/private) for secure communication. | RSA, ECC, Diffie-Hellman |
| **Hashing** | Converts data into a fixed-length digest (irreversible). | SHA-256, MD5, Bcrypt |
| **Digital Signatures** | Ensures data authenticity & non-repudiation. | RSA, DSA, ECDSA |

---

## 🔹 **Public Key Infrastructure (PKI)**
PKI secures communication by issuing and managing digital certificates.

### **Key Components**
- **Certificate Authority (CA)** – Issues and verifies digital certificates.
- **Registration Authority (RA)** – Validates identity before certificate issuance.
- **Digital Certificates** – Ties an entity’s identity to a cryptographic key.

---

## 🔹 **Real-World Cryptographic Applications**
| Application | Description |
|------------|-------------|
| **TLS/SSL** | Encrypts HTTPS traffic to prevent MITM attacks. |
| **PGP (Pretty Good Privacy)** | Encrypts emails and files. |
| **Blockchain Cryptography** | Uses hashing and asymmetric encryption for immutable transactions. |

---

## 🔹 **Common Cryptographic Attacks**
| Attack Type | Description | Real-World Example |
|------------|-------------|--------------------|
| **Brute Force Attack** | Tries all possible keys/passwords systematically. | [2012 LinkedIn Breach](https://en.wikipedia.org/wiki/2012_LinkedIn_hack) |
| **Rainbow Table Attack** | Uses precomputed hash values to crack passwords. | [NTLM Hash Exploitation](https://en.wikipedia.org/wiki/NT_LAN_Manager) |
| **Side-Channel Attack** | Exploits cryptographic system weaknesses (e.g., power consumption). | [Spectre & Meltdown (2018)](https://en.wikipedia.org/wiki/Meltdown_(security_vulnerability)) |

---

# 🖥 Security Information and Event Management (SIEM)

## 📌 Overview
Security Information and Event Management (SIEM) provides real-time security monitoring, analysis, and correlation of events across enterprise environments.

---

## 🔹 **Core SIEM Functionalities**
| Function | Description |
|----------|------------|
| **Log Collection** | Aggregates logs from diverse security sources. |
| **Event Correlation** | Identifies patterns and anomalies indicative of cyber threats. |
| **Incident Response** | Automates alerts, notifications, and remediation workflows. |
| **Compliance Monitoring** | Ensures regulatory adherence (GDPR, HIPAA, PCI-DSS). |

---

## 🔹 **SIEM Deployment Models**
| Model | Description | Example SIEM Solutions |
|-------|-------------|------------------------|
| **On-Premises** | Locally hosted SIEM solution. | Splunk, ArcSight |
| **Cloud-Based** | Managed SIEM solutions hosted on cloud infrastructure. | Microsoft Sentinel, IBM QRadar Cloud |
| **Hybrid** | Mix of on-premises and cloud SIEM deployment. | Elastic SIEM |

---

## 🔹 **Log Sources for SIEM**
- **Network Security Devices** (Firewalls, IDS/IPS)
- **Operating Systems** (Windows Event Logs, Syslog)
- **Applications** (Web Servers, Database Logs)
- **Threat Intelligence Feeds** (Malware indicators, anomaly detection)

---

## 🔹 **SIEM Use Cases**
| Use Case | Description |
|----------|-------------|
| **Advanced Persistent Threat (APT) Detection** | Identifies stealthy cyberattacks over time. |
| **Insider Threat Monitoring** | Detects unauthorized access or unusual user behavior. |
| **Forensic Investigation** | Analyzes historical log data for security incidents. |

---

## 📜 Summary
- **Networking** is the foundation of secure communication and infrastructure.
- **Encryption** safeguards data integrity, confidentiality, and authenticity.
- **SIEM** enhances proactive security monitoring, incident response, and compliance.

---

🚀 **Secure, Analyze, Defend – Repeat!** 🏴‍☠️