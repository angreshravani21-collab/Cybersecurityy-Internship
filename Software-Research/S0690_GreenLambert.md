# S0690 — GreenLambert

## Name & Type
- Type: Espionage Malware

---

# Description

GreenLambert is malware associated with
cyber espionage and stealth operations.
It is designed to maintain covert access,
collect sensitive information, and support
long-term surveillance activities.

---

# Threat Actor Association
- Advanced Persistent Threat (APT) actors

---

# Supported Platforms
- Windows

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Command Execution | T1059 |
| Masquerading | T1036 |
| Persistence | T1547 |
| Encrypted Channel | T1573 |

---

# Execution Method
- Malicious payload execution
- Phishing-based delivery

---

# Persistence Techniques
- Registry persistence
- Startup entries

---

# Privilege Escalation
- Administrative privilege abuse

---

# Defense Evasion
- Process hiding
- Obfuscation techniques

---

# Credential Access
- Credential collection

---

# Discovery Techniques
- System information discovery
- Network discovery

---

# Lateral Movement
- Remote execution
- Remote services

---

# Command & Control
- Encrypted remote communication

---

# Exfiltration
- Sensitive data transfer

---

# Impact Analysis
- Espionage activities
- Sensitive data compromise
- Persistent unauthorized access

---

# Indicators of Compromise (IOCs)
- Unknown background processes
- Suspicious encrypted traffic

---

# Detection & Mitigation

## Detection
- Monitor suspicious processes
- Detect unusual outbound connections
- Monitor registry persistence

## Mitigation
- Use endpoint security solutions
- Restrict unauthorized execution
- Monitor network traffic

---

# References & Sources
- MITRE ATT&CK
- Threat Intelligence Reports
- VirusTotal
