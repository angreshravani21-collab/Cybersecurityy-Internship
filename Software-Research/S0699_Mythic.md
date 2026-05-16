# S0699 — Mythic

## Name & Type

| Field | Details |
|------|---------|
| Name | Mythic |
| ATT&CK ID | S0699 |
| Type | Command and Control (C2) Framework |

---

# Description

Mythic is an open-source
command-and-control framework
used for red team and offensive
security operations.

It supports payload management,
remote command execution,
and post-exploitation activities.

---

# Threat Actor Association

- Red Team operators
- APT actors

---

# Supported Platforms

- Windows
- Linux
- macOS

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Command Execution | T1059 |
| Encrypted Channel | T1573 |
| Remote Services | T1021 |

---

# Execution Method

- Payload execution
- Remote command execution

---

# Persistence Techniques

- Payload-dependent persistence
- Registry modifications

---

# Privilege Escalation

- Token abuse
- Privilege misuse

---

# Defense Evasion

- Encrypted traffic
- Obfuscation techniques

---

# Credential Access

- Payload-supported credential collection

---

# Discovery Techniques

- System information discovery
- Network discovery

---

# Lateral Movement

- Remote services
- SMB-based movement

---

# Command & Control

Encrypted command-and-control
communication channels.

---

# Exfiltration

- File transfer
- Encrypted data uploads

---

# Impact Analysis

- Persistent remote access
- Data compromise
- Lateral movement across systems

---

# Indicators of Compromise (IOCs)

## Network Indicators
- Suspicious outbound encrypted traffic

## Process Indicators
- Unknown payload execution

## Registry Indicators
- Unexpected persistence entries

---

# Detection & Mitigation

## Detection

- Monitor C2 communication patterns
- Detect suspicious remote execution
- Monitor persistence modifications

## Mitigation

- Use EDR solutions
- Restrict unauthorized payload execution
- Monitor network traffic

---

# References & Sources

- MITRE ATT&CK
- GitHub Research
- Threat Intelligence Reports
- 
