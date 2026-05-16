# S0696 — Flagpro

## Name & Type

| Field | Details |
|------|---------|
| Name | Flagpro |
| ATT&CK ID | S0696 |
| Type | Malware Loader |

---

# Description

Flagpro is malware used for
payload delivery and execution
on compromised systems.

It supports malware deployment,
remote execution, and persistence activities.

---

# Threat Actor Association

- APT groups

---

# Supported Platforms

- Windows

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| User Execution | T1204 |
| Command Execution | T1059 |
| Persistence | T1547 |

---

# Execution Method

- Malicious document execution
- Payload delivery through phishing

---

# Persistence Techniques

- Startup entries
- Registry persistence

---

# Privilege Escalation

- Privilege misuse
- Administrative access abuse

---

# Defense Evasion

- Obfuscation techniques
- Hidden execution

---

# Credential Access

- Credential collection

---

# Discovery Techniques

- System discovery
- Network information collection

---

# Lateral Movement

- Remote execution
- Service-based movement

---

# Command & Control

Encrypted communication
with attacker-controlled servers.

---

# Exfiltration

- Data transfer
- File extraction

---

# Impact Analysis

- Malware deployment
- Persistent compromise
- Unauthorized access

---

# Indicators of Compromise (IOCs)

## File Indicators
- Suspicious executable payloads

## Registry Indicators
- Unknown startup entries

## Network Indicators
- Unusual outbound communication

---

# Detection & Mitigation

## Detection

- Monitor startup modifications
- Detect suspicious payload execution
- Monitor network traffic

## Mitigation

- Use antivirus and EDR solutions
- Restrict unauthorized applications
- Apply email filtering

---

# References & Sources

- MITRE ATT&CK
- Threat Intelligence Reports
- VirusTotal
