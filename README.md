<div align="center">

<img src="assets/jammie-logo.png" width="170" alt="JAMMIE — Cyber Threat Hunter">

<h1>iamjammie</h1>

<strong>INTELLIGENCE&nbsp;·&nbsp;HUNTING&nbsp;·&nbsp;RESILIENCE</strong>

<p>Threat hunter &amp; blue-team practitioner — building open-source, offline, MITRE&nbsp;ATT&amp;CK-mapped tooling and knowledge.</p>

<p>
<a href="https://iamjammie.github.io/FluxHunt/suite.html"><strong>▶&nbsp;The&nbsp;Hunt&nbsp;suite</strong></a> ·
<a href="https://iamjammie.github.io/hunt-sage/">Hunt-Sage&nbsp;site</a> ·
<a href="#-projects">All&nbsp;projects</a>
</p>

</div>

---

## 🧰 Projects

Ten open-source projects that share one approach — offline-first, auditable and built for defenders. Every repository links back to the others, so you can move from any tool to the next step of the hunt.

**Jump to:** [Hunt suite](#-the-hunt-suite) · [Detection & intelligence](#-detection--intelligence) · [Frameworks & air-gap tools](#-frameworks--air-gap-tools) · [Learning resources](#-learning-resources)

### 🎯 The Hunt suite

*Learn it, then hunt the wire, the box, the fleet and the directory — all mapped to the same ATT&CK techniques.*

| | Project | What it is |
|---|---|---|
| 🧠 | **[Hunt-Sage](https://github.com/iamjammie/hunt-sage)** | The one-stop **threat-hunting knowledge hub** — theory, 25 playbooks (KQL + SPL), 6 scenario hunt packs, 43 ATT&CK-mapped Sigma rules, a playbook finder, cheat sheets, labs and a blue-team CTF. [Site →](https://iamjammie.github.io/hunt-sage/) |
| 🌊 | **[FluxHunt](https://github.com/iamjammie/FluxHunt)** | *Hunting threats through traffic patterns* — a single-file, fully offline **PCAP analysis & IR** workbench in the browser. 35+ ATT&CK-mapped detectors, attack map, object export, reports. [Live demo →](https://iamjammie.github.io/FluxHunt/) |
| 🖥️ | **[HostHunt](https://github.com/iamjammie/HostHunt)** | *Hunting threats through host artefacts* — a dependency-free Python **host/endpoint triage** tool. 43 ATT&CK-mapped rules, live Windows/Linux collectors, IOC sweep, fleet stacking, HTML/JSON/Markdown reports. |
| 📡 | **[HostVigil](https://github.com/iamjammie/HostVigil)** | *Air-gapped workload security for Windows fleets* — a Rust agent streams process, flow, file, registry and logon telemetry over mTLS to a Linux server that correlates it, scores risk and renders a mission-control HUD. Signed offline CVE, Sigma and YARA feeds; nothing phones home. |
| 🔐 | **[ADHuntX](https://github.com/iamjammie/ADHuntX)** | *Hunting threats through directory exposure* — a single-file, fully offline **Active Directory security assessment & attack-path** analyzer in the browser. 35 ATT&CK-mapped rules, ACL/DACL analysis, PingCastle-style scoring, BloodHound-style attack graph, and a read-only PowerShell collector. |

### 🧭 Detection & intelligence

*Know what you can detect, how the frameworks connect, and what is coming.*

| | Project | What it is |
|---|---|---|
| 🎯 | **[Sentinel Matrix](https://github.com/iamjammie/Sentinel-Matrix)** | *See the Gaps. Engineer the Defence. Detect the Adversary.* — an offline-first, single-file **SIEM detection-coverage and rule-audit** workbench. Imports Sigma, Splunk, QRadar, Elastic and Sentinel rules, scores ATT&CK coverage, prioritises gaps and generates and validates new detections. |
| 🧬 | **[TTP NEXUS](https://github.com/iamjammie/TTP-Nexus)** | *Connecting Tactics. Decoding Threats. Enabling Defence.* — a single-file, offline-first **frameworks portal** unifying MITRE ATT&CK, D3FEND, CAPEC, CWE/CVE, the Cyber Kill Chain and pentest methodologies, with confidence-tagged mappings, a knowledge graph, learning paths and STIX 2.1 export. [Live demo →](https://iamjammie.github.io/TTP-Nexus/) |
| 🛡️ | **[ThreatIntFlux](https://github.com/iamjammie/ThreatIntFlux)** | *The Edge Before Engagement* — an offline-first **threat-intelligence console** with a public-feed collector (CISA KEV, NVD, abuse.ch, AlienVault OTX) and a schema validator. Every item carries a trust tier; built-in data is labelled SAMPLE. |

### 🧪 Frameworks & air-gap tools

| | Project | What it is |
|---|---|---|
| 🛰️ | **[SPECTRA](https://github.com/iamjammie/SPECTRA---Space-Cyber-Framework)** | A mission-first **space-systems cyber** assessment framework built around attack-path state transitions (Mission → Exposure → … → Resilience). |
| 🔦 | **[Photonwire](https://github.com/iamjammie/PhotonWire)** | *Offline file transfer across an air gap, by screen and camera* — two self-contained HTML files: the isolated machine shows a file as a loop of QR codes, a phone reads it back, verifies the SHA-256 and shares it. Own QR encoder/decoder, zero network. |

### 🔁 How they fit together

```text
Hunt-Sage ──▶ HostHunt · HostVigil ──▶ FluxHunt ──▶ ADHuntX ──▶ Sentinel Matrix
hypothesis    host and fleet           wire         directory    close the detection gap
```

TTP NEXUS and ThreatIntFlux supply the framework and intelligence context at every step; Photonwire carries the results out of an air-gapped network.

> 🔗 See the tools and knowledge together on the **[Hunt suite hub](https://iamjammie.github.io/FluxHunt/suite.html)** — from the wire, to the box, to the fleet, to the directory, to the playbook.

### 📚 Learning resources

Community training material kept as forks: **[ICDFA Open Labs](https://github.com/iamjammie/ICDFA-Open-Labs)** (cybersecurity and digital-forensics labs) · **[Beginner's Cyber Security Awareness](https://github.com/iamjammie/The-Beginners-2024-Cyber-Security-Awareness-Training-Course)** (introductory course).

---

## 🛡️ Focus Areas

`Threat Hunting` · `Detection Engineering` · `Incident Response` · `MITRE ATT&CK` · `SIEM/EDR` · `Blue Team`

---

## 📊 Latest from Hunt-Sage

<!-- These update when you publish new posts -->
- 📝 [Hunting Persistence: Every Place an Attacker Can Survive a Reboot](https://iamjammie.github.io/hunt-sage/blog/hunting-persistence)
- 📝 [Hunting C2 Beaconing: Finding the Heartbeat in Your Network Traffic](https://iamjammie.github.io/hunt-sage/blog/hunting-c2-beaconing)
- 📝 [Case Study: The Argon Dynamics Data Spill](https://iamjammie.github.io/hunt-sage/blog/argon-dynamics-case-study)
- 🚩 [CTF: Argon Nexus Challenge](https://iamjammie.github.io/hunt-sage/ctf/argon-nexus/)

---

## 📬 Connect

[![Hunt-Sage](https://img.shields.io/badge/Hunt--Sage-Visit-00B4D8?style=flat)](https://iamjammie.github.io/hunt-sage/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/iamjammie)
