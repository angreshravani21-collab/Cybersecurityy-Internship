# S0693 — CaddyWiper

## Name & Type

| Field | Details |
|------|---------|
| Name | CaddyWiper |
| ATT&CK ID | S0693 |
| Type | Wiper Malware |

---

# Description

CaddyWiper is destructive malware
designed to erase user data and
disrupt targeted systems.

The malware focuses on damaging
storage systems and preventing recovery.

---

# Threat Actor Association

- Sandworm Group

---

# Supported Platforms

- Windows

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Data Destruction | T1485 |
| Disk Structure Wipe | T1561.001 |
| Service Stop | T1489 |

---

# Execution Method

- Malicious executable payload
- Remote deployment

---

# Persistence Techniques

- Temporary persistence before wiping

---

# Privilege Escalation

- Administrative privilege abuse

---

# Defense Evasion

- Recovery disabling
- Service termination

---

# Credential Access

- Limited credential access

---

# Discovery Techniques

- Drive enumeration
- System discovery

---

# Lateral Movement

- Network propagation attempts

---

# Command & Control

- Limited communication activity

---

# Exfiltration

- Minimal exfiltration focus

---

# Impact Analysis

- Data destruction
- System downtime
- Permanent file loss

---

# Indicators of Compromise (IOCs)

## File Indicators
- Corrupted files
- Deleted partitions

## System Indicators
- Sudden service termination

---

# Detection & Mitigation

## Detection

- Monitor destructive file activity
- Detect suspicious service stopping
- Monitor disk modification behavior

## Mitigation

- Maintain regular backups
- Restrict administrative access
- Use endpoint security tools

---

# References & Sources

- MITRE ATT&CK
- CISA Advisories
- Threat Intelligence Reports
