# EL_Task3
Perform a Basic Vulnerability Scan on Your PC
# 🔍 Basic Vulnerability Scan on Personal Computer

This repository documents a practical vulnerability assessment performed on a personal computer using Nessus Essentials. It showcases how to identify, analyze, and understand system vulnerabilities from a beginner's perspective.

---

## 🧑‍💻 Project Overview

Vulnerability scanning is a critical part of cybersecurity. It helps identify known weaknesses that could be exploited by attackers. In this project, a full vulnerability scan was run on the local system (localhost) using the free version of **Nessus Essentials** to discover potential threats and understand their severity.

---

## 🎯 Objective

- To perform a basic vulnerability scan on a local machine
- To identify and document critical vulnerabilities
- To suggest basic remediations
- To gain hands-on experience in vulnerability assessment

---

## 🛠️ Tools Used

| Tool | Description |
|------|-------------|
| [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials) | Free vulnerability scanner by Tenable |
| Localhost / 127.0.0.1 | The target system (this PC) |
| Browser | To access Nessus dashboard (`https://santhohex:8834`) |

---

## 🧪 Project Steps

1. Installed Nessus Essentials and activated it using the free license key.
2. Configured a **new scan** targeting the local IP address (127.0.0.1).
3. Executed a **basic network scan**.
4. Waited ~45 minutes for scan completion.
5. Analyzed the vulnerability report and filtered high/critical issues.
6. Researched fixes for each vulnerability.
7. Documented the findings, solutions, and screenshots in a detailed report.

---

## 📋 Key Findings (Summary)

| Vulnerability | Severity | CVE ID | CVSS Score | Fix |
|---------------|----------|--------|-------------|-----|
| SMB Signing not required | High | CVE-2017-0143 | 8.1 | Enforce SMB signing |
| Outdated Firefox Version | Medium | CVE-2023-5381 | 6.5 | Update Firefox |
| SSL/TLS Weak Ciphers Supported | Medium | CVE-2016-2183 | 5.9 | Disable weak SSL protocols |
| ICMP Timestamp Response | Info | - | - | Disable ICMP timestamp replies via firewall |

---

## 🖼️ Screenshots

![img alt](https://github.com/santhosheyzz/Basic-Vulnerability-Scan-Pc/blob/f456ef0377f7917a828a19d3527b60d4c6acf125/Scan%20images/Dashboard.jpg)

![img alt](https://github.com/santhosheyzz/Basic-Vulnerability-Scan-Pc/blob/728f613e02d58cca8ee06bf2ba66f733731ace8a/Scan%20images/Nessus-2.png)

![img alt](https://github.com/santhosheyzz/Basic-Vulnerability-Scan-Pc/blob/728f613e02d58cca8ee06bf2ba66f733731ace8a/Scan%20images/Nessus-1.png)

![imgalt](https://github.com/santhosheyzz/Basic-Vulnerability-Scan-Pc/blob/728f613e02d58cca8ee06bf2ba66f733731ace8a/Scan%20images/Nessus-3.png)

---

## 🎓 Learning Outcomes

- Understood how vulnerability scanning works
- Learned to interpret and prioritize scan results
- Identified real-world system misconfigurations and outdated software
- Prepared for common cybersecurity interview questions

---
