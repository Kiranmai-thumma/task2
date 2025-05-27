# 🛡️ Phishing Email Analysis Report

This project contains a detailed analysis of a suspicious phishing email using real-world threat detection and email header inspection techniques.

## 📌 Objective

To demonstrate the real-world application of email forensics and phishing detection techniques used in SOC environments.

## 📄 Report Overview

The report provides a step-by-step breakdown of how to investigate and validate a potentially spoofed or malicious email. Each section includes visuals, domain verification, and forensic-level commentary.

### 🔍 Contents

- **Received Email Analysis** – Evaluates visual content and suspicious indicators in the received email.
- **Email Header Analysis** – Explains key metadata fields and their purpose in verifying sender authenticity.
- **SPF/DKIM Record Evaluation** – Inspects domain authentication records and their alignment.
- **ARC & Return-Path Inspection** – Assesses the transport and relay headers for red flags.
- **Received Chain Validation** – Maps the path the email took through servers.
- **MX Record Verification** – Confirms whether the sending IP matches the domain’s legitimate mail servers.
- **Remediation Steps** – Practical recommendations for preventing and detecting similar threats.

## 🧠 Tools Used

- [MXToolbox](https://mxtoolbox.com/) – Header and DNS inspection
- Mozilla Thunderbird – For accessing original email content
- WHOIS & MX Record Lookup – Verifying sender infrastructur

