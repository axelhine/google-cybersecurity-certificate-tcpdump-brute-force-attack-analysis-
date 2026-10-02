# google-cybersecurity-certificate-tcpdump-brute-force-attack-analysis-

# Security Incident Report: Brute Force Attack & Malware Redirect

A security incident investigation for a fictional company, completed as part of the Google Cybersecurity Certification course. This project analyzes a brute force attack that led to a website's admin panel being compromised and used to redirect visitors to a malicious site.

## About This Repository

This repo contains the completed incident report:

- [`Security-incident-report-brute-force-attack.pdf`](Security-incident-report-brute-force-attack.pdf) — my completed incident report, including the scenario, network protocol analysis, incident documentation, and remediation recommendations, submitted as part of the Google Cybersecurity Certificate coursework.

## What This Project Covers

- **Scenario** — a former employee brute-forces a website's admin panel, injects malicious code, and redirects customers to a fake site containing malware
- **Network Protocol Identification** — identifying HTTP as the protocol involved in serving the malicious redirect and payload
- **Incident Documentation** — analyzing `tcpdump` packet capture logs to trace the attack, including DNS resolution and HTTP traffic to both the legitimate and malicious domains
- **Remediation Recommendations** — proposing a layered defense against brute force attacks, including strong password policy, two-factor authentication, login attempt monitoring, password rotation, and account lockout thresholds

## Skills Demonstrated

- Packet capture analysis using tcpdump
- HTTP protocol identification and traffic analysis
- Malware and phishing incident investigation
- Brute force attack vector analysis
- Security remediation planning

---
*Completed as part of the Google Cybersecurity Professional Certificate.*
