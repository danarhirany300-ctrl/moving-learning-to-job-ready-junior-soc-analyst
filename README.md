# Week 1 – SIEM Fundamentals & Microsoft Sentinel

## Overview

This week focused on understanding the fundamentals of Security Information and Event Management (SIEM) and how Microsoft Sentinel supports Security Operations Center (SOC) analysts during security monitoring and investigations.

## Topics Covered

- Introduction to SIEM
- Microsoft Sentinel Fundamentals
- Alert vs Incident
- Analytics Rules
- Windows Event Logs
- Why Organizations Collect Logs
- Basic Investigation Workflow

## Skills Gained

- Understanding SIEM architecture
- Reading security alerts
- Understanding incident creation
- Basic SOC investigation workflow
- Windows logging fundamentals

## Outcome

By the end of this week, I understood how Microsoft Sentinel collects logs, generates alerts, groups related alerts into incidents, and supports analysts during investigations.



# Week 2 – Kusto Query Language (KQL)

## Overview

This week focused on learning Kusto Query Language (KQL), the primary language used to search, filter, and investigate security data within Microsoft Sentinel.

## Topics Covered

- KQL Basics
- Filtering Data
- Searching Logs
- Operators
- Time Filtering
- Aggregation
- Hunting Queries

## Skills Gained

- Writing KQL queries
- Investigating security events
- Searching Windows logs
- Performing threat hunting
- Filtering large datasets

## Outcome

By the end of this week, I was able to write practical KQL queries to investigate security events and perform basic threat hunting.




# Week 3 – Microsoft Defender XDR

## Overview

This week focused on Microsoft Defender XDR and endpoint investigation techniques used by SOC analysts.

## Topics Covered

- Microsoft Defender XDR
- Devices
- Users
- Alerts
- Evidence
- Investigation Timeline
- Endpoint Investigation

## Skills Gained

- Endpoint investigation
- Alert analysis
- Timeline analysis
- Device investigation
- User activity review

## Outcome

By the end of this week, I understood how to investigate endpoint alerts using Microsoft Defender XDR.




# Week 4 – Threat Hunting

## Overview

This week focused on proactive threat hunting using Microsoft Sentinel and Defender XDR.

## Topics Covered

- Threat Hunting
- Hunting Hypotheses
- IOC Hunting
- KQL Hunting
- Process Investigation
- Network Investigation

## Skills Gained

- Threat hunting methodology
- IOC analysis
- Process investigation
- Network investigation
- Log correlation

## Outcome

By the end of this week, I was able to perform structured threat hunting using multiple data sources.





# Week 5 – Splunk Fundamentals

## Overview

This week focused on using Splunk for log analysis and SOC investigations.

## Topics Covered

- Splunk Interface
- SPL Queries
- Search Commands
- Dashboards
- Investigation Workflow

## Skills Gained

- SPL query writing
- Log analysis
- Searching security events
- Dashboard interpretation

## Outcome

By the end of this week, I understood how Splunk is used to investigate security events in enterprise environments.




# Week 6 – Elastic Security

## Overview

This week focused on Elastic Security and Kibana for threat detection and investigation.

## Topics Covered

- Elastic Security
- Kibana
- Discover
- Dashboards
- Detection Rules
- Timeline Investigation

## Skills Gained

- Kibana searches
- Elastic investigations
- Dashboard analysis
- Timeline analysis

## Outcome

By the end of this week, I understood how Elastic Security supports SOC investigations.



# Week 7 – SOC Investigations (LetsDefend)

## Overview

This week focused on practical SOC investigations using realistic security incidents.

## Topics Covered

- PowerShell Investigation
- RDP Brute Force
- Phishing Investigation
- Malware Investigation
- Investigation Documentation

## Skills Gained

- Incident investigation
- Timeline creation
- IOC identification
- Analyst documentation
- Decision making

## Outcome

By the end of this week, I completed multiple practical SOC investigations using realistic attack scenarios.





# Week 8 – Incident Response & SOC Operations

## Overview

This week focused on incident response processes and core SOC operational concepts.

## Topics Covered

- Incident Response Lifecycle
- Alert Triage
- True Positive vs False Positive
- IOC vs IOA
- MITRE ATT&CK
- Professional Analyst Notes

## Skills Gained

- Incident handling
- Alert prioritization
- Evidence collection
- MITRE ATT&CK mapping
- Professional documentation

## Outcome

By the end of this week, I understood how SOC analysts investigate, prioritize, document, and respond to security incidents.



# Week 9 – Malware & Threat Intelligence

## Overview

This week focused on malware analysis fundamentals and the use of threat intelligence during SOC investigations.

## Topics Covered

- Malware Types
- Ransomware
- Command & Control (C2)
- Threat Intelligence
- VirusTotal
- URLScan
- Hybrid Analysis

## Skills Gained

