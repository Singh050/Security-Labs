# 🔐 Cybersecurity Labs Portfolio

This repository showcases a comprehensive collection of cybersecurity labs I have completed. These labs simulate real-world offensive security tasks including reconnaissance, exploitation, vulnerability analysis, social engineering, wireless network cracking, and web application attacks.

---

## 🧪 Lab Summaries

### 🔍 **Lab 1: Getting Acquainted with Kali Linux**
- Used basic Linux commands for system inspection (IP address, uptime, disk usage, kernel version).
- Performed scenario-based tool selection for:
  - Encrypted hard drive analysis
  - Stealthy network scanning
  - Passive monitoring with Wireshark
  - Bluetooth attack monitoring
  - Android APK reverse engineering

**Tools:** `ip`, `uptime`, `df`, `uname`, `nslookup`, `cryptsetup`, `nmap`, `wireshark`, `bettercap`, `apktool`

---

### 🌐 **Lab 2: Network Discovery & Password Cracking**
- Sniffed local network traffic to identify a web server.
- Scraped web content and created a custom wordlist.
- Brute-forced web login credentials using Hydra.
- Performed passive internal reconnaissance after login.

**Tools:** `wget`, `grep`, `awk`, `tcpdump`, `wireshark`, `hydra`, `p0f`, `ifconfig`, `arp-scan`

---

### 🛡️ **Lab 3: Service Discovery & Vulnerability Assessment**
- Scanned a local network for live hosts and open services.
- Performed OS and service fingerprinting.
- Conducted vulnerability scans using Nikto, OpenVAS, and Nmap scripts.
- Researched CVEs and documented risks.

**Tools:** `nmap`, `masscan`, `nikto`, `openvas`, `metasploit`, `cve.org`

---

### 🎣 **Lab 4: Social Engineering (Phishing Simulation)**
- Crafted a phishing email using Thunderbird with embedded base64 image.
- Set up a credential harvester using Social-Engineer Toolkit (SET).
- Cloned a legitimate login page and captured credentials via a fake page.

**Tools:** `thunderbird`, `base64`, `setoolkit`

---

### 📶 **Lab 5: Wi-Fi Security & WPA Cracking**
- Captured WPA 4-way handshake using Wireshark.
- Analyzed the handshake process and extracted key details.
- Performed a brute-force WPA password attack using Aircrack-ng and Crunch.

**Tools:** `wireshark`, `aircrack-ng`, `crunch`, `eapol` filters

---

### 💻 **Lab 6: Web Exploitation – Stored XSS Attacks**
- Executed stored XSS attacks by injecting JavaScript into form fields.
- Bypassed `htmlspecialchars()` sanitization using attribute injection.
- Delivered encoded payloads using base64 iframes for stealthy script execution.

**Tools:** Browser DevTools, `base64`, JavaScript, HTML injection techniques

---

## 🎯 Skills Demonstrated
- Network and service enumeration
- Vulnerability scanning and assessment
- Exploitation using Metasploit
- Password cracking (online & offline)
- Social engineering (phishing simulation)
- Web application testing (XSS)
- Wireless security testing (WPA cracking)
- Post-exploitation data extraction

---

## 🧠 Aligned Certifications
- [x] eLearnSecurity Junior Penetration Tester (eJPT)
- [x] CompTIA PenTest+
- [x] Offensive Security Certified Professional (OSCP) – foundational overlap
- [x] GIAC Certified Incident Handler (GCIH) – partial overlap (traffic analysis, forensics)
- [x] Offensive Security Wireless Professional (OSWP) – Lab 5 specific

---

## 📂 Repository Structure
```
labs/
├── Lab1_Kali_Intro/
├── Lab2_Network_Discovery/
├── Lab3_Vulnerability_Assessment/
├── Lab4_Phishing/
├── Lab5_WiFi_Cracking/
├── Lab6_Web_XSS/
```

Each directory contains:
- Lab report (.pdf)
- Relevant screenshots (optional)

---

## 📫 Contact
For inquiries or collaboration:
**Name:** Barjinder Singh  
**Email:** [barjindersingh1104@gmail.com]  
**LinkedIn:** [https://www.linkedin.com/in/barjinder-singh-88413b13b/] 

---

> ⭐ *This lab repository highlights practical cybersecurity knowledge applied across various domains. Each lab demonstrates real-world offensive and defensive security concepts in a safe, ethical, and academic environment.*
