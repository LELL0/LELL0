<div align="center">

# Elia El Khoury

### Cybersecurity Engineer · SOAR & AI Automation · Attack Surface Management

*"Comments Lie Sometimes, Code Never Does."*

[![Portfolio](https://img.shields.io/badge/Portfolio-eliaelkhoury.vercel.app-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white)](https://eliaelkhoury.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-elia--elkhoury-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elia-elkhoury/)
[![Email](https://img.shields.io/badge/Email-eliaelkhoury.eng@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eliaelkhoury.eng@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-LELLO-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/LELLO)

**Shipping now:**
[![Calcendar](https://img.shields.io/badge/Calcendar-calcendar.com-22C55E?style=flat-square&logo=googlecalendar&logoColor=white)](https://calcendar.com)
[![EncChat](https://img.shields.io/badge/EncChat-encchat.xyz-6D28D9?style=flat-square&logo=signal&logoColor=white)](https://encchat.xyz/download)

</div>

---

## 👋 About Me

Cybersecurity and Automation Engineer with **5+ years of experience**, based in Lebanon and working remotely for enterprise clients in the UAE. I specialize in building security automation that scales, from incident response playbooks to AI-augmented SOC workflows.

My work sits at the intersection of **security engineering** and **modern AI tooling**. I was an early adopter of agentic AI within SOC environments, integrating LLMs for autonomous alert triage and threat intelligence enrichment before it became mainstream.

- 🔒 Specialized in **Cortex XSOAR**, **Agentic AI**, and **Attack Surface Management**
- 📉 Reduced **MTTR by 40%** and **analyst workload by 35%**
- 🧰 Off-hours I ship full-stack and IoT side projects: Next.js, Flutter, Express/MongoDB, Arduino
- 🎓 B.Eng. in Computer and Telecommunications Engineering from Antonine University

---

## 💼 Experience

### 🛡️ Cybersecurity Engineer at Coordinates, Dubai, UAE *(Remote)* `Sep 2022 – Present`

- Integrated **agentic AI models** into the SOC for threat detection, alert triage, and incident response, cutting analyst intervention by **~30%**
- Developed **50+ Cortex XSOAR playbooks** and **15+ Python scripts** for SIEM, EDR, and WAF workflows, bringing triage from hours to minutes
- Built the **ASM platform from scratch** in Python with a distributed sensor-controller architecture and MongoDB backend, tracking **500+ external assets** across **3+ client environments**
- Set up **REST integrations** with third-party security tools to unify log ingestion, detection enrichment, and remediation across client environments
- Created **20+ offensive simulations** with automated scheduling for continuous external exposure visibility
- Built an **end-to-end phishing check flow** inspecting inbound email for malicious attachments, phishing indicators, unsafe redirects, squishing, homoglyphs, impersonation, and spoofing
- Designed a **passive asset discovery workflow** comparing expected vs. observed coverage to surface blindspots via SIEM queries and EDR telemetry
- Containerized the sensor stack with **Docker**, cutting deployment time from hours to minutes

### 📡 IoT Engineer at SAWA Group, Baalbek, Lebanon `Jan 2022 – Sep 2022`

- Built an **IoT flowmeter system** using Arduino Mega and NodeMCU, paired with a **Flutter mobile app** for real-time telemetry and remote monitoring
- Added a NodeMCU-hosted fallback web interface for manual control when the mobile app is unavailable

### 🔍 Cybersecurity Intern at Po.Tech Consulting, Mansourieh, Lebanon `Oct 2021 – Jan 2022`

- Ran **15+ OSINT investigations** and wrote Python scripts to automate passive reconnaissance, cutting manual research time by **50%**
- Contributed to the internal OSINT framework **Darkivor**

---

## 🚀 Featured Work

Professional and client work, built in private or closed-source environments.

| Project | Description | Stack |
|---------|-------------|-------|
| **🌐 Attack Surface Management Platform** | Enterprise ASM with remote controller, central server, and distributed sensor network over 500+ monitored assets. Automated reporting cut generation time by 60% | Python · Docker · MongoDB |
| **⚡ XSOAR Automations & Integrations** | 50+ playbooks and 15+ custom automations wiring SIEM, EDR, and WAF into one response surface | Cortex XSOAR · Python · REST |
| **🎣 Phishing Check Flow** | End-to-end email inspection for malicious attachments, redirect chains, QR abuse (squishing), homoglyphs, impersonation, and spoofing | SOAR · Python · Email Security |
| **🔎 Passive Asset Discovery** | Expected vs. observed coverage reconciliation to surface blindspots and missing log sources without noisy active scanning | SIEM · EDR · Python |
| **🎬 AI Script to Animation Platform** | Zaka.ai collaboration: parses a text prompt into logical scenes, then generates images and 5s clips per scene | Python · Stable Video Diffusion |
| **🗓️ [Calcendar](https://calcendar.com)** 🟢 *Live* | Multi-tenant client management, scheduling, and billing for practitioners. Recurring bookings with live conflict detection, per-session ledger, admin approval flow. One backend, three surfaces: marketing site, [web app](https://calcendar.com/app), Android APK | Express · MongoDB · Flutter · Docker |
| **🔐 [EncChat](https://encchat.xyz/download)** 🟢 *Live* | End-to-end encrypted messaging: RSA key exchange with AES session keys, DMs and groups, voice calls, view-once messages, read receipts and presence over STOMP WebSocket. Android APK, plus web and Linux builds | Spring Boot · Flutter · WebSocket · Docker |
| **💧 Water Truck Flow Meter (IoT)** | Embedded volume metering from truck to tank with live field readings and a fallback web UI | Arduino Mega · NodeMCU · Flutter |

---

## 📂 Open Source

Public repositories you can read, clone, and run.

| Repository | What it does | Language |
|------------|--------------|----------|
| [**find-setup-bottleneck**](https://github.com/LELL0/find-setup-bottleneck) | Windows bottleneck sampler: CPU/RAM/disk/net counters plus SMART health, wear, temps, RAM XMP, and GPU load, then flags the likely cause of lag | Python |
| [**EChat**](https://github.com/LELL0/EChat) | Original desktop build of the E2E messenger: hybrid RSA + AES, 50+ concurrent users, no plaintext at rest or in transit. Succeeded by [EncChat](https://encchat.xyz/download) | Java |
| [**Face-Mask-Detector**](https://github.com/LELL0/Face-Mask-Detector) | Raspberry Pi CV access control: 90%+ detection accuracy, 100+ daily entries, drives door lock, buzzer, and sanitizer | Python · OpenCV |
| [**Lora-Tracking-System**](https://github.com/LELL0/Lora-Tracking-System) | Two TTGO LoRa32 boards plus GPS relaying coordinates between separate locations | C |
| [**Web-Scraping**](https://github.com/LELL0/Web-Scraping) | Harvests social media links from target pages | Python |
| [**TeleIndexing**](https://github.com/LELL0/TeleIndexing) | Pulls the last N messages from a chosen Telegram channel | Python |
| [**fruit-detection-flask**](https://github.com/LELL0/fruit-detection-flask) | Image classification served behind a Flask app | Python |
| [**Pinger**](https://github.com/LELL0/Pinger) | Connection quality watchdog to run during online calls | Python |
| [**Python3**](https://github.com/LELL0/Python3) | Assorted small utility scripts | Python |

---

## 🛠️ Tech Stack

<div align="center">

#### Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

#### AI & Automation
![Agentic AI](https://img.shields.io/badge/Agentic_AI-412991?style=flat-square&logo=openai&logoColor=white)
![LLM Integration](https://img.shields.io/badge/LLM_Integration-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Stable Video Diffusion](https://img.shields.io/badge/Stable_Video_Diffusion-000000?style=flat-square&logo=stability-ai&logoColor=white)
![Computer Vision](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

#### Security Operations
![Cortex XSOAR](https://img.shields.io/badge/Cortex_XSOAR-FF6D36?style=flat-square&logo=paloaltonetworks&logoColor=white)
![Incident Response](https://img.shields.io/badge/Incident_Response-DC143C?style=flat-square&logo=hackaday&logoColor=white)
![ASM](https://img.shields.io/badge/Attack_Surface_Mgmt-2C2D72?style=flat-square&logo=hackthebox&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT-333333?style=flat-square&logo=osano&logoColor=white)
![Offensive Simulation](https://img.shields.io/badge/Offensive_Sim-CC0000?style=flat-square&logo=kalilinux&logoColor=white)
![Phishing Analysis](https://img.shields.io/badge/Phishing_Analysis-FF6600?style=flat-square&logo=protonmail&logoColor=white)
![SIEM](https://img.shields.io/badge/SIEM-000000?style=flat-square&logo=elastic&logoColor=white)
![EDR](https://img.shields.io/badge/EDR_(CrowdStrike/Defender)-005571?style=flat-square&logo=crowdstrike&logoColor=white)
![WAF](https://img.shields.io/badge/WAF-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

#### Web & Mobile
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

#### Infrastructure & Hardware
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![NodeMCU](https://img.shields.io/badge/NodeMCU-E7352C?style=flat-square&logo=espressif&logoColor=white)

</div>

---

## 📊 GitHub

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=LELL0&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=LELL0&layout=compact&hide_border=true&theme=tokyonight&langs_count=8)

</div>

---

## 📜 Certifications

| Certification | Issuer | Date |
|--------------|--------|------|
| Artificial Intelligence Program | Zaka AI | Dec 2025 |
| Google Cybersecurity Specialization | Google | Feb 2024 |
| Flutter Development Bootcamp with Dart | The App Brewery | Oct 2023 |
| JavaScript Algorithms and Data Structures | freeCodeCamp | Mar 2023 |
| Supervised Machine Learning: Regression and Classification | Coursera / Stanford | May 2022 |
| Scientific Computing with Python | freeCodeCamp | May 2022 |
| Practical Ethical Hacking | TCM Security | Sep 2021 |
| CCNA: Switching, Routing and Wireless Essentials | Cisco | Feb 2021 |
| CCNA: Enterprise Networking, Security and Automation | Cisco | Jul 2020 |
| Linux Essentials | Cisco | Jul 2020 |
| CCNA: Introduction to Networks | Cisco | Jun 2020 |

---

## 🌐 Languages

🇱🇧 Arabic *(Native)* · 🇬🇧 English *(Fluent)* · 🇫🇷 French *(Fluent)*

---

<div align="center">

### 📫 Let's Connect

I'm open to new opportunities, collaborations, and consulting engagements.
Whether you're looking to level up your SOC, build security automation, or integrate AI into your security workflows, let's talk.

[![Email Me](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eliaelkhoury.eng@gmail.com)
[![View Portfolio](https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://eliaelkhoury.vercel.app/)
[![Download CV](https://img.shields.io/badge/Download_CV-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://eliaelkhoury.vercel.app/Elia-El-Khoury-CV.pdf)

</div>
