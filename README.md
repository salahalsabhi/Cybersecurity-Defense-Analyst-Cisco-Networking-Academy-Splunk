# Cybersecurity-Defense-Analyst-Cisco-Networking-Academy-Splunk
Cybersecurity-Learning-Journey


![Cisco Networking Academy](https://img.shields.io/badge/Cisco%20Networking%20Academy-Cybersecurity%20Defense%20Analyst-0A9EDC)
![Splunk](https://img.shields.io/badge/Splunk-Enterprise%20Security-000000)
![Level](https://img.shields.io/badge/Level-Intermediate-orange)
![Learning](https://img.shields.io/badge/Training-30%20Hours-blue)
![Status](https://img.shields.io/badge/Pathway-Completed-success)
![Focus](https://img.shields.io/badge/Focus-SOC%20%7C%20SIEM%20%7C%20Threat%20Hunting-red)

> A professional learning portfolio documenting my completion of the **Cybersecurity Defense Analyst Career Path** from **Cisco Networking Academy**, developed in collaboration with **Splunk**.

---

## 📌 Overview

The **Cybersecurity Defense Analyst Career Path** is an intermediate-level cybersecurity learning pathway focused on developing practical **Security Operations Center (SOC)** and **Splunk Enterprise Security** skills.

The pathway covers the complete lifecycle of defensive security operations, from understanding modern cyber threats and security data to investigating incidents, detecting malicious activity, and performing proactive threat hunting.

The program consists of **8 courses and a pathway exam**, with approximately **30 hours of learning**.

Throughout the pathway, I developed practical knowledge in:

* Security Operations Center (SOC) workflows
* SIEM concepts
* Splunk Enterprise Security
* Splunk Search Processing Language (SPL)
* Security data analysis
* Threat detection
* Incident investigation
* Threat intelligence
* Risk-based alerting
* MITRE ATT&CK
* Threat hunting
* The PEAK Threat Hunting Framework
* Security monitoring and response

---

# 🎯 Learning Objectives

The main objective of this pathway was to develop the foundational skills required for a modern **Cybersecurity Defense Analyst / SOC Analyst**.

The pathway focused on learning how to:

1. Understand the modern cybersecurity threat landscape.
2. Identify common attack techniques and attacker behavior.
3. Understand SOC operations and analyst responsibilities.
4. Search and analyze security data using Splunk.
5. Understand and work with different security data sources.
6. Investigate security incidents using evidence from multiple sources.
7. Use Splunk Enterprise Security for detection and investigation.
8. Perform proactive threat hunting.
9. Apply statistical concepts and behavioral baselines to security investigations.
10. Understand risk-based detection and alerting.

---

# 📚 Career Path Structure

## 1. The Cybersecurity Landscape

**Status:** ✅ Completed

Introduced the fundamental concepts of cybersecurity and the modern threat landscape.

### Topics

* Cybersecurity fundamentals
* Security threats
* Attack surfaces
* Security controls
* Defensive security
* Security operations
* Cybersecurity roles

---

## 2. Understanding Threats and Attacks

**Status:** ✅ Completed

Focused on understanding how attackers operate and how defenders can identify malicious behavior.

### Topics

* Cyber threats
* Malware
* Ransomware
* Phishing
* Attack techniques
* MITRE ATT&CK
* Attacker behavior
* Defensive strategies

---

## 3. Security Operations and the Defense Analyst

**Status:** ✅ Completed

Introduced the role of the Security Operations Center and the responsibilities of a cybersecurity defense analyst.

### Topics

* SOC operations
* Security monitoring
* Alert investigation
* Incident handling
* Analyst workflows
* Escalation
* Security operations processes

---

## 4. Introduction to Splunk

**Status:** ✅ Completed

Introduced Splunk and its role in collecting, searching, analyzing, and visualizing security data.

### Topics

* Splunk fundamentals
* Searching data
* SPL
* Fields
* Indexes
* Sources
* Sourcetypes
* Hosts
* Data models
* Search commands
* Data analysis

### Key SPL Concepts

```text
index
source
sourcetype
host
fields
search
stats
transaction
lookup
tstats
```

---

# 5. Data and Tools for Defense Analysts

**Status:** ✅ Completed

Focused on the security data sources and tools used by SOC analysts.

### Security Data Sources

* Authentication logs
* Endpoint logs
* Firewall logs
* Network traffic
* Proxy logs
* Application logs
* Server logs
* IDS/IPS data
* Cloud security data
* Active Directory data

### Tools Covered

* Splunk Enterprise Security
* Splunk SOAR
* Wireshark
* Tshark
* Tcpdump
* CyberChef
* Splunkbase

### Key Concept

A SOC analyst cannot investigate effectively without the right data.

Different security devices provide different visibility, and analysts must understand:

```text
Data Source
     ↓
Security Events
     ↓
Splunk
     ↓
Analysis
     ↓
Detection
     ↓
Investigation
     ↓
Response
```

---

# 6. The Art of Investigation

**Status:** ✅ Completed

Focused on practical security investigations using Splunk and real-world SOC analyst workflows.

The course included analyst **ride-alongs** demonstrating how security professionals investigate suspicious activity.

### Topics

* Investigation methodology
* Evidence gathering
* Security logs
* HTTP investigation
* Process investigation
* Windows Event Logs
* Threat intelligence
* Data discovery
* Correlation
* Investigation timelines

### Important Investigation Principle

> Sometimes you have to **search for the data before you can search through the data.**

This is a critical SOC skill because an investigation is only as effective as the visibility available to the analyst.

---

# 7. SOC Essentials: Investigating with Splunk

**Status:** ✅ Completed

Focused on using **Splunk Enterprise Security (ES)** to investigate security events and identify suspicious behavior.

### Topics

* SIEM
* Splunk Enterprise Security
* Common Information Model (CIM)
* Data Models
* Accelerated Data Models
* Assets and Identities
* Threat Intelligence
* Notable Events
* Mission Control
* Risk Analysis
* Risk-based Alerting
* Event-based detections
* Finding-based detections

### SIEM Concepts

A SIEM provides centralized security visibility by collecting and analyzing security-relevant data from multiple sources.

Splunk Enterprise Security adds security-focused capabilities on top of Splunk, including:

```text
Security Data
      ↓
CIM Normalization
      ↓
Data Models
      ↓
Detections
      ↓
Risk Analysis
      ↓
Findings
      ↓
Investigation
```

---

# 8. SOC Essentials: Introduction to Threat Hunting

**Status:** ✅ Completed

Introduced proactive threat hunting and methods for identifying activity that may bypass automated detection.

### Topics

* Threat hunting
* Baselines
* Statistical analysis
* Behavioral analysis
* Anomalies
* Outliers
* Interquartile Range (IQR)
* Median
* Standard deviation
* PEAK Threat Hunting Framework
* Proactive security operations

---

# 🔎 Threat Hunting

Threat hunting differs from traditional detection because it is **proactive rather than purely reactive**.

Instead of waiting for an alert:

```text
Traditional Detection

Activity
   ↓
Detection Rule
   ↓
Alert
   ↓
Investigation
```

Threat hunting works more like:

```text
Hypothesis
   ↓
Search
   ↓
Analyze Behavior
   ↓
Find Anomalies
   ↓
Investigate
   ↓
Improve Detection
```

Threat hunting can uncover:

* Detection gaps
* Unknown threats
* Misconfigurations
* Vulnerabilities
* Suspicious behavior
* Previously unidentified attack techniques

---

# 🧠 PEAK Threat Hunting Framework

The pathway introduced the **PEAK Threat Hunting Framework**.

PEAK represents:

```text
P → Prepare
E → Execute
A → Act
K → Knowledge
```

### Prepare

Define the hunt and prepare the necessary research, data, hypotheses, and investigation plan.

### Execute

Perform the actual hunt by searching and analyzing available security data.

The results may confirm the hypothesis, disprove it, or reveal a completely different investigation path.

### Act

Turn the results into useful improvements.

Examples:

* Documentation
* New detections
* Automation
* Improved processes
* Closing data gaps
* Security recommendations

### Knowledge

Knowledge influences every phase of the hunt.

Knowledge can come from:

* Threat intelligence
* Previous investigations
* Previous hunts
* Organizational knowledge
* Security research
* Analyst experience

And importantly, the hunt itself creates new knowledge that can improve future investigations.

---

# 📊 Security Data Analysis

A major part of the pathway was learning how security analysts use data to identify unusual behavior.

### Baselines

A baseline represents what **normal behavior** looks like within an environment.

For example:

```text
Normal login activity
Normal DNS volume
Normal network traffic
Normal process execution
Normal authentication patterns
```

Once a baseline exists, analysts can identify deviations.

```text
Normal Behavior
      ↓
Establish Baseline
      ↓
Observe New Activity
      ↓
Compare
      ↓
Deviation
      ↓
Investigation
```

### Interquartile Range

The **Interquartile Range (IQR)** focuses on the middle 50% of a dataset.

It is useful when establishing behavioral baselines because it reduces the influence of extreme values and helps analysts understand the range of typical activity.

```text
Q1 ───────────── Median ───────────── Q3
        ←──── Middle 50% ────→

IQR = Q3 - Q1
```

---

# ⚠️ Risk-Based Alerting

Another important concept covered was risk-based alerting.

Instead of treating every suspicious event as an individual high-priority alert, Splunk Enterprise Security can accumulate risk associated with an entity.

Example:

```text
Failed Login
    ↓
Risk +20

Suspicious Process
    ↓
Risk +30

Malicious Domain
    ↓
Risk +25

Privilege Activity
    ↓
Risk +40

----------------
Total Risk = 115
----------------

Risk Threshold = 100
        ↓
Finding Generated
```

This allows SOC teams to focus on entities demonstrating a **pattern of risky behavior** rather than investigating every isolated event independently.

---

# 👤 Assets and Identities

Splunk Enterprise Security can enrich security events with information about assets and identities.

### Asset Context

Examples:

* IP address
* Hostname
* Asset owner
* Business unit
* Asset category
* Priority
* Criticality
* Geographic location

### Identity Context

Examples:

* Username
* Email address
* Full name
* Business unit
* Identity category
* Priority
* Contact information

This context helps analysts answer questions such as:

> Who owns this machine?

> Is this a critical server?

> Is this account privileged?

> How important is the affected asset?

> How urgent should this alert be?

---

# 🛡️ Cybersecurity Defense Analyst Pathway Exam

**Status:** ✅ Completed

The final pathway exam tested knowledge across the complete Cybersecurity Defense Analyst learning path.

The exam covered concepts from:

* Cybersecurity fundamentals
* Threats and attacks
* SOC operations
* Splunk
* Security data
* Incident investigation
* Splunk Enterprise Security
* Threat hunting

---

# 🏆 Achievement

I successfully completed the:

**Cybersecurity Defense Analyst Career Path**

Issued through:

**Cisco Networking Academy**

Developed in collaboration with:

**Splunk**

### Achievement Details

```text
Pathway: Cybersecurity Defense Analyst
Provider: Cisco Networking Academy
Collaboration: Splunk
Level: Intermediate
Learning Time: 30 Hours
Courses: 8
Pathway Exam: Completed
Status: Completed
```

This achievement demonstrates foundational knowledge in SOC operations, Splunk Enterprise Security, security investigations, threat detection, and threat hunting.

---

# ⚠️ Certification Note

This repository documents completion of the **Cybersecurity Defense Analyst Career Path and pathway exam**.

It should **not** be interpreted as completion of the separate:

**Splunk Certified Cybersecurity Defense Analyst certification exam**

The certification exam is a separate credential that can be pursued after completing the learning pathway.

---

# 🧰 Skills Developed

### Security Operations

* SOC Operations
* Security Monitoring
* Incident Investigation
* Security Alert Analysis
* Incident Response Concepts

### Splunk

* Splunk Enterprise
* Splunk Enterprise Security
* SPL
* Data Models
* Common Information Model (CIM)
* Risk Analysis
* Risk-Based Alerting
* Detection Engineering Concepts
* Mission Control

### Threat Detection

* MITRE ATT&CK
* IOC Analysis
* Threat Intelligence
* Behavioral Detection
* Anomaly Detection
* Security Data Analysis

### Threat Hunting

* Threat Hunting
* Baseline Analysis
* Statistical Analysis
* IQR
* Outlier Analysis
* PEAK Framework
* Hunt Hypothesis Development

### Security Data

* Endpoint Logs
* Authentication Logs
* Firewall Logs
* Network Traffic
* Proxy Logs
* Application Logs
* Server Logs
* IDS/IPS Data
* Cloud Security Data

---

# 🔧 Tools & Technologies

| Tool / Technology          | Purpose                               |
| -------------------------- | ------------------------------------- |
| Splunk Enterprise          | Security data search and analysis     |
| Splunk Enterprise Security | SIEM, detection and investigation     |
| Splunk SOAR                | Security orchestration and automation |
| SPL                        | Security search and analysis          |
| Splunkbase                 | Apps and add-ons                      |
| Wireshark                  | Network traffic analysis              |
| Tshark                     | Command-line packet analysis          |
| Tcpdump                    | Network packet capture                |
| CyberChef                  | Data decoding and analysis            |
| MITRE ATT&CK               | Threat behavior framework             |

---

# 🧩 SOC Investigation Methodology

One of the most important lessons from this pathway was understanding that effective security investigations require more than simply finding alerts.

A strong investigation combines:

```text
              ┌─────────────────┐
              │ Security Events │
              └────────┬────────┘
                       │
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
    Asset Data    Identity Data   Threat Intel
        │              │              │
        └──────────────┼──────────────┘
                       ↓
                Context & Correlation
                       ↓
                 Risk Assessment
                       ↓
                  Investigation
                       ↓
                Detection / Response
```

This contextual approach allows analysts to move from isolated events toward a complete security story.

---

# 📈 Key Lessons Learned

### 1. Data is fundamental to defense

Without sufficient security telemetry, even the best detection rules cannot provide complete visibility.

### 2. Context matters

An alert involving a normal workstation is different from the same alert involving a domain controller or critical production server.

### 3. Detection is not enough

Automated detections can miss novel or modified attacker behavior.

Threat hunting provides a proactive layer of defense.

### 4. Risk can improve prioritization

Risk-based alerting helps analysts focus on entities demonstrating multiple suspicious behaviors.

### 5. Baselines provide context

Understanding normal behavior makes abnormal behavior easier to identify.

### 6. Threat intelligence improves investigations

Known indicators, TTPs, reports, and community knowledge can accelerate investigations and improve detections.

### 7. Analysts must understand their data

Knowing what data exists, where it comes from, and what it represents is essential for effective SOC investigations.

---

# 🚀 Career Relevance

The skills developed through this pathway are relevant to roles such as:

* SOC Analyst
* Security Operations Analyst
* Cybersecurity Analyst
* Threat Detection Analyst
* Incident Response Analyst
* Threat Hunter
* Junior Detection Engineer

This pathway strengthened my understanding of how modern SOC teams use **SIEM, security telemetry, detection engineering, risk analysis, and threat hunting** to defend organizations.

---

# 📚 Recommended Next Steps

After completing the pathway, the natural progression is to continue developing practical experience with:

* Splunk Enterprise Security
* SPL
* Detection Engineering
* MITRE ATT&CK
* Threat Hunting
* Incident Response
* Security Automation
* Splunk SOAR
* Network Security
* Endpoint Detection and Response
* Practical SOC labs

The next goal is to continue building hands-on experience and eventually pursue the **Splunk Certified Cybersecurity Defense Analyst** certification.

---

# 🔗 Official Resources

* [Cisco Networking Academy](https://www.netacad.com/)
* [Splunk](https://www.splunk.com/)
* [Splunk Enterprise Security](https://www.splunk.com/en_us/products/enterprise-security.html)
* [Splunk Certified Cybersecurity Defense Analyst](https://www.splunk.com/en_us/training/certification-track/splunk-certified-cybersecurity-defense-analyst.html)
* [MITRE ATT&CK](https://attack.mitre.org/)

---

# 📜 Disclaimer

This repository is a personal learning portfolio documenting my progress through the Cybersecurity Defense Analyst Career Path.

The content is intended for educational and professional development purposes.

---

# 👨‍💻 Author

**Salah Al Sabhi**

Cybersecurity Learner | SOC Analyst Path | Splunk | Threat Hunting | Security Operations

---

LinkedIn:[https://www.linkedin.com/feed/update/urn:li:activity:7495098042631667712/]

X: [https://x.com/charisma1385/status/2089317466124038157]

---

## 🏷️ Tags

#CyberSecurity #SOC #SOCAnalyst #Splunk #SplunkES #SIEM #ThreatDetection #ThreatHunting #IncidentResponse #CyberDefense #MITREATTACK #SecurityOperations #SplunkSOAR #BlueTeam #InfoSec #CiscoNetworkingAcademy #CybersecurityDefenseAnalyst #LearningInPublic
