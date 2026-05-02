# 🚀 Zero2Hero — A Cybersecurity Learning Roadmap

> **A structured, opinionated path from "I just got a PC" to "I can think like an attacker, defender, and architect."**

<p align="left">
  <img src="https://static.wixstatic.com/media/6e5019_5854134ecc1d4b8ea537a47df28ab320~mv2.png/v1/fill/w_473,h_473,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/6e5019_5854134ecc1d4b8ea537a47df28ab320~mv2.png" width="120" alt="Osher Assor">
</p>

**— Osher Assor**

---

## 📖 About this roadmap

Cybersecurity isn't built on tools or exploits — it's built on understanding *how things work*: how an OS schedules a process, how a packet flows from NIC to NIC, how a binary loads into memory. Only after that foundation is real does specialization (pentest, DFIR, GRC, RE…) make sense.

This repo is a **map**, not a textbook. Every topic links to a folder with a structured syllabus, prerequisites, free learning resources (YouTube, free books, free labs), and a checkpoint that tells you when you're ready to move on.

> 💡 **How to use this:** work through the foundations in order (`01 → 16`). Don't skip ahead. Each folder's `readme.md` lists the free resources for that topic. When you've nailed the checkpoint, move to the next number. When you've hit `16 - Security Basics`, you're ready for the **Cyber Security Domain**.

> 📊 **Track your progress:** copy [PROGRESS.md](./PROGRESS.md) to your own fork and check items off as you learn.
> 📚 **All resources in one place:** see [RESOURCES.md](./RESOURCES.md).

---

## 🧱 Part 1 — Foundations (learn in order)

