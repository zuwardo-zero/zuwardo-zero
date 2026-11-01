<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,60:0891b2,100:22c55e&height=190&section=header&text=m1h&fontSize=62&fontColor=ffffff&animation=fadeIn&desc=%24%20whoami%20%C2%B7%20Security%20Researcher%20%C2%B7%20Penetration%20Tester%20%C2%B7%20Purple%20Team&descSize=17&descAlignY=72" width="100%" />

<h3 align="center">🌐 Find Me Online</h3>

<p align="center">
  <a href="https://m1h.hashnode.dev/"><img src="https://img.shields.io/badge/Blog-Cyber_Range-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" alt="Blog" /></a>
  <a href="https://bugcrowd.com/h/m1h"><img src="https://img.shields.io/badge/Bugcrowd-m1h-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white" alt="Bugcrowd" /></a>
  <a href="https://hackenproof.com/hackers/Wiz-Zero"><img src="https://img.shields.io/badge/HackenProof-Wiz--Zero-00C853?style=for-the-badge&logo=hackthebox&logoColor=white" alt="HackenProof" /></a>
  <a href="https://tryhackme.com/p/WIZ.ZERO"><img src="https://img.shields.io/badge/TryHackMe-Top_3%25-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" /></a>
  <a href="https://x.com/Zu_wardo"><img src="https://img.shields.io/badge/X-@Zu__wardo-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p>

---

## 🛡️ About Me

```python
class m1h:
    aliases     = ["m1h", "zuwardo-zero", "Wiz-Zero"]
    role        = "Cybersecurity Researcher & Penetration Tester"
    location    = "EMEA (Remote)"
    education   = "B.Sc. in Computer Science"
    languages   = ["Arabic (Native)", "English (Fluent)", "French (Professional)"]

    experience  = [
        "Independent Security Researcher & Penetration Tester (2025 – Present)",
        "University IT Support Volunteer — L1/L2 & Network Ops (2023 – 2024)",
    ]

    focus       = [
        "Application Security: Web, API, Mobile (Android) & Source Code Review",
        "Purple Team Operations, SIEM, Threat Hunting & Incident Response",
        "Open-Source Security Tooling (Rust & Python)",
        "Deep Learning for Healthcare (94.6% accuracy X-ray triage model — 5m → 5s)",
    ]

    certs       = [
        "Microsoft Certified: Security Operations Analyst Associate (SC-200)",
        "Fortinet NSE 3 — Network Security Associate",
    ]
    status      = "Performing security audits & vulnerability research | Open to security roles"
```

---

## ⚡ Vulnerability Research & Impact

