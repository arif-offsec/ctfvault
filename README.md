<div align="center">

# 🗝️ CTFVault

**A categorized, difficulty-tagged directory of 100+ completely free CTF and cybersecurity practice platforms.**

[![Free](https://img.shields.io/badge/Cost-100%25%20Free-brightgreen)]()
[![Categories](https://img.shields.io/badge/Categories-15-blue)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## About

CTFVault is a curated, deduplicated list of free CTF platforms, wargames, vulnerable labs, and challenge archives — sorted by subject (Web, Crypto, Pwn, Forensics, Active Directory, Cloud, Mobile, and more) and tagged 🟢 Beginner, 🟡 Intermediate, or 🔴 Advanced within each category, so you can find your actual starting point instead of scrolling a flat list.

A resource is listed in the main sections only if it's free to access without a subscription or paid tier. Platforms that are free-to-start but paywalled past a point (TryHackMe, Hack The Box, Root-Me, PentesterLab, etc.) are kept in a clearly marked [Freemium](#freemium--free-tier-only) section instead of the main list, so the two are never mixed.

No list like this can stay perfectly current — CTF sites appear and disappear constantly. If a link is dead or a platform's pricing changed, please open a PR. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Table of Contents

- [General & Multi-Category Platforms](#general--multi-category-platforms)
- [Linux, Systems & Privilege Escalation](#linux-systems--privilege-escalation)
- [Web Application & API Security](#web-application--api-security)
- [Binary Exploitation (Pwn) & Reverse Engineering](#binary-exploitation-pwn--reverse-engineering)
- [Cryptography](#cryptography)
- [Digital Forensics, Blue Team & SOC](#digital-forensics-blue-team--soc)
- [OSINT](#osint)
- [Active Directory & Vulnerable VMs](#active-directory--vulnerable-vms)
- [Cloud Security](#cloud-security)
- [Mobile Security (Android / iOS)](#mobile-security-android--ios)
- [Blockchain, Smart Contracts & AI/LLM Security](#blockchain-smart-contracts--aillm-security)
- [Hardware & Embedded](#hardware--embedded)
- [CTF Archives & Past Competitions](#ctf-archives--past-competitions)
- [Learning Guides, Field Manuals & Curated Lists](#learning-guides-field-manuals--curated-lists)
- [Freemium / Free-Tier Only](#freemium--free-tier-only)
- [Regional Platforms (pricing unverified)](#regional-platforms-pricing-unverified)
- [A Note on Using These Responsibly](#a-note-on-using-these-responsibly)

---

<details open>
<summary><h2>General & Multi-Category Platforms</h2></summary>

#### 🟢 Beginner
- **[picoCTF / picoGym](https://play.picoctf.org/)** — Carnegie Mellon's flagship beginner-to-intermediate archive. Web, Crypto, Forensics, Reverse Engineering, Binary Exploitation, General Skills. picoGym stays open year-round, not just during the annual competition.
- **[CTFlearn](https://ctflearn.com/)** — Community-submitted challenges tagged by difficulty and category. Free forever, donations optional.
- **[HackThisSite](https://www.hackthissite.org/)** — One of the oldest training grounds still active. Starts with 11 Basic missions, then moves into JavaScript, programming, stego, forensics, and application challenges.
- **[Hackropole](https://hackropole.fr/en/)** — 300+ past France Cybersecurity Challenge tasks across crypto/web/forensics/pwn, beginner to expert, no account required.
- **[Hacker101 CTF](https://ctf.hacker101.com/)** (HackerOne) — Challenge-based levels for practicing web application hacking. Fully free.

#### 🟡 Intermediate
- **[pwn.college](https://pwn.college/)** (Arizona State University) — Free worldwide. Material is split into ordered "dojos," from Intro to Cybersecurity through Program Security and System Security. Assumes some C and OS familiarity.
- **[W3Challs](https://w3challs.com/)** — Hacking, wargame, forensics, crypto, stego and programming challenges aimed at feeling realistic.
- **[247CTF](https://247ctf.com/)** — Always-on, learning-oriented environment: Web, Crypto, Networking, Reversing, Exploitation.
- **[RingZer0 CTF](https://ringzer0ctf.com/)** — 300+ exercises across Cryptography, Reverse Engineering, Binary Exploitation, Web, Coding, and jail escapes.
- **[Defend the Web](https://defendtheweb.net/)** — Interactive security platform covering multiple categories.
- **[TaipanByte CTF](https://ctf.taipanbyte.ru/)** — Web, pwn, crypto, reversing and misc challenges; interface is in Russian.
- **[Cyber CTF](https://www.cyberctf.org/en)** — Open-source labs (Network, AD, Web, Pwn, Crypto, Reverse, CI/CD) described as "free forever."

#### 🔴 Advanced
- **[SmashTheStack](https://www.smashthestack.org/main.html#wargames)** & **[IO NetGarage](http://io.netgarage.org/)** — IRC-coordinated wargame networks; both still maintained.
- **[echoCTF.RED](https://echoctf.red/)** — Running free since 2019, funded by donations; platform code is open source.
- **[Try2Hack](https://www.try2hack.nl/)** — One of the oldest challenge sites still standing.

</details>

<details>
<summary><h2>Linux, Systems & Privilege Escalation</h2></summary>

#### 🟢 Beginner
- **[OverTheWire — Bandit](https://overthewire.org/wargames/bandit/)** — Linux command-line fundamentals over SSH. The canonical starting point for the entire OverTheWire suite.
- **[Linux Journey](https://linuxjourney.com/)** — Linux command-line fundamentals as a structured course.
- **[CMD Challenge](https://cmdchallenge.com/)** — Browser-based Linux shell and command-line puzzles.

#### 🟡 Intermediate
- **[OverTheWire — Leviathan](https://overthewire.org/wargames/leviathan/)** — General Linux-based challenge solving.
- **[OverTheWire — Natas](https://overthewire.org/wargames/natas/)** — Web security, black-box style.
- **[OverTheWire — Krypton](https://overthewire.org/wargames/krypton/)** — Classical cryptography.
- **[OverTheWire — Narnia](https://overthewire.org/wargames/narnia/)** — Introductory binary exploitation.
- **[Exploit Education](https://exploit.education/)** — Free downloadable VMs: **Phoenix** (stack/heap/format-string, modern x86-64), **Nebula** (Linux privilege escalation), **Fusion** (advanced exploitation with mitigation bypasses).

#### 🔴 Advanced
- **[OverTheWire — Behemoth](https://overthewire.org/wargames/behemoth/)**, **[Utumno](https://overthewire.org/wargames/utumno/)**, **[Maze](https://overthewire.org/wargames/maze/)** — Progressively harder binary/system exploitation.
- **OverTheWire — Vortex, Semtex, Manpage, Drifter, FormulaOne** — Additional advanced wargames in the same family ([full list](https://overthewire.org/wargames/)).

</details>

<details>
<summary><h2>Web Application & API Security</h2></summary>

#### 🟢 Beginner
- **[Google XSS Game](https://xss-game.appspot.com/)** — Progressive, guided XSS challenges.
- **[Google Gruyere](https://google-gruyere.appspot.com/)** — XSS, CSRF, path traversal and information disclosure in a deliberately bug-ridden toy app.
- **[OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)** — Full vulnerable web app with a built-in challenge scoreboard; the most popular single OWASP training target.
- **[OWASP WebGoat](https://github.com/WebGoat/WebGoat)** — Guided lessons paired with vulnerable challenges, built to teach as you go.
- **[DVWA](https://github.com/digininja/DVWA)** (Damn Vulnerable Web Application) — The classic self-hosted vulnerable app: SQLi, XSS, command injection, file inclusion.
- **[bWAPP](https://sourceforge.net/projects/bwapp/)** — Deliberately vulnerable app covering a wide spread of common web flaws.

#### 🟡 Intermediate
- **[PortSwigger Web Security Academy](https://portswigger.net/web-security)** — 200+ free interactive labs on real target instances: SQLi, XSS, SSRF, request smuggling, prototype pollution, JWT flaws. The industry-standard free web security training.
- **[OWASP Mutillidae II](https://github.com/webpwnized/mutillidae-II)** — 40+ intentionally vulnerable scenarios.
- **[OWASP Security Shepherd](https://github.com/OWASP/SecurityShepherd)** — Web and mobile application security challenges.
- **[Webhacking.kr](https://webhacking.kr/)** — Long-running Korean platform: PHP flaws, SQLi, client-side bypasses.
- **[Lord of SQLi](https://los.rubiya.kr/)** — Dedicated entirely to SQL injection filter bypasses and logic flaws.
- **[APIsec University](https://au.apisec.ai/api-tools-and-resources)** — API security tools & resources.

#### 🔴 Advanced
- **[OWASP crAPI](https://github.com/OWASP/crAPI)** — API1–API10 vulnerabilities, authorization and business-logic flaws in a realistic API.
- **[Damn Vulnerable GraphQL Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application)** — GraphQL authorization, injection and information-disclosure challenges.
- **[Damn Vulnerable Web Sockets (DVWS)](https://github.com/interference-security/DVWS)** — WebSocket-specific security testing.

### All in One
- **[Vulnerable Web Applications Directory](https://vwad.owasp.org/)** — A comprehensive registry of known vulnerable web and mobile applications for legal security testing and training by OWASP.

</details>

<details>
<summary><h2>Binary Exploitation (Pwn) &amp; Reverse Engineering</h2></summary>

#### 🟢 Beginner
- **[pwnable.xyz](https://pwnable.xyz/)** — Explicitly tailored to beginners in C/C++ memory corruption.
- **[Microcorruption](https://microcorruption.com/)** — Browser-based MSP430 assembly reversing with a well-liked debugger interface; "lockpick" virtual devices.
- **[crackmes.one](https://crackmes.one/)** — The largest community crackme repository (Windows/Linux/macOS/Android), categorized by difficulty and architecture.

#### 🟡 Intermediate
- **[pwnable.kr](https://pwnable.kr/)** — Classic, highly-regarded wargame with Toddler's Bottle → Rookie → Specialist → Hacker tiers.
- **[ROP Emporium](https://ropemporium.com/)** — Isolates one return-oriented-programming technique per challenge across x86, x86_64, ARMv5, MIPS and AArch64.
- **[Nightmare](https://guyinatuxedo.github.io/nightmare/) ([repo](https://github.com/guyinatuxedo/nightmare))** — An intro course built around real past CTF challenges: C/assembly → tooling → beginner RE → overflows → ROP.
- **[Reversing.kr](http://reversing.kr/)** — Windows-focused cracking and reverse-engineering puzzles, including anti-debugging and unpacking.
- **[RPISEC Modern Binary Exploitation](https://github.com/RPISEC/MBE)** — Open university course on binary exploitation.

#### 🔴 Advanced
- **[pwnable.tw](https://pwnable.tw/)** — Harder than pwnable.kr; heap exploitation, custom format-string attacks, modern mitigation bypasses.
- **[how2heap](https://github.com/shellphish/how2heap)** (Shellphish) — Executable walkthroughs of glibc heap exploitation techniques (fastbin dup, unsafe unlink, house of force, etc.).
- **[FLARE-On](https://flare-on.com/)** (Mandiant) — The best-known annual single-player reverse engineering CTF; past years' binaries and official solutions stay archived.
- **[Pwn Adventure 3: Pwnie Island](https://pwnadventure.com/)** (Vector35) — A fully playable 3D MMO built to be hacked via reverse engineering, memory editing and DLL injection.
- **[challenges.re](http://challenges.re/)** — Standalone reverse engineering exercise set.
- **[MalwareTech's beginner malware reversing challenges](https://malwaretech.com/labs/)** — Introduces common malware-analysis techniques (despite the "beginner" name, assumes RE fundamentals).

</details>

<details>
<summary><h2>Cryptography</h2></summary>

#### 🟢 Beginner
- **[Cryptopals](https://cryptopals.com/)** — 8 sets of practical crypto challenges; Set 1 is approachable, later sets ramp up sharply (XOR/AES fundamentals → padding oracles → RSA implementation attacks).
- **OverTheWire — Krypton** — see [Linux, Systems & Privilege Escalation](#linux-systems--privilege-escalation).

#### 🟡 Intermediate
- **[CryptoHack](https://cryptohack.org/)** — Entirely free, donation-funded. Tracks: RSA, Diffie-Hellman, elliptic curves, hash functions, crypto-on-the-web, post-quantum. Includes a CTF Archive of runnable past challenges.

#### 🔴 Advanced
- **[MysteryTwister C3](https://mysterytwister.org/)** — Longer-running crypto challenge archive referenced by CryptoHack's own FAQ for deeper material.

</details>

<details>
<summary><h2>Digital Forensics, Blue Team &amp; SOC</h2></summary>

#### 🟢 Beginner
- **[Digital Corpora](https://digitalcorpora.org/)** — Free forensic disk images, memory dumps and network captures to practice against.
- **[NIST CFReDS](https://cfreds.nist.gov/)** — Official digital forensics reference datasets for evidence validation.

#### 🟡 Intermediate
- **[KC7 Cyber](https://www.kc7cyber.com/)** — Free-forever, realistic SOC investigations: log analysis, threat hunting, incident response. 40+ cases.
- **[MemLabs](https://github.com/stuxnet999/MemLabs)** — Open CTF-style memory forensics challenges built around Volatility.
- **[Malware-Traffic-Analysis.net](https://www.malware-traffic-analysis.net/)** — PCAP analysis and real malware traffic investigation sets.
- **[Magnet Forensics CTFs](https://www.magnetforensics.com/blog/magnet-weekly-ctf-2020-images-and-questions/)** — The Magnet Virtual Summit CTF and the Magnet Weekly CTF archive, each with its own write-up page.
- **[Splunk Boss of the SOC (BOTS) v3](https://github.com/splunk/botsv3)** — SIEM investigation dataset: network logs, Windows events, AWS activity.

#### 🔴 Advanced
- **[Honeynet Project Challenges](https://www.honeynet.org/challenges/)** — Historical malware-analysis and DFIR challenge datasets.
- **[BelkaCTF](https://belkasoft.com/ctf)**, **[Cellebrite CTF](https://ctf.cellebrite.com/)**, **[DEF CON Blue Team Village CTF](https://ctf.blueteamvillage.org/challenges)**, **[13Cubed's Linux Memory Forensics](https://cdn.13cubed.com/downloads/linux_challenge.zip)**, **[13Cubed's Windows Memory Forensics](https://cdn.13cubed.com/downloads/windows_challenge.zip)**, **[13Cubed's Mini Memory CTF](https://cdn.13cubed.com/downloads/mini_memory_ctf.zip)**, **[DFIR Madness](https://dfirmadness.com/category/labs/)** — Recurring free DFIR-focused CTF archives.

</details>

<details>
<summary><h2>OSINT</h2></summary>

#### 🟢 Beginner
- **[Sourcing.Games](https://sourcing.games/)** — Free gamified search challenges teaching query construction and pivoting.
- **[OSINT Dojo](https://osintdojo.com/)** — Structured challenges that rise in difficulty, created by Sinwindie.

#### 🟡 Intermediate
- **[Gralhix OSINT exercises](https://gralhix.com/list-of-osint-exercises/)** (Sofia Santos) — A well-regarded public list of OSINT exercises.
- **[linuskay/osint-challenges](https://github.com/linuskay/osint-challenges)** — Free, with attribution requested for public use.
- **[OSINT-FR CTF](https://ctf.challenge-osint.fr/login)** — Free OSINT CTF run by the OSINT-FR community; the same hub lists **@Quiztime** geolocation quizzes and **@Sector035** challenges, often based on real (sometimes short-lived) cases.

#### 🔴 Advanced
- **[Trace Labs](https://www.tracelabs.org/)** — Weekly OSINT challenges tied to real missing-persons search methodology, with write-ups and an active Discord. Some Search Party CTF events list a $0.00 ticket — confirm current pricing before registering.

</details>

<details>
<summary><h2>Active Directory &amp; Vulnerable VMs</h2></summary>

#### 🟢 Beginner
- **[VulnHub](https://www.vulnhub.com/)** — Massive archive of downloadable boot-to-root VMs, attacked from your own Kali VM. x86/AMD-focused — Apple Silicon Macs will struggle without extra setup.
- **[Metasploitable3](https://github.com/rapid7/metasploitable3)** (Rapid7) — Free vulnerable Linux/Windows VM, built via Packer/Vagrant. (Metasploitable2 is the older, simpler single-VM version, archived on SourceForge.)

#### 🟡 Intermediate

- **[DetectionLab](https://github.com/clong/DetectionLab)** (Chris Long) — Vagrant/Packer automation that spins up a small working AD domain (DC + Windows/Linux hosts) with logging pre-configured. Built for blue-team/detection practice, but it's a solid live AD target too — a natural step up from VulnHub/Metasploitable3 before tackling the full GOAD.
- **[HackMyVM](https://hackmyvm.eu/)** — Free, community-run VulnHub-style vulnerable VM host that's picked up a lot of the slack as VulnHub's upload pace has slowed. Mostly Linux, but includes some Windows/AD-adjacent boxes.

#### 🔴 Advanced
- **[GOAD — Game Of Active Directory](https://github.com/Orange-Cyberdefense/GOAD)** — Free, self-hosted AD lab ranging from a 2-VM MINILAB to the full 5-VM GOAD, plus NHA and DRACARYS scenarios. Uses free 180-day Windows evaluation VMs. Budget ~115 GB disk space.

> 📎 See also: [`funkmykali`](https://github.com/arif-offsec/funkmykali) — a zero-error Kali Linux setup script that installs every tool these labs require (BloodHound, Impacket, Certipy, evil-winrm, and more) in one command.

</details>

<details>
<summary><h2>Cloud Security</h2></summary>

> ⚠️ **Cost warning:** CloudGoat, CloudFoxable, AzureGoat, GCPGoat and similar projects are **free to download**, but deploying them against real AWS/Azure/GCP infrastructure can incur cloud provider charges. They are not guaranteed zero-cost to run.

#### AWS
🟢 Beginner — **[flaws.cloud](http://flaws.cloud/)** — Author-hosted AWS CTF with levels and built-in clues.
🟡 Intermediate — **[flaws2.cloud](http://flaws2.cloud/)** (adds attacker/defender paths) · **[The Big IAM Challenge](https://iamchallenge.wiz.io/)** (Wiz) — S3 bucket policies, role assumption, cross-account misconfigurations.
🔴 Advanced — **[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)** (Rhino Security Labs, Terraform-deployed scenarios) · **[CloudFoxable](https://github.com/BishopFox/CloudFoxable)** (Seth Art / Bishop Fox, self-hosted AWS CTF)

#### Azure
🔴 Advanced — **[Broken Azure](https://www.brokenazure.cloud/)** (deliberately misconfigured environment) · **[EntraGoat](https://github.com/Semperis/EntraGoat)** (Microsoft Entra ID scenarios) · **[AzureGoat](https://github.com/ine-labs/AzureGoat)** (INE Security — vulnerable Azure infrastructure & identity)

#### GCP
🔴 Advanced — **[GCPGoat](https://github.com/ine-labs/GCPGoat)** (INE Security) — Terraform-deployed vulnerable GCP infrastructure covering IAM, Storage Bucket, Cloud Functions and Compute Engine misconfigurations; black-box style with multiple escalation paths. Same cost caveat as the other *Goat projects above — free to deploy, but real GCP charges apply once you're past the free tier.

#### Multi-Cloud & Cloud-Native
🟡 Intermediate — **[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)** — 20+ Kubernetes attack-and-defense scenarios with a guided workbook. Free, MIT-licensed, self-hosted on K3s or any cloud cluster.
🔴 Advanced — **[Thunder CTF](https://thunder-ctf.cloud/)** (bring your own GCP account) — 6 levels of vulnerable GCP projects, from a Portland State University research paper on low-cost cloud security training.

</details>

<details>
<summary><h2>Mobile Security (Android / iOS)</h2></summary>

#### 🟢 Beginner
- **[DIVA Android](https://github.com/payatu/diva-android)** — Deliberately vulnerable Android app built for learning.
- **[InjuredAndroid](https://github.com/B3nac/InjuredAndroid)** — Android CTF-style challenges in a single app.

#### 🟡 Intermediate
- **[OWASP MASTG Hacking Playground](https://mas.owasp.org/)** — Vulnerable Android/iOS apps maintained alongside the Mobile Application Security Testing Guide.
- **[AndroGoat](https://github.com/satishpatnayak/AndroGoat)** — Android vulnerability challenges.
- **[InsecureBankv2](https://github.com/dineshshetty/Android-InsecureBankv2)** — Vulnerable Android banking app with backend.
- **[DVIA v2](https://github.com/prateek147/DVIA-v2)** — iOS application security challenges.
- **[iGoat-Swift](https://github.com/OWASP/iGoat-Swift)** — iOS security exercises.

#### 🔴 Advanced
- **[OWASP MAS Crackmes](https://mas.owasp.org/crackmes/)** — Downloadable Android APKs and iOS IPAs sorted by difficulty.

</details>

<details>
<summary><h2>Blockchain, Smart Contracts &amp; AI/LLM Security</h2></summary>

#### 🟢 Beginner
- **[Ethernaut](https://ethernaut.openzeppelin.com/)** (OpenZeppelin) — 30+ levels; the standard starter CTF for blockchain security.
- **[Gandalf](https://gandalf.lakera.ai/)** (Lakera) — Free 7-level prompt-injection CTF. A companion "Gandalf Agent Breaker" targets tool-using agents.

#### 🟡 Intermediate
- **[Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)** — Harder than Ethernaut; focused entirely on DeFi exploit patterns.
- **[EVM Puzzles](https://github.com/fvictorio/evm-puzzles)** — Bite-sized EVM bytecode puzzles.
- **[Crucible](https://crucible.dreadnode.io/)** (Dreadnode) — Free, open AI red-teaming environment; 65+ hosted challenges covering prompt injection, model fingerprinting, inversion and evasion.
- **[Prompt Airlines](https://promptairlines.com/)** (Wiz) — Prompt-injection scenario built around a fake airline chatbot.
- **[HackAPrompt](https://www.hackaprompt.com/)** — Public LLM prompt-injection playground.

#### 🔴 Advanced
- **[DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs)** — Reproductions of real, historical DeFi exploits for study.
- **[Paradigm CTF archives](https://ctf-archives.com/en/ctf/Paradigm)** — Past Paradigm CTF challenges published on GitHub for offline solving.
- **[Damn Vulnerable LLM Agent](https://github.com/ReversecLabs/damn-vulnerable-llm-agent)**, **WithSecure's [MyLLMBank](https://myllmbank.com/)** / **[MyLLMDoctor](https://myllmdoc.com/)**, **[Doublespeak](https://doublespeak.chat/#/)** — Additional free LLM/agent security CTFs.

</details>

<details>
<summary><h2>Hardware &amp; Embedded</h2></summary>

This category is inherently advanced — expect to need a logic analyzer, UART adapter, or emulator.

- **[BLE CTF](https://github.com/hackgnar/ble_ctf)** — Bluetooth Low Energy exploitation challenges.
- **[IoTGoat](https://github.com/scriptingxss/IoTGoat)** — Deliberately insecure OpenWrt-based firmware.
- **[Riscure RHme hardware CTFs](https://github.com/Keysight)** (2015–2018 archives) — Classic hardware-focused CTF challenge sets.
- **[CSAW Embedded Security Challenge](https://github.com/TrustworthyComputing/csaw_esc_2026)** archives — Past embedded-security CTF challenges from NYU's CSAW.

</details>

<details>
<summary><h2>CTF Archives &amp; Past Competitions</h2></summary>

- **[pwn.college CTF Archive](https://pwn.college/)** — 650+ past CTF challenges spanning over a decade, preconfigured in browser-based Docker sandboxes.
- **[Google CTF GitHub](https://github.com/google/google-ctf)** — Challenge source and infrastructure from Google CTF since 2017 (pwn, reversing, crypto, web, sandboxing, forensics). ⚠️ Deliberate vulnerabilities — never run on production infrastructure.
- **[Sajjadium's ctf-archives](https://github.com/sajjadium/ctf-archives)** — MIT-licensed source files pulled from many CTFs over many years.
- **[archive.ooo](https://archive.ooo/)** — A playable archive of many DEF CON CTF challenges (currently in beta; not every OOO challenge is included).
- **[SANS Holiday Hack Challenge](https://www.sans.org/mlp/holiday-hack-challenge/)** — Free game-style CTF released each holiday season, beginner warm-ups through expert puzzles. Archive goes back to 2010, and past years stay online.
- **[Hack-A-Sat challenge source](https://hackasat.com/learn/)** — Source for the Hack-A-Sat 4 qualifier and final challenges, published on GitHub.
- **[CTF-Archives](https://github.com/CTF-Archives/CTF_Archive_CN)** (Chinese GitHub organization) — Hosts `CTF_Archive_CN`, an archive of attachments from past competitions.
- **[ImaginaryCTF](https://imaginaryctf.org/)** — Regular, beginner-friendly CTFs with write-ups published afterward.

</details>

<details>
<summary><h2>Learning Guides, Field Manuals &amp; Curated Lists</h2></summary>

These point you *toward* other resources rather than hosting challenges themselves.

- **[Trail of Bits CTF Field Guide](https://trailofbits.github.io/ctf/)** — Free, open-source (CC-BY-SA-4.0) book on vulnerability discovery, exploit creation, toolkit building and operational tradecraft. Written in 2014 — some content is dated, but the fundamentals hold up.
- **[CTF101](https://ctf101.org/)** — Beginner handbook covering the basics, key techniques and strategy per category.
- **[CTF Wiki](https://ctf-wiki.org/)** — Large technique and resource hub, including many Chinese-language resources.
- **[HackTricks](https://book.hacktricks.xyz/)** — Large, constantly updated pentesting/CTF techniques wiki; its Windows/AD privilege-escalation and attack sections are some of the best free material available.
- **[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)** — Massive community-maintained collection of payloads and bypass techniques spanning nearly every category in this list.
- **[The Hacker Recipes](https://www.thehacker.recipes/)** — Narrower scope than HackTricks, but excellent and heavily focused on AD/Windows attack techniques.
- **[GTFOBins](https://gtfobins.github.io/)** / **[LOLBAS](https://lolbas-project.github.io/)** — The standard Linux and Windows "living off the land" privilege-escalation cheat sheets.
- **[awesome-ctf](https://github.com/apsdehal/awesome-ctf)** (apsdehal, and forks like c4pr1c3's) — Curated list of wargames, tools and tutorials.
- **[b01lers' welcome-to-ctf](https://github.com/b01lers/welcome-to-ctf)** — A starter path through Nightmare, CTF Wiki, how2heap, pwntools, Ghidra and practice sites.
- **[WeChall](https://www.wechall.net/)** — Long-running cross-site challenge index; tracks sites like RingZer0 and W3Challs with live challenge counts.
- **[Rawsec's Cybersecurity Inventory](https://inventory.raw.pm/)** — A large resource table tagging each challenge site as free or paid.
- **[OWASP Vulnerable Web Applications Directory](https://owasp.org/www-project-vulnerable-web-applications-directory/)** — Registry of known vulnerable web/mobile apps for legal testing.
- **[Awesome CloudSec Labs](https://github.com/iknowjason/Awesome-CloudSec-Labs)** — Directory of free AWS, Azure, GCP and Kubernetes security labs.
- **[CTFtime](https://ctftime.org/)** — The global CTF calendar: upcoming and past events, team rankings, and a huge community write-up archive. Start here if you want to join a **live** team CTF rather than an always-on archive.
- **YouTube channels** — John Hammond, LiveOverflow, ir0nstone, 13Cubed and IppSec are the most commonly recommended for CTF basics, web security, memory forensics, pwn and reverse engineering respectively.

</details>

---

## Freemium / Free-Tier Only

These are excellent platforms, but their **full catalogue is not free** — each has a meaningful paywall beyond a free tier or sample. Listed here instead of the main sections so the two are never confused.

| Platform | What's actually free |
|---|---|
| [TryHackMe](https://tryhackme.com/) | A rotating set of free rooms; most content requires a subscription |
| [Hack The Box](https://www.hackthebox.com/) | Starting Point machines + limited retired-machine access |
| [HTB Academy](https://academy.hackthebox.com/) | Some modules free; most require a paid tier |
| [Root-Me](https://www.root-me.org/) | Sources disagree — some call it free for public use with a paid "Pro" tier, others tag it fully paid. Verify current terms before relying on it. |
| [PentesterLab](https://pentesterlab.com/) | Roughly half the content is free; PRO tier is paid |
| [CyberDefenders](https://cyberdefenders.org/) | Free practice labs alongside paid labs |
| [Blue Team Labs Online](https://blueteamlabs.online/) | Free + paid challenges |
| [LetsDefend](https://letsdefend.io/) | Free + paid content |
| [Pwned Labs](https://pwnedlabs.io/) | Some free hosted scenarios; paid bootcamps |
| [OffSec Proving Grounds](https://www.offsec.com/labs/play/) | PG Play tier is free — 3 hrs/day on community (VulnHub-sourced) Linux machines, no payment info needed; PG Practice ($19/mo) adds unlimited time plus Windows machines |
| [CyberTalents](https://cybertalents.com/challenges) | Not all of its CTFs are free |

## Regional Platforms (pricing unverified)

Mentioned frequently in community lists, but we couldn't independently confirm current pricing — check before relying on these:

**China:** CTFHub · BugKu · XCTF Adworld · BUUCTF
**Korea:** Dreamhack
**Japan:** AlpacaHack
**Spain:** Atenea (CCN-CERT)

---

## A Note on Using These Responsibly

- Only attack targets you're explicitly authorized to test — the platform's own challenge infrastructure, or VMs/labs you run yourself.
- Run downloaded vulnerable VMs (VulnHub, GOAD, Metasploitable, etc.) on an **isolated/host-only network**, never bridged to your home or work network.
- Cloud-based labs (CloudGoat, AzureGoat, Thunder CTF, etc.) can incur real charges from your cloud provider — read each project's README before deploying.
- If you're setting up a Kali box to work through these, [`funkmykali`](https://github.com/arif-offsec/funkmykali) installs the tooling most of these categories need in one command.

---

## Contributing

Found a dead link, a platform that's gone freemium, or a great resource that's missing? See [CONTRIBUTING.md](CONTRIBUTING.md) — PRs are very welcome.

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md).

## Security

Found a malicious or hijacked link in this list? See [SECURITY.md](SECURITY.md) for how to report it privately.

## License

[MIT](LICENSE) — use freely, credit appreciated, contributions welcome.

---

<div align="center">
<b>Pick a tier. Start solving. 🚩</b><br><br>
<a href="https://github.com/arif-offsec/ctfvault">github.com/arif-offsec/ctfvault</a>
</div>
