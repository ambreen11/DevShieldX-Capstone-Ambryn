# DevShieldX SOC Capstone Project

## 🔐 Project Title
Port Scanning, SSH Exploitation & Data Exfiltration (Windows → Kali)

---

## 📌 Project Overview
This project simulates a real-world SOC investigation involving reconnaissance, unauthorized access, and data exfiltration.

The attacker performed port scanning on a target Windows machine, identified an open SSH service, gained access, and transferred sensitive data (`secret.txt`) to a Kali Linux machine.

---

## 🧪 Investigation Methodology

1. Network Reconnaissance
   - Performed port scanning using Nmap
   - Identified open ports and services

2. Service Enumeration
   - Detected SSH service running on target

3. Unauthorized Access
   - SSH login attempt to target system

4. Data Exfiltration
   - Transferred `secret.txt` from Windows to Kali

5. Log Analysis
   - Reviewed logs to detect suspicious activity

---

## 🛠️ Tools Used

- Nmap (Port Scanning)
- SSH
- Kali Linux
- Windows Machine
- Wireshark (optional)
- wazuh 

---

## 🚨 Key Findings

- Open SSH port exposed attack surface
- Weak/misconfigured access controls enabled login
- Sensitive file % secret.txt % was exfiltrated
- Lack of monitoring allowed attack progression

---

## 📂 Indicators of Compromise (IOCs)

- Suspicious IP address (attacker machine)
- Unusual SSH login attempts
- File transfer activity
- Port scanning behavior

---

## 📸 Evidence

Screenshots and logs are available in:
- `/Screenshots`
- `/Evidence`

---

## 📚 Lessons Learned

- Always secure open ports
- Use strong authentication (disable password login)
- Monitor SSH activity
- Implement intrusion detection systems

---
