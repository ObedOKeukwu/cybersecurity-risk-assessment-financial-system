
# Cybersecurity Risk Assessment – Financial System Security Incident

## Overview

This project presents a comprehensive cybersecurity risk assessment for a Linux-based Financial System following a security incident involving a backdoor and command-and-control (C2) access.

The assessment identifies critical vulnerabilities, evaluates business risks, develops an attack tree, prioritizes remediation activities, and provides strategic recommendations to executive leadership.

The project was completed as part of CYBR 3060 – Information Security Risk Management at NAIT.

---

## Scenario

A Linux Web Server hosting a business-critical Financial System was compromised after recommended security controls were not implemented.

A subsequent vulnerability assessment identified multiple critical security weaknesses including:

- SQL Injection
- Cross-Site Scripting (XSS)
- Buffer Overflow
- Backdoor Re-establishment Risk
- Phishing Vulnerabilities
- Credential-Based Account Takeover

The objective was to evaluate the risk landscape and recommend appropriate controls to prevent future incidents.

---

## Asset Assessed

### Linux Web Server (Financial System)

Business-critical asset responsible for:

- Financial transaction processing
- Accounts payable and receivable
- Payroll processing
- Budget reporting
- Financial audit logging

### Business Impact

Compromise of the system could result in:

- Financial fraud
- Data theft
- Regulatory violations
- Operational disruption
- Reputational damage

---

## Risk Assessment Methodology

The assessment uses a semi-qualitative risk analysis approach:

Risk Score = Likelihood × Impact

### Risk Scale

- Likelihood: 1–5
- Impact: 1–5

Severity Categories:

- Low
- Medium
- High
- Critical

Based on:

- NIST SP 800-30
- Industry best practices
- Organizational risk management requirements

---

## Attack Tree Analysis

An attack tree was developed to identify attack paths leading to:

- Financial data theft
- Persistent access
- Backdoor deployment
- Financial fraud
- Credential compromise

### Attack Vectors

#### Web Application Attacks

- SQL Injection
- Cross-Site Scripting
- Buffer Overflow

#### Credential Attacks

- Phishing
- Credential Theft
- Password Reuse

#### Network Exploitation

- Backdoor Deployment
- Command and Control (C2)
- Reconnaissance

#### Insider and Social Engineering Threats

- Phishing Campaigns
- Malicious Insiders
- Privilege Abuse

---

## Key Risks Identified

### RA-001 – SQL Injection

Risk Level: Critical

Potential Impact:

- Database compromise
- Financial fraud
- Data manipulation

---

### RA-002 – Cross-Site Scripting (XSS)

Risk Level: Critical

Potential Impact:

- Session hijacking
- Credential theft
- User impersonation

---

### RA-003 – Buffer Overflow

Risk Level: Critical

Potential Impact:

- Remote code execution
- Root compromise
- System takeover

---

### RA-004 – Backdoor Re-establishment

Risk Level: Critical

Potential Impact:

- Persistent attacker access
- Command-and-control communications
- Data exfiltration

---

### RA-005 – Phishing and Social Engineering

Risk Level: High

Potential Impact:

- Credential theft
- Unauthorized access
- Malware delivery

---

### RA-006 – Credential-Based Account Takeover

Risk Level: Critical

Potential Impact:

- Unauthorized financial transactions
- Data theft
- Privilege escalation

---

## Security Controls Recommended

### Web Application Firewall (WAF)

Recommended Solutions:

- Cloudflare WAF
- AWS WAF
- Palo Alto Prisma Cloud WAF

Benefits:

- SQL Injection protection
- XSS protection
- OWASP Top 10 coverage

---

### Multi-Factor Authentication (MFA)

Recommended Solutions:

- Microsoft Entra ID MFA
- Conditional Access
- FIDO2 Security Keys

Benefits:

- Prevents account takeover
- Reduces phishing impact
- Protects privileged accounts

---

### IDS / IPS Deployment

Recommended Technologies:

- Wazuh HIDS
- Suricata IPS
- Microsoft Sentinel

Benefits:

- File Integrity Monitoring
- Threat Detection
- Faster Incident Response

---

### Access Control Governance

Recommended Technologies:

- Microsoft Entra Governance
- SailPoint IdentityNow

Benefits:

- Quarterly access reviews
- Least privilege enforcement
- Insider threat reduction

---

### Next Generation Firewall (NGFW)

Recommended Solutions:

- Fortinet FortiGate
- Palo Alto NGFW

Benefits:

- Deep Packet Inspection
- Threat Prevention
- C2 Traffic Detection

---

## Security Awareness Program

The project includes a Security Awareness Training strategy focused on reducing phishing susceptibility.

### Components

- Mandatory annual training
- Quarterly refreshers
- Monthly phishing simulations
- Management reporting

Recommended Platform:

- KnowBe4

---

## Skills Demonstrated

- Cybersecurity Risk Assessment
- Risk Analysis and Prioritization
- Attack Tree Modeling
- Threat Modeling
- Security Control Selection
- Risk Treatment Planning
- Vulnerability Assessment Analysis
- Security Awareness Strategy
- Executive Security Reporting
- NIST Risk Management Principles
- Defense-in-Depth Planning

---

## Technologies Referenced

- Linux
- Microsoft Entra ID
- Wazuh
- Suricata
- Microsoft Sentinel
- KnowBe4
- Cloudflare WAF
- Palo Alto Networks
- Fortinet FortiGate
- Cisco Umbrella

---

## Key Frameworks

- NIST SP 800-30
- OWASP Top 10
- Defense in Depth
- Risk Management Lifecycle
- Security Awareness Frameworks

---

## Author

Obed Okeukwu

NAIT Cybersecurity Graduate

Areas of Interest:

- Security Operations (SOC)
- Risk Management
- Governance, Risk & Compliance (GRC)
- Identity and Access Management (IAM)
- Security Architecture
