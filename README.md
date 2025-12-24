# Splunk SIEM Lab – SSH Brute Force Detection

## 📌 Overview
This project demonstrates a hands-on Splunk SIEM deployment on Linux, focusing on authentication log ingestion, failed SSH login detection, and alerting for potential brute-force attacks.

The lab simulates a SOC-style workflow including log onboarding, field extraction, detection engineering, and alert configuration.

---

## 🧱 Lab Environment
- **Platform:** Oracle VirtualBox
- **OS:** REMnux (Linux)
- **SIEM:** Splunk Enterprise 10.x
- **Log Source:** `/var/log/auth.log`
- **Access Method:** SSH (local simulation)

---

## ⚙️ Splunk Setup

### Splunk Web Interface
Splunk Enterprise was installed and accessed via the web interface.

![Splunk Home](screenshots/splunk_home.png)

---

### Log Ingestion
The Linux authentication log was monitored and indexed into Splunk.
