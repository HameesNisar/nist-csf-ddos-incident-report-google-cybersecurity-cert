# Portfolio Project: NIST CSF DDoS Incident Response

## 📘 Overview
This is a cybersecurity incident response report created as part of the Google Cybersecurity Certificate (Course 3). The report applies the **NIST Cybersecurity Framework (CSF)** to analyze and respond to a simulated DDoS attack involving ICMP packet flooding.

---

## 🔍 Scenario Summary
A multimedia company was targeted by a DDoS attack using ICMP packets, resulting in a two-hour internal network outage. The root cause was an unconfigured firewall that allowed unrestricted inbound ICMP traffic.

The response included implementing firewall rules, rate limiting, IP verification, and deploying IDS/IPS solutions.

---

## 🔐 NIST CSF Phases Applied

### 1. **Identify**
- DDoS attack via ICMP flood
- Caused network outage due to firewall misconfiguration
- Internal systems and operations were affected

### 2. **Protect**
- Updated firewall configurations
- Applied IP filtering and ICMP rate limiting
- Created stricter network policies

### 3. **Detect**
- Implemented IDS/IPS systems
- Deployed network monitoring tools to alert on abnormal traffic
- SIEM configuration for real-time visibility

### 4. **Respond**
- Blocked ICMP traffic temporarily
- Shut down non-critical services
- Conducted forensics on firewall and system logs

### 5. **Recover**
- Restored services and verified system health
- Reviewed lessons learned
- Communicated post-incident findings with stakeholders

---

## 📂 Files Included

- `nist-csf-ddos-incident-report.pdf` — Main report following the NIST CSF structure  
- `Applying the NIST CSF(supporting-material).pdf` — *(Optional)* Actionable steps for DDoS response

---

## 🛠️ Skills Demonstrated

- Incident response planning
- Use of the NIST Cybersecurity Framework
- Network monitoring and firewall configuration
- Writing formal security documentation

---

## 🏆 Certification Context
This portfolio submission is part of the **Google Cybersecurity Certificate – Course 3**. It demonstrates the application of real-world cybersecurity frameworks to improve organizational security posture.

