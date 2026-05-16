# S0694 — DRATzarus

## Name & Type

| Field | Details |
|------|---------|
| Name | DRATzarus |
| ATT&CK ID | S0694 |
| Type | Remote Access Trojan (RAT) |

---

# Description

DRATzarus is a remote access trojan
associated with cyber espionage activities.

It provides attackers with remote control,
data collection capabilities, and persistent access
to compromised systems.

---

# Threat Actor Association

- Lazarus Group

---

# Supported Platforms

- Windows

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Remote Services | T1021 |
| Persistence | T1547 |
| Encrypted Channel | T1573 |
| Command Execution | T1059 |

---

# Execution Method

- Phishing attachments
- Malicious payload execution

---

# Persistence Techniques

- Registry startup entries
- Scheduled tasks

---

# Privilege Escalation

- Privilege abuse
- Administrative access misuse

---

# Defense Evasion

- Obfuscation techniques
- Encrypted communication

---

# Credential Access

- Credential theft
- Access to stored credentials

---

# Discovery Techniques

- System information collection
- User account discovery

---

# Lateral Movement

- Remote service exploitation
- Remote execution

---

# Command & Control

Encrypted remote communication
with attacker-controlled servers.

---

# Exfiltration

- Sensitive file transfer
- Encrypted data uploads

---

# Impact Analysis

- Espionage activities
- Data compromise
- Persistent unauthorized access

---

# Indicators of Compromise (IOCs)

## File Indicators
- Unknown executable files

## Registry Indicators
- Suspicious startup entries

## Network Indicators
- Unusual encrypted outbound traffic

---

# Detection & Mitigation

## Detection

- Monitor suspicious remote sessions
- Detect registry modifications
- Monitor outbound traffic patterns

## Mitigation

- Enable MFA
- Use endpoint monitoring tools
- Restrict unauthorized execution

---

# References & Sources

- MITRE ATT&CK
- VirusTotal
- Threat Intelligence Reports
