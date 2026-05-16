# S0697 — HermeticWiper

## Name & Type

| Field | Details |
|------|---------|
| Name | HermeticWiper |
| ATT&CK ID | S0697 |
| Type | Wiper Malware |

---

# Description

HermeticWiper is destructive malware
designed to corrupt data and disable
Windows systems.

The malware targets storage systems
to cause operational disruption and data loss.

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

- Malicious executable deployment
- Remote malware execution

---

# Persistence Techniques

- Temporary persistence before destruction

---

# Privilege Escalation

- Administrative privilege abuse

---

# Defense Evasion

- Driver abuse
- Recovery disabling

---

# Credential Access

- Limited credential access

---

# Discovery Techniques

- Drive discovery
- System information gathering

---

# Lateral Movement

- Network spread attempts

---

# Command & Control

- Limited communication activity

---

# Exfiltration

- Minimal exfiltration activity

---

# Impact Analysis

- System destruction
- Data corruption
- Operational downtime

---

# Indicators of Compromise (IOCs)

## File Indicators
- Corrupted drives
- Missing files

## System Indicators
- Unexpected shutdowns
- Failed recovery attempts

---

# Detection & Mitigation

## Detection

- Monitor destructive disk activity
- Detect suspicious driver execution
- Monitor service termination

## Mitigation

- Maintain secure backups
- Restrict administrative privileges
- Use endpoint protection tools

---

# References & Sources

- MITRE ATT&CK
- CISA Advisories
- Threat Intelligence Reports
