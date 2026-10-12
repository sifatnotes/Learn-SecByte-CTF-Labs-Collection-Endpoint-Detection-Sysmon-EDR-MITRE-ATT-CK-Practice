# Learn-SecByte-CTF-Labs-Collection-Endpoint-Detection-Sysmon-EDR-MITRE-ATT-CK-Practice
A curated collection of hands-on endpoint detection and threat intelligence CTF labs covering Microsoft Defender Telemetry, Sysmon Analysis, Windows Event Logs, EDR Forensics, Sigma Rules, and MITRE ATT&amp;CK Mapping from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on endpoint detection, Windows event logging, threat intelligence, and detection engineering labs designed for cybersecurity students, CTF players, SOC analysts, detection engineers, and incident response personnel.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Detecting sophisticated threat actors across modern enterprise endpoints requires mastering security telemetry, correlation frameworks, and threat intelligence. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenge labs focuses on practical endpoint investigation and alert tuning.

From analyzing Microsoft Defender for Endpoint alerts and hunting via Windows Event Logs and Sysmon, to authoring Sigma detection rules, mapping adversary techniques against the MITRE ATT&CK framework, and extracting actionable Indicators of Compromise (IOCs), these exercises build essential SOC analyst and threat detector skills.

---

## Lab Collection & Index

