# S0691 — Whirlpool

> Note: Software naming follows assigned internship documentation.

## Name & Type

| Field | Details |
|------|---------|
| Name | Whirlpool |
| ATT&CK ID | S0691 |
| Type | TLS Reverse Shell |

---

# Description

Whirlpool is a stealthy reverse shell malware
used for encrypted command-and-control (C2)
communication between attacker and victim systems.

It supports remote command execution,
encrypted communication, and covert access.

---

# Threat Actor Association

- Lazarus Group

---

# Supported Platforms

- Windows
- Linux
- macOS

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Command and Scripting Interpreter | T1059 |
| Encrypted Channel | T1573 |
| Masquerading | T1036 |
| System Information Discovery | T1082 |

---

# Execution Method

- Executed through malicious payloads
- Remote shell execution
- Command execution through encrypted sessions

---

# Persistence Techniques

- Startup scripts
- Scheduled tasks
- Registry persistence

---

# Privilege Escalation

- Abuse of system permissions
- Administrative privilege misuse

---

# Defense Evasion

- TLS encrypted communication
- Process masquerading
- Obfuscation techniques

---

# Credential Access

- Shell-based credential collection
- Access to stored credentials

---

# Discovery Techniques

- System information discovery
- Network discovery
- Process enumeration

---

# Lateral Movement

- Remote shell communication
- Remote command execution

---

# Command & Control

Whirlpool communicates with attacker-controlled
servers using encrypted HTTPS/TLS channels.

---

# Exfiltration

- Encrypted transfer of collected data
- Remote file extraction

---

# Impact Analysis

- Persistent unauthorized access
- Remote system compromise
- Data theft and espionage activities

---

# Indicators of Compromise (IOCs)

## File Names
- whirlpool.exe
- ssld.exe

## Process Names
- ssld.exe

## Network Indicators
- Suspicious outbound TLS traffic

---

# Detection & Mitigation

## Detection

- Monitor unusual encrypted outbound traffic
- Detect suspicious shell execution activity
- Monitor startup persistence entries

## Mitigation

- Use Endpoint Detection & Response (EDR)
- Restrict unauthorized execution
- Monitor network traffic
- Apply least privilege access

---

# References & Sources

- MITRE ATT&CK
- VirusTotal
- MalwareBazaar
- Threat Intelligence Reports