| #  | Topic | What you'll learn | Time | Key free resource |
|----|-------|-------------------|------|-------------------|
| 01 | [PC Architecture & Hardware](./01%20-%20PC%20Architecture%20%26%20Hardware) | CPU, RAM, storage, motherboard, PSU | 8–12 h | [Crash Course CS](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo) |
| 02 | [Digital Logic & Binary Systems](./02%20-%20Digital%20Logic%20%26%20Binary%20Systems) | Binary, gates, adders, FSMs | 6–10 h | [Ben Eater — 8-bit computer](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU) |
| 03 | [Operating System Fundamentals](./03%20-%20Operating%20System%20Fundamentals) | Processes, memory, syscalls, scheduling | 20–30 h | [OSTEP (free book)](https://pages.cs.wisc.edu/~remzi/OSTEP/) |
| 04 | [Filesystems & Storage](./04%20-%20Filesystems%20%26%20Storage) | Partitions, FS internals, RAID | 5–8 h | [OSTEP File System chapters](https://pages.cs.wisc.edu/~remzi/OSTEP/) |
| 05 | [Linux Fundamentals](./05%20-%20Linux%20Fundamentals) | CLI, permissions, packages, bash | 30–40 h | [Linux Journey](https://linuxjourney.com/) + [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) |
| 06 | [Windows Internals](./06%20-%20Windows%20Internals) | Kernel, registry, services, PowerShell | 20–30 h | [Microsoft Learn](https://learn.microsoft.com/en-us/training/) |
| 07 | [Networking](./07%20-%20Networking) | OSI, devices, routing, switching | 40–60 h | ⭐ **[Jeremy's IT Lab — free CCNA](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ)** |
| 08 | [Fundamental IT Protocols](./08%20-%20Fundamental%20IT%20Protocols) | HTTP(S), DNS, DHCP, TLS, SMB | 15–20 h | [Cloudflare Learning](https://www.cloudflare.com/learning/) |
| 09 | [Active Directory & Domain Services](./09%20-%20Active%20Directory%20%26%20Domain%20Services) | Forest/domain, GPO, Kerberos | 20–30 h | [TryHackMe AD Basics](https://tryhackme.com/room/winadbasics) |
| 10 | [Virtualization & Containers](./10%20-%20Virtualization%20%26%20Containers) | Hypervisors, VMs, Docker, K8s basics | 15–20 h | [Docker Get Started](https://docs.docker.com/get-started/) |
| 11 | [Cloud Computing Fundamentals](./11%20-%20Cloud%20Computing%20Fundamentals) | IaaS/PaaS/SaaS, IAM, cloud nets | 20–30 h | [AZ-900](https://learn.microsoft.com/en-us/training/courses/az-900t00) / [AWS CCP](https://skillbuilder.aws/) |
| 12 | [System Administration & IT Operations](./12%20-%20System%20Administration%20%26%20IT%20Operations) | Run real Linux + Windows + AD systems | ongoing | [Sander van Vugt RHCSA (YT)](https://www.youtube.com/@SandervanVugt) |
| 13 | [Software & Application Behavior](./13%20-%20Software%20%26%20Application%20Behavior) | How apps run, log, fail | 10–15 h | [Brendan Gregg](https://www.brendangregg.com/) |
| 14 | [Software Development Environments](./14%20-%20Software%20Development%20Environments) | git, IDEs, build, package, CI | 10–15 h | [Pro Git (free)](https://git-scm.com/book/en/v2) |
| 15 | [Programming & Scripting Foundations](./15%20-%20Programming%20%26%20Scripting%20Foundations) | Python + bash + a compiled lang | 60–100 h | [CS50x](https://cs50.harvard.edu/x/) + [Automate the Boring Stuff](https://automatetheboringstuff.com/) |
| 16 | [Security Basics](./16%20-%20Security%20Basics) | CIA, threats, controls, OWASP | 20–30 h | [Professor Messer Sec+](https://www.youtube.com/playlist?list=PLG49S3nxzAnnVhoAaL4B6aMFDQ8_gdxAy) |

> Each folder's `readme.md` contains the **full syllabus** for that topic plus 2–3 curated free resources. Don't just watch videos — do the labs and the OverTheWire/TryHackMe rooms.

---

## 🛡️ Part 2 — Cyber Security Domain (specialize)

Once Part 1 is solid, pick a specialization. The domains below are grouped by orientation — **defensive**, **offensive**, **governance** — but read the foundations of each before committing to one.

### 🟦 Foundational

| Domain | Topics |
|--------|--------|
| [Cybersecurity Foundations](./Cyber%20Security%20Domain/Cybersecurity%20Foundations) | CIA Triad · Risk vs Threat · Security Controls · Kill Chain · Attacker Types |
| [Security Appliances & Defensive Mechanisms](./Cyber%20Security%20Domain/Security%20Appliances%20%26%20Defensive%20Mechanisms) | Firewalls · WAF · EDR/XDR · IDS/IPS · DLP · NAC |

### 🔍 Defensive (Blue Team)

| Domain | Topics |
|--------|--------|
| [Security Operations Center (SOC)](./Cyber%20Security%20Domain/Security%20Operations%20Center%20%28SOC%29) | SIEM & SOAR · Alert Triage · Threat Hunting · Incident Response |
| [Digital Forensics & Incident Response (DFIR)](./Cyber%20Security%20Domain/Digital%20Forensics%20%26%20Incident%20Response%20%28DFIR%29) | Memory · Network · Malware Triage · Timeline Reconstruction |
| [Malware Analysis](./Cyber%20Security%20Domain/Malware%20Analysis) | Static · Dynamic · Persistence · C2 Behavior |
| [Reverse Engineering Fundamentals](./Cyber%20Security%20Domain/Reverse%20Engineering%20Fundamentals) | Binary Dissection · Assembly · Debugging · Anti-Reversing |

### 🗡️ Offensive (Red Team)

| Domain | Topics |
|--------|--------|
| [OSINT (Open Source Intelligence)](./Cyber%20Security%20Domain/OSINT%20%28Open%20Source%20Intelligence%29) | Passive/Active Recon · Metadata · Social · Infra Enum · Tooling |
| [Penetration Test](./Cyber%20Security%20Domain/Penetration%20Test) | Web · Mobile · Thick Client · Internal/External Infra · Cloud · Wi-Fi · RF · Hardware · OT · LLM Attacks · Code Review · Reports |

#### 🎯 Penetration Test sub-paths

| Path | Folder |
|------|--------|
| Web Application | [link](./Cyber%20Security%20Domain/Penetration%20Test/Web%20Application%20Penetration%20Testing) |
| Mobile Application | [link](./Cyber%20Security%20Domain/Penetration%20Test/Mobile%20Application%20Penetration%20Testing) |
| Thick Client | [link](./Cyber%20Security%20Domain/Penetration%20Test/Thick%20Client%20Application%20Penetration%20Testing) |
| Internal & External Infra (with MITRE) | [link](./Cyber%20Security%20Domain/Penetration%20Test/Internal%20%26%20External%20Infrastructure%20Pentesting%20%28with%20MITRE%20Mapping%29) |
| Cloud | [link](./Cyber%20Security%20Domain/Penetration%20Test/Cloud%20Penetration%20Testing) |
| Wi-Fi | [link](./Cyber%20Security%20Domain/Penetration%20Test/Wi-Fi%20Penetration%20Testing) |
| Radio Frequency (RF) | [link](./Cyber%20Security%20Domain/Penetration%20Test/Radio%20Frequancy%20Penetration%20Test) |
| Hardware | [link](./Cyber%20Security%20Domain/Penetration%20Test/Hardware%20Penetration%20Testing) |
| OT (Operational Technology) | [link](./Cyber%20Security%20Domain/Penetration%20Test/OT%20%28Operational%20Technology%29%20Penetration%20Testing) |
| LLM Attacks | [link](./Cyber%20Security%20Domain/Penetration%20Test/LLM%20Attacks) |
| Security Code Review | [link](./Cyber%20Security%20Domain/Penetration%20Test/Security%20Code%20Review) |
| Structure of a PT Report | [link](./Cyber%20Security%20Domain/Penetration%20Test/Structure%20of%20a%20Penetration%20Testing%20Report) |

### 📋 Governance & Engineering

| Domain | Topics |
|--------|--------|
| [CI/CD Security Processes](./Cyber%20Security%20Domain/CICD%20Security%20Processes) | Threat Modeling · Secure Coding · SAST / DAST · Pipeline Hardening |
| [Governance, Risk, and Compliance (GRC)](./Cyber%20Security%20Domain/Governance%2C%20Risk%2C%20and%20Compliance%20%28GRC%29) | ISO/NIST · Risk Register · Control Mapping · Audit Readiness |

---

## 🤝 Contributing

This is a **living roadmap**. If you have:

- a better free resource for a topic,
- a missing subtopic,
- a corrected link,
- or a structured guide / video series aligned with a section,

…open a PR or reach out. Collaboration welcome.

---

## 📜 License & credit

Roadmap by **Osher Assor**. Free to share, fork, learn from. Attribution appreciated.
