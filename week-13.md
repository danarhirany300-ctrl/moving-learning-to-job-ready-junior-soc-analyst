# Week 13 — Detection Engineering

## 🎯 Goal

Learn how to turn observed attacker behavior into practical SOC detections and improve those detections through testing, tuning, and MITRE ATT&CK mapping.

## 📚 Topics Covered

- Detection engineering
- KQL detection logic
- Behavioral detections
- Brute-force detection
- PowerShell detection
- Detection tuning
- False-positive reduction
- Regression testing
- MITRE ATT&CK mapping
- Detection coverage
- Detection engineering capstone

## 🔎 Practical Work

### 1. Behavioral Detection

Designed detection logic for suspicious activity involving:

```text
Office Application
       ↓
PowerShell
       ↓
Suspicious Command
       ↓
File Creation
       ↓
External Connection


