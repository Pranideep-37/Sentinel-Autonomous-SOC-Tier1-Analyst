# 🛡️ Sentinel – Autonomous SOC Tier-1 Analyst & Incident Triage Agent

> **Built using NitroStack MCP Framework**

Sentinel is an AI-powered **Tier-1 Security Operations Center (SOC) Analyst** designed to automate the initial stages of security incident investigation. It assists SOC analysts by performing evidence-based alert triage, mapping attacks to MITRE ATT&CK, correlating alerts, parsing logs, and generating structured incident reports through a natural language interface.

---

## 👥 Team

**Team Name:** LOOP_h()LeS

---

# 🚀 Problem Statement

Modern Security Operations Centers (SOCs) receive hundreds of security alerts every day. Analysts spend significant time manually triaging repetitive alerts, leading to:

- Alert fatigue
- Increased Mean Time to Respond (MTTR)
- Delayed incident investigation
- Missed critical threats

Sentinel addresses these challenges by automating Tier-1 incident triage while ensuring investigations remain evidence-based.

---

# 💡 Solution

Sentinel acts as an autonomous Tier-1 SOC analyst capable of:

- Performing security alert triage
- Mapping observed behaviour to MITRE ATT&CK
- Parsing Windows & Sysmon logs
- Correlating multiple alerts
- Assessing IP addresses
- Assessing file hashes
- Generating SOC incident reports
- Providing incident response recommendations

---

# 🛠 Features

## 🔹 Evidence-Based Alert Triage
Automatically analyses incoming alerts and provides:

- Severity
- Confidence
- Observed indicators
- Analyst assessment
- Recommended next steps

---

## 🔹 MITRE ATT&CK Mapping

Maps suspicious activity to:

- MITRE Technique
- ATT&CK Tactic
- Confidence level

---

## 🔹 Threat Intelligence

Supports:

- IP Reputation Assessment
- File Hash Assessment

---

## 🔹 Security Log Parsing

Extracts suspicious indicators from:

- Windows Event Logs
- Microsoft Sysmon Logs
- PowerShell Events
- Command Execution
- Authentication Logs

---

## 🔹 Alert Correlation

Correlates alerts using:

- Source IP
- Username
- Hostname

---

## 🔹 Incident Report Generation

Produces structured SOC reports including:

- Incident Summary
- Assessment
- Severity
- Priority
- Recommended Actions

---

## 🔹 Response Recommendation Engine

Suggests containment and investigation actions based on incident severity.

---

# 📚 Cybersecurity Knowledge Resources

Sentinel integrates real cybersecurity reference material including:

- MITRE ATT&CK Framework
- Windows Security Event IDs
- Microsoft Sysmon Event IDs
- NIST Incident Response Lifecycle
- OWASP Top 10 (2021)
- Lockheed Martin Cyber Kill Chain
- Tier-1 SOC Investigation Checklist

These resources help ensure investigations remain structured and evidence-driven.

---

# 🎯 MCP Components

### Tools

- Alert Triage
- MITRE Mapper
- IP Assessment
- Hash Assessment
- Log Parser
- Alert Correlation
- Incident Report Generator
- Response Recommendation

### Resources

- MITRE ATT&CK
- Windows Event IDs
- Sysmon Events
- NIST IR Lifecycle
- OWASP Top 10
- Cyber Kill Chain
- SOC Investigation Checklist

### Prompts

Specialised SOC investigation prompts designed for structured incident analysis.

---

# 🖥 Interactive SOC Dashboard

The project includes a custom dashboard that visualises:

- Threat Severity
- Confidence
- Alert Type
- Source & Destination IP
- MITRE Mapping
- Incident Summary
- Recommendations
- Investigation Status

---

# 🧪 Testing

The project was validated using **10 comprehensive test cases** covering:

- Ransomware Detection
- PowerShell Abuse
- Credential Attacks
- Windows Authentication Events
- Sysmon Events
- Malware Indicators
- Suspicious Command Execution
- Threat Intelligence
- Alert Correlation
- Security Log Parsing

---

# 🤖 Deployment

The solution is deployed using:

- NitroStack MCP Framework
- NitroChat
- ChatGPT MCP Plugin Integration

The ChatGPT MCP Plugin enables natural language investigations while leveraging Sentinel's specialised SOC tools and cybersecurity resources.

---

# 🏗 Technology Stack

- TypeScript
- NitroStack MCP Framework
- Nitro Widgets
- React
- Next.js
- ChatGPT MCP Plugin

---

# 📂 Project Structure

```
src/
│
├── modules/
│   └── calculator/
│       ├── soc.module.ts
│       ├── soc.tools.ts
│       ├── soc.prompts.ts
│       └── soc.resources.ts
│
├── widgets/
│   └── soc-dashboard/
│
├── health/
│
└── app.module.ts
```

---

# 🎥 Demonstration

The project demonstrates:

- Automated Tier-1 Alert Triage
- Interactive SOC Dashboard
- NitroChat Integration
- ChatGPT MCP Plugin Integration
- Evidence-Based Incident Investigation

---

# 🔮 Future Scope

Potential future enhancements include:

- Live SIEM Integration
- VirusTotal API Integration
- AbuseIPDB Integration
- MISP Integration
- Real-time Threat Intelligence
- Multi-Agent SOC Workflows
- Automated IOC Enrichment
- Incident Timeline Reconstruction

---

# 📌 Key Highlights

✅ Autonomous Tier-1 SOC Analyst

✅ Evidence-Based Investigation

✅ Interactive SOC Dashboard

✅ Real Cybersecurity Reference Resources

✅ Modular MCP Tools

✅ Natural Language Investigation

✅ ChatGPT MCP Integration

---

## Thank You

Built with ❤️ by **Team LOOP_h()LeS**