Below is the complete, searchable index of all endpoint detection and threat intelligence challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Microsoft Defender Analysis: Telemetry Triage & Detection Tuning** | EDR & Telemetry | MDE alert investigation, false positive tuning, advanced hunting queries (KQL) | [Access Lab](https://learn.secbyte.org/ctf/microsoft-defender-analysis-telemetry-triage-detection-tunin) |
| 2 | **Sysmon Sleuth: Detecting Malware with Windows Telemetry** | Endpoint Telemetry | Sysmon process creation, DNS queries, network connection correlation | [Access Lab](https://learn.secbyte.org/ctf/sysmon-sleuth-detecting-malware-with-windows-telemetry) |
| 3 | **Windows Event Log Analysis: Midnight Service Incident** | Log Forensics | Security event log parsing, Service Control Manager logs (Event ID 7045), logon audits | [Access Lab](https://learn.secbyte.org/ctf/windows-event-log-analysis-midnight-service-incident) |
| 4 | **Endpoint Detection & Response: Investigating Endpoint Security** | EDR Forensics | Process tree inspection, memory dumping, telemetry correlation, EDR triage | [Access Lab](https://learn.secbyte.org/ctf/endpoint-detection-response-investigating-the-endpoint-secur) |
| 5 | **Behavioral Beacon Detection** | Network & Host Hunting | C2 beacon jitter analysis, periodic network traffic detection, process injection | [Access Lab](https://learn.secbyte.org/ctf/behavioral-beacon-detection) |
| 6 | **Detection Engineering Fundamentals: Building Better Alerts** | Detection Engineering | Alert logic design, signal-to-noise ratio optimization, detection validation | [Access Lab](https://learn.secbyte.org/ctf/detection-engineering-fundamentals-building-better-alerts) |
| 7 | **Sigma Rule Development: From Logs to Detection** | Detection Engineering | YAML-based Sigma writing, log field mapping, SIEM rule conversion | [Access Lab](https://learn.secbyte.org/ctf/sigma-rule-development-from-logs-to-detection) |
| 8 | **MITRE ATT&CK Mapping Lab** | Threat Intelligence | TTP categorization, adversary technique mapping, coverage gap analysis | [Access Lab](https://learn.secbyte.org/ctf/mitre-attack-mapping-lab) |
| 9 | **Threat Intel for Malware Analysis** | Threat Intelligence | Threat actor attribution, campaign tracking, OSINT correlation | [Access Lab](https://learn.secbyte.org/ctf/threat-intel-for-malware-analysis) |
| 10 | **Behavioral Indicators of Compromise** | Threat Analysis | Anomaly detection, behavioral IOC identification, execution chain analysis | [Access Lab](https://learn.secbyte.org/ctf/behavioral-indicators-of-compromise) |
| 11 | **IOC Extraction & Evidence Triage Lab** | Evidence Triage | Hash extraction, domain/IP parsing, forensic evidence collection | [Access Lab](https://learn.secbyte.org/ctf/ioc-extraction-evidence-triage-lab) |
| 12 | **Malware Command and Control Infrastructure** | C2 Infrastructure | Domain generation algorithms (DGA), redirectors, staging servers, C2 profiling | [Access Lab](https://learn.secbyte.org/ctf/malware-command-and-control-infrastructure) |

---

## Categories

### 1. Endpoint Security & Telemetry Analysis
Analyze real-world host telemetry from Microsoft Defender, Sysmon, and Windows Event Logs to track down malicious execution.
- [Microsoft Defender Analysis: Telemetry Triage & Detection Tuning](https://learn.secbyte.org/ctf/microsoft-defender-analysis-telemetry-triage-detection-tunin)
- [Sysmon Sleuth: Detecting Malware with Windows Telemetry](https://learn.secbyte.org/ctf/sysmon-sleuth-detecting-malware-with-windows-telemetry)
- [Windows Event Log Analysis: Midnight Service Incident](https://learn.secbyte.org/ctf/windows-event-log-analysis-midnight-service-incident)
- [Endpoint Detection & Response: Investigating Endpoint Security](https://learn.secbyte.org/ctf/endpoint-detection-response-investigating-the-endpoint-secur)

### 2. Detection Engineering & Rule Authoring
Design robust detection logic, minimize false positives, and author vendor-neutral Sigma detection rules.
- [Detection Engineering Fundamentals: Building Better Alerts](https://learn.secbyte.org/ctf/detection-engineering-fundamentals-building-better-alerts)
- [Sigma Rule Development: From Logs to Detection](https://learn.secbyte.org/ctf/sigma-rule-development-from-logs-to-detection)

### 3. Threat Intelligence, IOC Triage & ATT&CK Mapping
Map security alerts against the MITRE ATT&CK framework, extract indicators of compromise, and profile threat infrastructure.
- [MITRE ATT&CK Mapping Lab](https://learn.secbyte.org/ctf/mitre-attack-mapping-lab)
- [Threat Intel for Malware Analysis](https://learn.secbyte.org/ctf/threat-intel-for-malware-analysis)
- [Behavioral Indicators of Compromise](https://learn.secbyte.org/ctf/behavioral-indicators-of-compromise)
- [IOC Extraction & Evidence Triage Lab](https://learn.secbyte.org/ctf/ioc-extraction-evidence-triage-lab)

### 4. Command & Control (C2) & Behavioral Hunting
Detect stealthy C2 beaconing patterns, periodic communication channels, and malicious infrastructure setups.
- [Behavioral Beacon Detection](https://learn.secbyte.org/ctf/behavioral-beacon-detection)
- [Malware Command and Control Infrastructure](https://learn.secbyte.org/ctf/malware-command-and-control-infrastructure)

---

## Learning Path

Follow this structured learning pathway to master endpoint security monitoring and threat detection:

1. **Phase 1: Log Telemetry & Windows Monitoring** — Learn essential host logging and event correlation:
   - [Windows Event Log Analysis: Midnight Service Incident](https://learn.secbyte.org/ctf/windows-event-log-analysis-midnight-service-incident)
   - [Sysmon Sleuth: Detecting Malware with Windows Telemetry](https://learn.secbyte.org/ctf/sysmon-sleuth-detecting-malware-with-windows-telemetry)

2. **Phase 2: EDR Triage & Defender Analysis** — Investigate enterprise EDR alerts and tune detections:
   - [Microsoft Defender Analysis: Telemetry Triage & Detection Tuning](https://learn.secbyte.org/ctf/microsoft-defender-analysis-telemetry-triage-detection-tunin)
   - [Endpoint Detection & Response: Investigating Endpoint Security](https://learn.secbyte.org/ctf/endpoint-detection-response-investigating-the-endpoint-secur)

3. **Phase 3: Threat Intelligence & Forensic Triage** — Extract technical indicators and map adversary TTPs:
   - [IOC Extraction & Evidence Triage Lab](https://learn.secbyte.org/ctf/ioc-extraction-evidence-triage-lab)
   - [Behavioral Indicators of Compromise](https://learn.secbyte.org/ctf/behavioral-indicators-of-compromise)
   - [MITRE ATT&CK Mapping Lab](https://learn.secbyte.org/ctf/mitre-attack-mapping-lab)
   - [Threat Intel for Malware Analysis](https://learn.secbyte.org/ctf/threat-intel-for-malware-analysis)

4. **Phase 4: C2 Infrastructure & Detection Engineering** — Detect network beacons and build production-ready detection rules:
   - [Behavioral Beacon Detection](https://learn.secbyte.org/ctf/behavioral-beacon-detection)
   - [Malware Command and Control Infrastructure](https://learn.secbyte.org/ctf/malware-command-and-control-infrastructure)
   - [Detection Engineering Fundamentals: Building Better Alerts](https://learn.secbyte.org/ctf/detection-engineering-fundamentals-building-better-alerts)
   - [Sigma Rule Development: From Logs to Detection](https://learn.secbyte.org/ctf/sigma-rule-development-from-logs-to-detection)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and telemetry samples provided on [Learn SecByte](https://learn.secbyte.org/).
3. Analyze host logs and network captures using tools such as Event Viewer, Sysmon log parsers, KQL, SIEM platforms, and Sigma converters.
4. Extract required indicators, map threat behaviors, validate alerts, and submit flags to verify your solution.

---

## Disclaimer

This repository and its linked resources are created exclusively for educational, cybersecurity training, and authorized threat research purposes. Always ensure you have formal authorization before analyzing telemetry or performing security investigations on enterprise networks.
