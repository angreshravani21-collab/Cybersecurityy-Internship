# S0695 — Donut

## Name & Type

| Field | Details |
|------|---------|
| Name | Donut |
| ATT&CK ID | S0695 |
| Type | Shellcode Loader |

---

# Description

Donut is an open-source shellcode loader
used for in-memory execution of payloads.

It helps attackers deploy malware while
avoiding traditional file-based detection methods.

---

# Threat Actor Association

- Red Team operators
- APT actors

---

# Supported Platforms

- Windows

---

# ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Reflective Code Loading | T1620 |
| Process Injection | T1055 |
| Obfuscated Files or Information | T1027 |

---

# Execution Method

- In-memory payload execution
- Reflective loading

---

# Persistence Techniques

- Depends on deployed payload

---

# Privilege Escalation

- Token abuse
- Permission misuse

---

# Defense Evasion

- Memory-only execution
- Payload obfuscation

---

# Credential Access

- Payload-dependent credential access

---

# Discovery Techniques

- System checks before execution
- Environment discovery

---

# Lateral Movement

- Depends on deployed payload

---

# Command & Control

- Payload-dependent communication

---

# Exfiltration

- Payload-dependent data transfer

---

# Impact Analysis

- Malware deployment
- Stealthy execution
- Evasion of detection

---

# Indicators of Compromise (IOCs)

## Process Indicators
- Suspicious injected processes

## Memory Indicators
- Reflective memory loading activity

---

# Detection & Mitigation

## Detection

- Monitor process injection activity
- Detect reflective loading behavior
- Analyze memory anomalies

## Mitigation

- Deploy EDR solutions
- Monitor memory activity
- Restrict unauthorized execution

---

# References & Sources

- MITRE ATT&CK
- GitHub Research
- Threat Intelligence Reports
