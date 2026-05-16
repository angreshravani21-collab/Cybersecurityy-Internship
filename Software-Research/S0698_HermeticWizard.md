# S0698 — HermeticWizard

## Name & Type

| Field | Details |
|------|---------|
| Name | HermeticWizard |
| ATT&CK ID | S0698 |
| Type | Worm Malware |

---

# Description

HermeticWizard is a worm malware
used for spreading malicious payloads
across networked systems.

It supports rapid malware propagation
through remote services and shared networks.

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
| Remote Services | T1021 |
| Ingress Tool Transfer | T1105 |
| Network Service Scanning | T1046 |

---

# Execution Method

- Network propagation
- Remote payload deployment

---

# Persistence Techniques

- Service creation
- Startup persistence

---

# Privilege Escalation

- Privilege abuse
- Administrative access misuse

---

# Defense Evasion

- Service masquerading
- Hidden execution activity

---

# Credential Access

- Credential usage
- Access token usage

---

# Discovery Techniques

- Network scanning
- Shared drive discovery

---

# Lateral Movement

- SMB propagation
- Remote services exploitation

---

# Command & Control

Remote communication with
attacker-controlled infrastructure.

---

# Exfiltration

- Limited exfiltration activity

---

# Impact Analysis

- Rapid malware spread
- Network-wide compromise
- Operational disruption

---

# Indicators of Compromise (IOCs)

## Network Indicators
- Suspicious SMB traffic

## Service Indicators
- Unknown created services

## File Indicators
- Suspicious copied payloads

---

# Detection & Mitigation

## Detection

- Monitor SMB traffic
- Detect suspicious service creation
- Monitor network scanning activity

## Mitigation

- Segment networks
- Restrict SMB access
- Use endpoint monitoring tools

---

# References & Sources

- MITRE ATT&CK
- Security Research Reports
- CISA Advisories
