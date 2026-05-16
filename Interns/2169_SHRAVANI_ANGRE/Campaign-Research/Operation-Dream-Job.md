# Operation Dream Job

## Campaign Overview

Operation Dream Job is a cyber espionage campaign
associated with the Lazarus Group. The campaign
targets aerospace, defense, cryptocurrency,
and government organizations using fake job
offers and social engineering attacks.

---

# Threat Actor / Group Association

| Threat Actor | Country |
|--------------|----------|
| Lazarus Group | North Korea |

The Lazarus Group is known for conducting
cyber espionage, financial theft, and
advanced persistent threat (APT) operations.

---

# Timeline

| Year | Activity |
|------|----------|
| 2020 | Initial campaign activity observed |
| 2021 | Increased LinkedIn phishing attacks |
| 2022 | Expansion towards aerospace sector |
| 2023 | Malware delivery using fake recruiters |

---

# Objectives of Attack

- Cyber espionage
- Credential theft
- Initial access into organizations
- Malware deployment
- Data exfiltration

---

# Targeted Sectors / Countries

## Sectors

- Aerospace
- Defense
- Cryptocurrency
- Government
- Research Organizations

## Countries

- United States
- India
- South Korea
- Japan
- European countries

---

# Attack Flow

1. Fake recruiter contacts target
2. Phishing message or fake job offer sent
3. Victim downloads malicious file
4. Malware executes on system
5. Persistence established
6. Data collection begins
7. Command and control communication initiated
8. Sensitive information exfiltrated

---

# MITRE ATT&CK Techniques Used

| Technique | ATT&CK ID |
|-----------|-----------|
| Phishing | T1566 |
| User Execution | T1204 |
| PowerShell | T1059.001 |
| Command and Scripting Interpreter | T1059 |
| Persistence | T1547 |
| Masquerading | T1036 |
| Encrypted Channel | T1573 |

---

# Real-world Incidents

- Fake LinkedIn recruiter campaigns
- Aerospace employee targeting
- Cryptocurrency company intrusions
- Malware deployment through fake interviews

---

# Detection Opportunities

- Monitor suspicious LinkedIn interactions
- Detect malicious attachments
- Monitor PowerShell execution
- Identify unusual outbound encrypted traffic
- Detect unknown startup entries

---

# Defensive Recommendations

- Security awareness training
- Email attachment filtering
- Endpoint Detection and Response (EDR)
- Multi-factor authentication (MFA)
- Network traffic monitoring
- Restrict unauthorized PowerShell usage

---

# References

- MITRE ATT&CK
- Microsoft Threat Intelligence
- CrowdStrike Research
- CISA Advisories