| Target / Recognition | Impact & Details |
|---|---|
| 🔓 **[CVE-2026-92916](https://www.cve.org/CVERecord?id=CVE-2026-92916) — Grav CMS** | **CVSS 8.7 (High)** · Unauthenticated profiler exposure leading to admin account takeover via session hijacking across **5,000+ live websites** ([GHSA-q3ff-cj6v-rr5g](https://github.com/getgrav/grav/security/advisories/GHSA-q3ff-cj6v-rr5g) · [Writeup](https://m1h.hashnode.dev/how-i-got-my-first-official-high-severity-cve-that-leads-to-admin-account-hijacking)) |
| 🇩🇰 **Danish State Railways (DSB.dk)** | **Hall of Fame (10th Researcher)** · High-severity subdomain takeover (Dangling NS Delegation) mitigating DNS zone hijacking across national rail infrastructure |
| 🚀 **NASA** | **2× Official Letters of Recognition** · Identified in-scope infrastructure vulnerabilities (`CWE-200` & `CWE-538`) |
| 🇦🇺 **ACT Government (Australia)** | **Official Recognition** · Responsibly disclosed vulnerability in Australian Capital Territory government infrastructure |
| 📺 **Sky News UK** | **Hall of Fame** · Sensitive information exposure via log files (`CWE-532`) |
| 🌍 **JLL Real Estate** | **Hall of Fame** · Forced browsing / direct request vulnerabilities across two assets (`CWE-425`) |
| 🩸 **HackenProof** | **First Blood Trophy** (beat 30+ researchers to first valid bug in program) · **Top 1800** Global Researcher |
| 🏋️ **CTF & Cyber Ranges** | **120+ environments compromised** across **Hack The Box**, **TryHackMe** (Top 3%), and **Hack Smarter** · Active technical writeup author |

---

## 🛠️ Open-Source Security Tooling

### 🦀 [subtake](https://github.com/zuwardo-zero/subdomain-takeover) — Fast Async Subdomain Takeover Scanner
> High-concurrency CLI scanner written in **Rust** that enumerates subdomains and detects dangling DNS records pointing to unclaimed cloud resources.
> - **Multi-Source Enumeration:** Combines Certificate Transparency logs (`crt.sh`, `CertSpotter`, `URLScan.io`), async DNS brute-forcing, permutation generation, recursive discovery, and **BBOT** integration (5 scan modes)
> - **78 Cloud Provider Fingerprints:** Follows full CNAME chains, filters wildcard DNS false positives, and validates NXDOMAIN + HTTP body fingerprints in a single pass
>
> ![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black)
> ![Tokio](https://img.shields.io/badge/Async-Tokio-000000?style=flat-square&logo=rust&logoColor=white)
> ![DNS](https://img.shields.io/badge/Recon-DNS_%26_CT_Logs-0891b2?style=flat-square)

### 🤖 [Shadow MCP](https://github.com/zuwardo-zero/shadow-mcp) — AI Agent & MCP Server Security Auditor
> Lightweight, strictly offline command-line scanner that discovers AI coding agents and Model Context Protocol (MCP) servers on a workstation, builds a complete inventory, and assigns actionable security risk scores.
> - **Multi-Client & Live Process Discovery:** Audits configs across Claude Desktop, Claude Code, Cursor, Windsurf, VS Code, Cline, Roo Code, Continue, and Zed alongside active OS processes in **< 1 second**
> - **6-Domain Static Risk Engine:** Scores exposure (`0–100`, `LOW` to `CRITICAL`) for privileged Docker/sudo execution, root filesystem grants, unpinned `@latest` packages, cleartext transport, and autonomous approval bypasses, with automatic live credential redaction
>
> ![Python](https://img.shields.io/badge/Python_3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
> ![Zero Deps](https://img.shields.io/badge/Dependencies-Zero_(Stdlib)-22c55e?style=flat-square)
> ![AI Security](https://img.shields.io/badge/AI_Sec-MCP_Auditor-8b5cf6?style=flat-square)

### 🔱 [Apk-Hunter](https://github.com/zuwardo-zero/Apk-Hunter) — Android Static Analysis & Bug Bounty Triage Scanner
> Automated Android APK security analysis tool combining `apktool`/`jadx` decompilation, 190+ secret-detection patterns, Firebase auto-testing, and PoC intent generation into a single self-contained interactive HTML/JSON report.
> - **~90% Triage Noise Reduction:** Excludes 50+ third-party SDK prefixes (`okhttp3`, `BouncyCastle`, `Google`, `Facebook`, etc.) for near-zero false positives on application code
> - **Speed & Exploitation:** Cuts per-APK static analysis time from **45+ minutes across 4+ tools to under 5 minutes**, automatically probing `*.firebaseio.com` databases and generating ready-to-run `adb shell am` PoC commands for exported components
>
> ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
> ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
> ![Android](https://img.shields.io/badge/Android_AppSec-SAST-3DDC84?style=flat-square&logo=android&logoColor=black)

---

## 🎓 Certifications

<p>
  <img src="https://img.shields.io/badge/Microsoft_Certified-SC--200_Security_Operations_Analyst_Associate-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft SC-200" />
  <img src="https://img.shields.io/badge/Fortinet_NSE_3-Network_Security_Associate-EE3124?style=for-the-badge&logo=fortinet&logoColor=white" alt="Fortinet NSE 3" />
</p>

---

## 🧰 Technical Arsenal

**🔴 Offensive & Application Security**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&logo=nmap&logoColor=white)
![ffuf](https://img.shields.io/badge/ffuf-EC5923?style=flat-square&logoColor=white)
![BloodHound](https://img.shields.io/badge/BloodHound-AD_Attack_Paths-B91C1C?style=flat-square)
![Ligolo-ng](https://img.shields.io/badge/Ligolo--ng-Pivoting-0891b2?style=flat-square)
![MobSF](https://img.shields.io/badge/MobSF-3DDC84?style=flat-square&logoColor=black)
![apktool/jadx](https://img.shields.io/badge/apktool_%2F_jadx-3DDC84?style=flat-square&logo=android&logoColor=black)

**🔵 Blue Team, SIEM & Detection**

![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel_%2F_Defender-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3AABF7?style=flat-square&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata_IDS/IPS-EF3B2D?style=flat-square&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-CC0000?style=flat-square&logoColor=white)
![Sysmon](https://img.shields.io/badge/Sysmon-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-BF1E2E?style=flat-square&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

**🐍 Programming & Scripting**

![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**🖥️ Infrastructure, Cloud & Networking**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-003399?style=flat-square&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=flat-square&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="155" src="https://github-readme-stats-eight-theta.vercel.app/api?username=zuwardo-zero&show_icons=true&theme=chartreuse-dark&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img height="155" src="https://streak-stats.demolab.com?user=zuwardo-zero&theme=chartreuse-dark&hide_border=true" alt="GitHub Streak" />
  <img height="155" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=zuwardo-zero&layout=compact&theme=chartreuse-dark&hide_border=true" alt="Top Languages" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22c55e,40:0891b2,100:0d1117&height=110&section=footer" width="100%" />