- Malware identification
- IOC analysis
- Threat intelligence research
- Sandbox analysis
- Malware investigation workflow

## Outcome

By the end of this week, I understood how SOC analysts investigate malware, analyze indicators, use threat intelligence, and safely examine suspicious files.



# Week 10 — Advanced SOC Investigations

## 🎯 Goal

Develop the ability to investigate complete security incidents from initial alert through analysis, containment, and documentation.

## 📚 Topics Covered

- End-to-end incident investigation
- Phishing investigations
- Credential compromise
- Authentication log analysis
- Endpoint investigation
- Threat intelligence
- MITRE ATT&CK mapping
- Incident classification
- Containment recommendations
- Professional analyst notes

## 🔎 Practical Investigations

### 1. End-to-End Incident Investigation

Practiced investigating a security alert from initial triage through evidence collection, analysis, classification, and recommended response actions.

### 2. Phishing Investigation

Investigated a simulated phishing incident involving:

- Suspicious sender domain
- Malicious URL
- Fake login page
- Credential submission
- Suspicious authentication activity

Determined that the incident represented likely credential compromise.

### 3. Authentication Investigation

Analyzed authentication logs to identify:

- Repeated failed logins
- Successful authentication
- Unfamiliar locations
- Unknown devices
- Potential account compromise

### 4. Endpoint Investigation

Reviewed endpoint activity following a phishing event and investigated browser activity, credential submission, and subsequent authentication events.

## 🧠 Investigation Workflow

```text
Alert
  ↓
Triage
  ↓
Collect Evidence
  ↓
Investigate Endpoint
  ↓
Review Authentication Logs
  ↓
Threat Intelligence
  ↓
Determine Impact
  ↓
MITRE ATT&CK Mapping
  ↓
Classify Incident
  ↓
Contain / Escalate
  ↓
Document



# Week 11 — Advanced SOC Investigation

## 🎯 Goal

Develop stronger investigation skills by analyzing suspicious activity across multiple security data sources and building a complete incident timeline.

## 📚 Topics Covered

- Advanced alert triage
- Multi-source log correlation
- Authentication investigation
- Endpoint investigation
- PowerShell analysis
- Network activity analysis
- IOC investigation
- Incident timelines
- Scope assessment
- Evidence-based classification

## 🔎 Practical Investigations

### 1. Authentication Investigation

Analyzed authentication activity involving:

- Multiple failed logins
- Successful authentication
- Unusual source IPs
- Unknown devices
- Suspicious login patterns

Focused on determining whether the activity represented legitimate user behavior or possible account compromise.

### 2. PowerShell Investigation

Investigated suspicious PowerShell activity by reviewing:

- Parent process
- Command-line activity
- User
- Host
- File creation
- Network connections

Used the surrounding context to determine whether the PowerShell activity was suspicious.

### 3. Multi-Source Correlation

Correlated evidence from different security sources:

```text
Authentication Logs
        +
Endpoint Telemetry
        +
Network Activity
        +
Threat Intelligence
        ↓
Incident Timeline


# Week 12 — Advanced Incident Response

## 🎯 Goal

Develop the ability to investigate multi-stage incidents, determine the scope of a compromise, and recommend appropriate containment and response actions.

## 📚 Topics Covered

- Multi-stage incident investigation
- Incident response workflow
- Attack-chain analysis
- Endpoint compromise
- Account compromise
- Lateral movement
- Persistence
- IOC investigation
- Scope determination
- Containment
- Evidence preservation
- Incident documentation

## 🔎 Practical Investigations

### 1. Multi-Stage Incident Investigation

Analyzed a simulated attack chain involving:

```text
Initial Access
      ↓
Execution
      ↓
Credential Activity
      ↓
Lateral Movement
      ↓
Persistence
      ↓
Collection



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




# Week 14 — Professional SOC Skills & Career Preparation

## 🎯 Goal

Complete the SOC training program by developing professional investigation, threat-hunting, reporting, portfolio, resume, and interview skills.

## 📚 Topics Covered

- Professional SOC investigation
- Incident reporting
- IOC investigation
- Threat hunting
- Threat-hunting case studies
- SOC portfolio development
- Resume preparation
- LinkedIn preparation
- Final SOC assessment
- SOC interview preparation

## 🔎 Practical Work

### 1. Professional SOC Investigation

Practiced documenting investigations using:

- Incident summaries
- Timelines
- Evidence
- IOCs
- Analysis
- Impact assessment
- Classification
- Recommended actions
- Final conclusions

Focused on using evidence-based language and separating confirmed facts from assumptions.

### 2. Complete Incident Report

Built a professional incident-report structure:

```text
Incident Summary
       ↓
Incident Details
       ↓
Timeline
       ↓
Evidence
       ↓
IOCs
       ↓
Analysis
       ↓
Impact Assessment
       ↓
Classification
       ↓
Recommendations
       ↓
Final Conclusion

