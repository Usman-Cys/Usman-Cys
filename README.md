<div align="center">

# Hi, I'm Usman Fazal 👋

<p align="center">
  <b>Cybersecurity Graduate</b> building practical security tools, secure applications, and privacy-focused systems.
</p>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00F0FF&center=true&vCenter=true&width=650&lines=Offensive+Security+%7C+Web+%26+AppSec;Post-Quantum+Cryptography+%26+Client-Side+ZK;Reverse+Engineering+%26+Protocol+Analysis;Linux%2C+Cloud+Security+%26+DevSecOps;Learn.+Break.+Build.+Secure." alt="Typing SVG" />
</a>

<p align="center">
  <i>"Learn. Break. Build. Secure."</i>
</p>

[![GitHub](https://img.shields.io/badge/GitHub-Usman--Cys-181717?style=flat-square&logo=github)](https://github.com/Usman-Cys)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail)](mailto:contact@usmanfazal.com)

</div>

---

### 🧑‍💻 About Me

I am a **BS Cybersecurity graduate** passionate about understanding how systems operate, finding where they break, and engineering robust solutions to defend them. 

My hands-on work bridges **offensive security, application security, reverse engineering, and cryptographic engineering**:
* 🎓 **BS Cybersecurity Graduate** with hands-on project and lab experience.
* 🛡️ Interested in **Offensive Security, Web & Application Security, and Security Engineering**.
* 🌐 Practicing **Vulnerability Assessment, OWASP Top 10, and Web Penetration Testing**.
* ☁️ Exploring **Cloud Security, Containerization, and DevSecOps**.
* 🔬 Built **NGCloud** as my Final Year Project, implementing client-side zero-knowledge encryption and post-quantum lattice cryptography.
* 🔎 Experienced with **Android APK decompilation and binary/protocol reverse engineering**.
* 🐧 Comfortable working daily in **Linux & Kali Linux** environments.
* 🧪 Active on **TryHackMe, Hack The Box, and hands-on vulnerable lab environments**.
* 💻 Committed to writing working code, building tools, and doing practical security over pure theory.

---

### 🛡️ Security Focus & Interests

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🎯 Offensive & Web Security</h4>
      <ul>
        <li>Web Application Penetration Testing</li>
        <li>OWASP Top 10 (SQLi, XSS, CSRF, IDOR, SSRF)</li>
        <li>Reconnaissance & Asset Enumeration</li>
        <li>Authentication & Session / JWT Flaws</li>
        <li>Vulnerability Assessment (DAST / SAST)</li>
        <li>Hands-on CTFs, Hack The Box & TryHackMe</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🔒 Cryptography & Privacy</h4>
      <ul>
        <li>Client-Side Zero-Knowledge Architectures</li>
        <li>Post-Quantum Cryptography (NIST FIPS 203 ML-KEM)</li>
        <li>Symmetric & Lattice Stream Ciphers</li>
        <li>Authenticated Encryption (Ascon-128a AEAD)</li>
        <li>Key Derivation (Argon2id, PBKDF)</li>
        <li>Key Encapsulation & Secure Wrapping</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔎 Reverse Engineering & Malware Analysis</h4>
      <ul>
        <li>Android APK Decompilation & Static Analysis</li>
        <li>API Endpoint & Protocol Extraction</li>
        <li>Ghidra, JADX, APKTool, and Bytecode Inspection</li>
        <li>ELF / PE Binary Fundamentals</li>
        <li>Dynamic Analysis & Network Traffic Interception</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>☁️ Cloud & Infrastructure Security</h4>
      <ul>
        <li>Linux Systems Administration & Hardening</li>
        <li>Docker & Container Security</li>
        <li>Object Storage (MinIO S3) & Access Policies</li>
        <li>Relational Database Security (PostgreSQL)</li>
        <li>DevSecOps Fundamentals & CI/CD Hygiene</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🚀 Featured Practical Projects

#### 1. 🛡️ [NG-CLOUD — Post-Quantum Zero-Knowledge Cloud Storage](https://github.com/Usman-Cys/NG-CLOUD)
> **Final Year Project (BS Cybersecurity)**

A client-side zero-knowledge cloud storage platform engineered to protect files against "Harvest Now, Decrypt Later" quantum threats. Plaintext files, passwords, and private keys never leave the client browser's memory.

* **Cryptography & WebAssembly:** Rust compiled to WASM running **NIST FIPS 203 ML-KEM-768**, custom **FS-MLWE-SC-256** lattice stream cipher, **Ascon-128a AEAD**, **Argon2id**, and **KT-QHF** toroidal quantum-walk simulated hash.
* **Storage & Infrastructure:** Direct presigned S3 uploads/downloads to **MinIO**, metadata coordination via **PostgreSQL 15**, and **Express 5 / Node.js** API gateway.
* **Collaboration & Sync:** Cryptographic key re-wrapping under recipient public keys, 4 MB chunk-level delta synchronization, and 15-minute concurrency lock leases.
* **Tech Stack:** `Rust` • `WebAssembly` • `React 18` • `Vite` • `Node.js` • `Express` • `PostgreSQL` • `MinIO S3` • `Docker`

---

#### 2. 🔍 [Android APK Reverse Engineering & Protocol Extraction](https://github.com/Usman-Cys/partybox-photobooth-final)
> Practical reverse engineering and software reconstruction from compiled binaries.

* Analyzed and decompiled Android APKs ([Kodak](https://github.com/Usman-Cys/kodak-reverse-eng) & [PartyBox](https://github.com/Usman-Cys/partybox-photobooth-final)) to understand proprietary communication protocols, undocumented API endpoints, internal state machines, and hardware integration ports.
* Used **JADX**, **APKTool**, and traffic analysis to map client-server workflows and re-implement a clean, modern working software interface from scratch.
* **Concepts Demonstrated:** Static analysis, obfuscation navigation, socket inspection, API discovery, and protocol reconstruction.

---

#### 3. 🔍 [VulnIntel — Vulnerability Assessment & Security Analysis Platform](https://github.com/Usman-Cys/VulnIntel)
> Practical security analysis platform integrating automated scanning workflows.

* Combines **DAST** and **SAST** security assessment pipelines with Google Gemini AI assistance for contextual vulnerability analysis, CVSS scoring, and actionable remediation guidance.
* **Tech Stack:** `Python` • `FastAPI` • `React` • `Tailwind CSS` • `Security Scanners`

---

#### 4. 🧰 Network Reconnaissance & Security Tooling

* **[Port-Scanner](https://github.com/Usman-Cys/Port-scanner):** Custom multithreaded network utility for rapid TCP and UDP port discovery, socket state verification, and open service identification.
* **[Password-Analyzer](https://github.com/Usman-Cys/password-analyzer):** Practical security tool evaluating password entropy, dictionary attack susceptibility, and cryptographic hashing requirements.
* **[Sentinel](https://github.com/Usman-Cys/Sentinel):** Web penetration testing assistant coordinating asset enumeration, endpoint crawling, and initial attack surface mapping.

---

### 🧪 Practical Labs & Hands-On Practice

I actively strengthen my offensive security skills through hands-on labs and challenge environments:

* **Hack The Box:** Focus on Linux privilege escalation, network enumeration, SSH/web service exploitation, and CTF challenges.
* **TryHackMe:** Completing learning paths across Web Security Fundamentals, Network Security, Linux Fundamentals, and Offensive Tooling.
* **Vulnerable Application Testing:** Practicing manual exploit verification on Juice Shop, DVWA, and custom vulnerable labs.
* **Network & Traffic Inspection:** Analyzing PCAP captures in **Wireshark** to dissect protocols, cleartext leaks, and anomalous communication.

---

### 🛠️ Technical Skills

```text
Security & Tools     Nmap • Burp Suite • OWASP ZAP • Wireshark • Ghidra • JADX • Metasploit • Kali Linux
Cryptography         ML-KEM-768 (Kyber) • Ascon-128a • Argon2id • Zero-Knowledge • AEAD • SHA-256 / SHAKE
Languages            Python • JavaScript • TypeScript • C/C++ • Rust • SQL • Bash
Web & Frameworks     React 18 • Vite • Node.js • Express • FastAPI • REST APIs • JWT
Infrastructure       Linux • Docker • MinIO S3 • PostgreSQL • Git & GitHub • VS Code
```

---

### 📚 Currently Learning & Exploring

* 🎯 Deepening **Web Application Penetration Testing** & manual vulnerability exploitation
* 🐧 Advanced **Linux Privilege Escalation** techniques and kernel exploit mechanics
* ☁️ **Cloud Security & DevSecOps** (CI/CD pipeline security, container hardening, IAM policy audit)
* 🔬 Practical **Binary Exploitation & Buffer Overflow** fundamentals
* ⚙️ Security automation using **Python & Bash scripting**

---

### 🚧 What I'm Building & Career Direction

```text
Offensive Security & Web Pentesting
                 ↓
Application Security & Vulnerability Assessment
                 ↓
Cloud Security & DevSecOps
                 ↓
Security Engineering & Cryptography (NGCloud / PQC)
```

> **Goal:** Transitioning from university into full-time roles in **Cybersecurity**, **Security Engineering**, **Application Security / Pentesting**, or **Cloud Security**.

---

### 📊 GitHub Activity

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Usman-Cys&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F0FF&text_color=c9d1d9&icon_color=00F0FF" alt="Usman's GitHub Stats" />
      </td>
      <td>
        <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Usman-Cys&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F0FF&text_color=c9d1d9" alt="Top Languages" />
      </td>
    </tr>
  </table>
  <br />
  <img src="https://streak-stats.demolab.com?user=Usman-Cys&theme=tokyonight&hide_border=true&background=0d1117&ring=00F0FF&fire=00F0FF&currStreakLabel=00F0FF" alt="GitHub Streak" />
</div>

---

### 🤝 Let's Connect

I am actively looking for **entry-level and junior cybersecurity opportunities**, internships, and collaborative projects in:
* **Penetration Testing & Web Application Security**
* **Application Security (AppSec) & DevSecOps**
* **Security Engineering & Cloud Security**
* **Cryptographic Engineering & Security Research**

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow_@Usman--Cys-181717?style=flat-square&logo=github)](https://github.com/Usman-Cys)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail)](mailto:contact@usmanfazal.com)

<br />

<i>Building systems, breaking systems, and learning how to secure them.</i>

</div>
