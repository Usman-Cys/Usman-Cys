<div align="center">

# Hi, I'm Usman Fazal 👋

<p align="center">
  <b>Cybersecurity Graduate</b> building practical security tools, secure applications, and privacy-focused systems.
</p>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=38BDF8&center=true&vCenter=true&width=680&lines=Offensive+Security+%7C+Web+%26+AppSec;Post-Quantum+Cryptography+%26+Client-Side+ZK;Reverse+Engineering+%26+Protocol+Analysis;Linux%2C+Cloud+Security+%26+DevSecOps;Learn.+Break.+Build.+Secure." alt="Typing Headline" />
</a>

<p align="center">
  <i>"Learn. Break. Build. Secure."</i>
</p>

<!-- Clean, refined contact badges -->
[![GitHub](https://img.shields.io/badge/GitHub-Usman--Cys-24292f?style=flat&logo=github&logoColor=white)](https://github.com/Usman-Cys)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-334155?style=flat&logo=gmail&logoColor=white)](mailto:contact@usmanfazal.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Labs-1e293b?style=flat&logo=tryhackme&logoColor=f97316)](https://tryhackme.com)
[![Hack The Box](https://img.shields.io/badge/HackTheBox-CTFs-1e293b?style=flat&logo=hackthebox&logoColor=22c55e)](https://www.hackthebox.com)

</div>

---

### 🧑‍💻 About Me

I am a **BS Cybersecurity graduate** passionate about understanding how systems operate, discovering where they break, and engineering robust solutions to defend them.

My hands-on work bridges **offensive security, application security, reverse engineering, and cryptographic engineering**:

* 🎓 **BS in Cybersecurity** with solid foundations in application security, network defense, and cryptography.
* 🛡️ **Offensive & Web Security:** Experienced with **OWASP Top 10**, asset enumeration, auth flaws, and manual vulnerability verification.
* 🔬 **Cryptographic Tool Builder:** Designed and implemented **NGCloud** as my Final Year Project, pairing NIST post-quantum key encapsulation with client-side zero-knowledge architecture.
* 🔎 **Reverse Engineering:** Experienced decompiling Android APKs (**JADX**, **APKTool**), reconstructing proprietary protocols, and identifying undocumented API endpoints.
* 🐧 **System Proficiency:** Daily Linux & Kali Linux workflow, Docker container isolation, and Python/Bash automation.
* 🧪 **Hands-On Labs:** Regular practical work across **Hack The Box**, **TryHackMe**, and vulnerable web labs (DVWA, OWASP Juice Shop).

---

### 🛡️ Security Focus & Core Areas

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🎯 Offensive & Web Security</h4>
      <ul>
        <li><b>Web Penetration Testing:</b> Methodical enumeration, parameter fuzzing, and manual exploit verification.</li>
        <li><b>OWASP Top 10 Mitigation:</b> Identifying and mitigating XSS, SQLi, IDOR, SSRF, and CSRF vulnerabilities.</li>
        <li><b>Auth & Session Flaws:</b> JWT signature bypasses, token expiration risks, and broken access controls.</li>
        <li><b>Security Tooling:</b> Custom multithreaded port scanners and automated reconnaissance scripts.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🔒 Cryptography & Privacy</h4>
      <ul>
        <li><b>Post-Quantum Cryptography:</b> NIST FIPS 203 <b>ML-KEM-768</b> key encapsulation mechanism.</li>
        <li><b>Client-Side Zero-Knowledge:</b> Memory-only browser cryptographic boundaries with zero server-side trust.</li>
        <li><b>Lightweight AEAD & Ciphers:</b> <b>Ascon-128a</b> authenticated encryption and custom lattice stream ciphers.</li>
        <li><b>Key Derivation & Hashing:</b> <b>Argon2id</b> memory-hard KDF and quantum-walk simulated hash (KT-QHF).</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔎 Reverse Engineering & Analysis</h4>
      <ul>
        <li><b>Android APK Decompilation:</b> Static bytecode inspection using <b>JADX-GUI</b> and <b>APKTool</b>.</li>
        <li><b>Protocol & API Extraction:</b> Intercepting socket payloads, extracting hidden REST endpoints, and analyzing data flow.</li>
        <li><b>Binary Fundamentals:</b> Inspecting ELF/PE structures, string extraction, and Ghidra disassembly.</li>
        <li><b>Software Reconstruction:</b> Re-engineering functional software clients from reverse-engineered specifications.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>☁️ Cloud & Infrastructure Security</h4>
      <ul>
        <li><b>Linux Server Hardening:</b> Service auditing, SSH key policy enforcement, and permission least-privilege.</li>
        <li><b>Container Isolation:</b> Docker Compose and multi-container security configurations.</li>
        <li><b>Object Storage Security:</b> MinIO S3 bucket access policies, presigned URLs, and CORS hardening.</li>
        <li><b>Relational DB Integrity:</b> PostgreSQL schema constraints, RBAC, and hash-chained audit trails.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🚀 Featured Practical Projects

#### 1. 🛡️ [NG-CLOUD — Post-Quantum Zero-Knowledge Cloud Storage](https://github.com/Usman-Cys/NG-CLOUD)
> **Final Year Project (BS Cybersecurity)**

A client-side zero-knowledge cloud storage platform engineered to protect files against "Harvest Now, Decrypt Later" quantum threats. Plaintext files, passwords, and private decryption keys exist exclusively in volatile browser RAM and never reach the backend server or database.

* **Cryptography & WebAssembly:** Pure Rust compiled to WebAssembly running **NIST FIPS 203 ML-KEM-768**, custom **FS-MLWE-SC-256** lattice stream cipher with 1 MB epoch rekeying, **Ascon-128a AEAD**, **Argon2id**, and **KT-QHF** hash.
* **Storage & Architecture:** Direct presigned S3 transfers to **MinIO Object Storage**, metadata handling via **PostgreSQL 15**, and **Express 5 / Node.js** API gateway.
* **Collaboration & Sync:** Cryptographic key re-wrapping under recipient public keys, 4 MB chunk-level delta synchronization, and 15-minute concurrency lock leases.
* **Tech Stack:** `Rust` • `WebAssembly` • `React 18` • `Vite` • `Node.js` • `Express` • `PostgreSQL` • `MinIO S3` • `Docker`

---

#### 2. 🔍 [Android APK Reverse Engineering & Protocol Extraction](https://github.com/Usman-Cys/partybox-photobooth-final)
> **Binary & Protocol Reverse Engineering Project**

In-depth static and dynamic reverse engineering of proprietary Android APKs ([Kodak](https://github.com/Usman-Cys/kodak-reverse-eng) & [PartyBox](https://github.com/Usman-Cys/partybox-photobooth-final)).

* Analyzed compiled classes using **JADX-GUI** and **APKTool** to navigate obfuscated bytecode, trace state machines, and map internal logic execution paths.
* Intercepted socket traffic to extract hidden TCP commands, hardware communication ports, and internal REST API endpoints.
* Used the reversed protocol specifications to re-author a clean, modern working software interface from scratch.
* **Tech Stack:** `JADX` • `APKTool` • `Android Bytecode` • `Wireshark` • `Socket Analysis`

---

#### 3. ⚡ [VulnIntel — Vulnerability Assessment & Security Analysis Platform](https://github.com/Usman-Cys/VulnIntel)
> **Application Security & Automated Triage**

An intelligent security analysis engine uniting **DAST** and **SAST** security assessment pipelines with Google Gemini AI contextual analysis for automated attack surface mapping, CVSS 3.1 scoring, and prioritized remediation playbooks.

* **Tech Stack:** `Python` • `FastAPI` • `DAST/SAST` • `Gemini AI` • `React` • `Tailwind CSS`

---

#### 4. 🧰 Network Reconnaissance & Security Tooling

* **[Port-Scanner](https://github.com/Usman-Cys/Port-scanner):** Custom multithreaded network utility for rapid TCP and UDP port discovery, socket state verification, and open service identification.
* **[Password-Analyzer](https://github.com/Usman-Cys/password-analyzer):** Security evaluation tool calculating Shannon entropy, testing dictionary vulnerability, and verifying cryptographic salt/hash resistance.
* **[Sentinel](https://github.com/Usman-Cys/Sentinel):** Web penetration testing assistant automating initial reconnaissance, endpoint enumeration, and parameter discovery.

---

### 🧪 Hands-On Labs & Practical Training

I actively strengthen my offensive security skills through hands-on labs and challenge environments:

| Platform / Lab | Focus Areas & Hands-On Skills | Primary Tools Used |
| :--- | :--- | :--- |
| **Hack The Box** | Linux Privilege Escalation, SSH Enumeration, Web Exploitation, CTF challenges | `Nmap`, `Burp Suite`, `LinPEAS`, `Netcat` |
| **TryHackMe** | Web Security Fundamentals, Network Security, Active Directory Basics, Linux Hardening | `Gobuster`, `Hydra`, `Metasploit`, `John` |
| **Vulnerable Apps** | Manual OWASP testing on DVWA, OWASP Juice Shop, and custom vulnerable microservices | `Burp Suite Pro`, `OWASP ZAP`, `SQLmap` |
| **Traffic Inspection** | Dissecting packet captures (.pcap), spotting cleartext credential leaks, DNS analysis | `Wireshark`, `Tcpdump`, `Tshark` |

---

### 🛠️ Technical Skills & Toolbelt

<div align="center">

#### 🔒 Security, Audit & Penetration Testing
[![Kali Linux](https://img.shields.io/badge/Kali_Linux-1e293b?style=flat-square&logo=kali-linux&logoColor=38bdf8)](https://www.kali.org/)
[![Burp Suite](https://img.shields.io/badge/Burp_Suite-1e293b?style=flat-square&logo=burp-suite&logoColor=f97316)](https://portswigger.net/burp)
[![Wireshark](https://img.shields.io/badge/Wireshark-1e293b?style=flat-square&logo=wireshark&logoColor=38bdf8)](https://www.wireshark.org/)
[![Nmap](https://img.shields.io/badge/Nmap-1e293b?style=flat-square&logo=freebsd&logoColor=60a5fa)](https://nmap.org/)
[![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-1e293b?style=flat-square&logo=owasp&logoColor=38bdf8)](https://www.zaproxy.org/)
[![Metasploit](https://img.shields.io/badge/Metasploit-1e293b?style=flat-square&logo=metasploit&logoColor=f43f5e)](https://www.metasploit.com/)
[![Ghidra](https://img.shields.io/badge/Ghidra-1e293b?style=flat-square&logo=gnubash&logoColor=a78bfa)](https://ghidra-sre.org/)
[![JADX](https://img.shields.io/badge/JADX-1e293b?style=flat-square&logo=android&logoColor=34d399)](https://github.com/skylot/jadx)

#### 🔐 Cryptography & Privacy Primitives
[![ML-KEM-768](https://img.shields.io/badge/ML--KEM--768-NIST_FIPS_203-0284c7?style=flat-square)](https://csrc.nist.gov/pubs/fips/203/final)
[![Ascon-128a](https://img.shields.io/badge/Ascon--128a-NIST_LWC-0284c7?style=flat-square)](https://csrc.nist.gov/projects/lightweight-cryptography)
[![Argon2id](https://img.shields.io/badge/Argon2id-RFC_9106-0284c7?style=flat-square)](https://www.rfc-editor.org/rfc/rfc9106)
[![Zero-Knowledge](https://img.shields.io/badge/Zero--Knowledge-Architecture-0284c7?style=flat-square)](https://en.wikipedia.org/wiki/Zero-knowledge_proof)
[![SHA-256 / SHAKE](https://img.shields.io/badge/SHA--256_%7C_SHAKE-FIPS_202-0284c7?style=flat-square)](https://csrc.nist.gov/publications/detail/fips/202/final)

#### 💻 Programming & Scripting Languages
[![Python](https://img.shields.io/badge/Python-1e293b?style=flat-square&logo=python&logoColor=38bdf8)](https://www.python.org/)
[![Rust](https://img.shields.io/badge/Rust-1e293b?style=flat-square&logo=rust&logoColor=f97316)](https://www.rust-lang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-1e293b?style=flat-square&logo=javascript&logoColor=facc15)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/TypeScript-1e293b?style=flat-square&logo=typescript&logoColor=60a5fa)](https://www.typescriptlang.org/)
[![C / C++](https://img.shields.io/badge/C_%2F_C%2B%2B-1e293b?style=flat-square&logo=c%2B%2B&logoColor=60a5fa)](https://isocpp.org/)
[![Bash](https://img.shields.io/badge/Bash-1e293b?style=flat-square&logo=gnubash&logoColor=34d399)](https://www.gnu.org/software/bash/)
[![SQL](https://img.shields.io/badge/SQL-1e293b?style=flat-square&logo=postgresql&logoColor=60a5fa)](https://www.postgresql.org/)

#### ⚙️ Web, Cloud & Storage Infrastructure
[![React](https://img.shields.io/badge/React_18-1e293b?style=flat-square&logo=react&logoColor=38bdf8)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-1e293b?style=flat-square&logo=vite&logoColor=a78bfa)](https://vitejs.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-1e293b?style=flat-square&logo=node.js&logoColor=34d399)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-1e293b?style=flat-square&logo=express&logoColor=e2e8f0)](https://expressjs.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-1e293b?style=flat-square&logo=fastapi&logoColor=2dd4bf)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e293b?style=flat-square&logo=postgresql&logoColor=60a5fa)](https://www.postgresql.org/)
[![MinIO](https://img.shields.io/badge/MinIO_S3-1e293b?style=flat-square&logo=minio&logoColor=f43f5e)](https://min.io/)
[![Docker](https://img.shields.io/badge/Docker-1e293b?style=flat-square&logo=docker&logoColor=38bdf8)](https://www.docker.com/)

</div>

---

### 🚧 What I'm Building & Career Pathway

```mermaid
flowchart LR
    A["🎯 <b>Offensive Security</b><br/>Web Pentesting, Recon & CTFs"] --> B["🛡️ <b>Application Security</b><br/>OWASP Top 10 & Code Audit"]
    B --> C["☁️ <b>Cloud & DevSecOps</b><br/>Docker, Linux Hardening & CI/CD"]
    C --> D["🔐 <b>Security Engineering</b><br/>PQC, Zero-Knowledge & Cryptography"]

    classDef default fill:#0f172a,stroke:#334155,stroke-width:1px,color:#cbd5e1;
    classDef nodeStyle fill:#0f172a,stroke:#38bdf8,stroke-width:1.5px,color:#38bdf8;
    class A,B,C,D nodeStyle;
```

> **Current Objective:** Transitioning university achievements into professional roles in **Cybersecurity**, **Application Security (AppSec)**, **Penetration Testing**, or **Cloud Security Engineering**.

---

### 📚 Currently Exploring & Expanding

* 🎯 Deepening manual **Web Application Penetration Testing** methodologies beyond automated tooling.
* 🐧 Advanced **Linux Privilege Escalation** techniques and kernel vulnerability identification.
* ☁️ **Cloud Security Posture Management (CSPM)** & AWS / S3 container policy auditing.
* 🔬 Low-level **Binary Exploitation & Memory Safety** fundamentals in C and Rust.


---

### 🤝 Let's Connect

I am actively open to discussing **entry-level and junior cybersecurity opportunities**, technical collaborations, and project discussions:

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow_@Usman--Cys-24292f?style=flat&logo=github&logoColor=white)](https://github.com/Usman-Cys)
[![Email](https://img.shields.io/badge/Email-Contact_Me-334155?style=flat&logo=gmail&logoColor=white)](mailto:contact@usmanfazal.com)

<br />

<sub><i>Building systems, breaking systems, and learning how to secure them.</i></sub>

</div>
