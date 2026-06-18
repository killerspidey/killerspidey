<div align="center">

# Aarohan Shyam

### Cybersecurity Student · Offensive Security & Python Tooling · Building the Stark Network

[![Email](https://img.shields.io/badge/Email-1E90FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aarohanshyam@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aarohanshyam/)
[![Portfolio](https://img.shields.io/badge/Portfolio-00FF8C?style=for-the-badge&logo=netlify&logoColor=black)](https://aarohan-portfolio.netlify.app)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/aarohanshyam)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/public/users/3511359)

</div>

---

## About Me

B.Tech CSE (Cyber Security) student at SRM IST Delhi NCR. I build Python security tooling and AI systems that work in real environments — validated against intentionally vulnerable targets, not just in theory.

Currently building the **Stark Network** — a fully operational 5-agent MCU-inspired AI system with LLM-based intent routing, shared RAG memory (ChromaDB), and a single-command launcher. Agents cover intel, communications, OSINT/recon, and security automation. On the security side, my tools detect ARP spoofing, port scans, DNS tunnelling, and OWASP Top 10 vulnerabilities — tested in a home lab against Metasploitable 2.

Grinding TryHackMe and HackTheBox. Working toward **eJPT**. Open to cybersecurity internship opportunities.

---

## 🚀 Featured Projects

### 🤖 Stark Network — MCU-Inspired 5-Agent AI System
> Python · PyQt6 · Groq LLaMA-3.3-70b · FastMCP/SSE · LiveKit · Whisper · ChromaDB · SQLite · Playwright · PyInstaller

Fully operational 5-agent AI network with a single-command launcher, shared RAG memory, and LLM-based multi-agent intent routing.

| Agent | Role | Stack |
|---|---|---|
| **J.A.R.V.I.S.** | Orchestrator · Voice UI · Tool Dispatch | PyQt6 HUD · Whisper STT · webrtcvad · Groq LLaMA-3.3-70b · SQLite |
| **F.R.I.D.A.Y.** | Intel · News · Weather · Live Markets | FastMCP/SSE · LiveKit · Gemini 2.5 Flash · Sarvam STT |
| **V.E.R.O.N.I.C.A.** | Comms · Gmail · Outlook · Slack · Telegram | OAuth 2.0 · AI Inbox Triage |
| **E.D.I.T.H.** | OSINT · Research · Fact-Check · Domain Intel | Serper · Firecrawl · WHOIS · DNS · Shodan · ChromaDB |
| **U.L.T.R.O.N.** | Security · Automation · Shell Exec · Log Monitor | Playwright · Async Port Scanner · APScheduler · psutil |

- **Shared RAG memory** — ChromaDB + SQLite with sentence-transformer embeddings; memories persist across sessions and are retrieved semantically at query time
- **LLM-based intent routing** via Groq LLaMA-3.3-70b — multi-agent query chaining supported (e.g. *"Research Tesla and email the summary to John"* → EDITH → VERONICA)
- Single `start_network.py` entry point manages all 5 MCP/SSE sub-agents as monitored subprocesses; supports headless mode and per-agent selective launch
- webrtcvad VAD pipeline with energy-threshold fallback — sub-second voice response on 100% free-tier infrastructure

🔗 [View Repository](https://github.com/killerspidey/J.A.R.V.I.S.)

---

### 📡 Network Threat Detection & Traffic Analyzer
> Python · Scapy · Wireshark · Kali Linux

Real-time packet capture and analysis tool detecting active network attacks on a LAN.

- **100% detection rate** on simulated arpspoof and Nmap SYN scan events — validated in VirtualBox lab (Kali + Metasploitable 2) with **<2s alert latency**
- Detects **ARP spoofing**, **SYN/FIN/XMAS/NULL port scans**, **DNS tunnelling**, and **cleartext HTTP credential exposure**
- Output structured as per-session summaries mapped to **SOC Tier 1 triage workflow**
- **40-test unit suite** (no root required) · JSON report generation with CVSS-style severity classification

🔗 [View Repository](https://github.com/killerspidey/network-traffic-analyzer)

---

### 🔎 Web Application Vulnerability Scanner
> Python · Requests · BeautifulSoup

Python-based security scanner targeting OWASP Top 10 vulnerabilities.

- Detects **6 vulnerability classes** — SQLi, XSS, CSRF, insecure headers, open redirects — matching coverage of 4–6 separate manual tools in a single automated scan
- **0 false negatives** on known high-severity injection points against DVWA and OWASP Juice Shop
- CVSS-style severity engine auto-classifies findings into Critical / High / Medium / Low
- Automated parameter fuzzing simulates real penetration testing workflows

🔗 [View Repository](https://github.com/killerspidey/web-application-vulnerability-scanner)

---

## 🛠️ Tools & Skills

**Security Tools**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-214478?style=flat-square&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-005C84?style=flat-square&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**AI & Automation**

![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-CC785C?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-000000?style=flat-square&logoColor=white)
![FastMCP](https://img.shields.io/badge/FastMCP-6C3483?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**Security Concepts**

`OWASP Top 10` `Penetration Testing` `Vulnerability Assessment` `SQL Injection` `XSS` `CSRF` `ARP Spoofing` `DNS Tunnelling` `Port Scanning` `Privilege Escalation` `Threat Modelling` `Secure Coding` `Packet Analysis` `SOC Tier 1` `Log Analysis` `Alert Triage`

---

## 📜 Certifications

| Status | Certification | Issuer | Year |
|---|---|---|---|
| ✅ | Cybersecurity Fundamentals | Infosys Springboard | 2025 |
| ✅ | SQLi, XSS, CSRF, Authentication, Access Control Labs | PortSwigger Web Security Academy | 2025–26 |
| 🟡 | eJPT — Junior Penetration Tester | eLearnSecurity / INE | In Progress |
| 🟡 | SOC Level 1 Path | TryHackMe | In Progress |

---

## 🏆 Achievements

- 🥇 **1st Place** — Ardubotics Workshop, Engineer's Day Celebrations, SRM IST (Sep 2024)
- 🛠️ **B-Inventors Hackathon** — Built EduBuddy peer-support platform in 48 hours (Connect SRM)

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=killerspidey&theme=tokyonight&hide_border=true)](https://github.com/killerspidey)

</div>

---

## 📬 Let's Connect

Open to **cybersecurity internship opportunities** — web application security, penetration testing, SOC / network security, or security engineering roles.

Reach out via [email](mailto:aarohanshyam@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aarohanshyam/) · [Portfolio](https://aarohan-portfolio.netlify.app)

<div align="center">

*"Security is not a product, but a process."*

</div>
