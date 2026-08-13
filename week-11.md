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
