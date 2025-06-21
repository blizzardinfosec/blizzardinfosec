# 🛡️ Blizzard InfoSec

**Welcome.** I'm a blue team security engineer focused on real-world detection, incident response, and automation. This GitHub serves as a growing library of high-signal, low-noise detection and response artifacts tailored for modern enterprise environments.

---

## 📂 Featured Projects

### 🧩 [sigma-rules-custom](https://github.com/blizzardinfosec/sigma-rules-custom)
Original Sigma rules authored and tuned for production use across a wide range of environments.

- ✅ Windows, macOS, Linux
- ☁️ AWS, Microsoft 365, Okta, Kubernetes
- 📦 Containers, SaaS, and physical security (e.g. Verkada, HID)
- 🧠 Mapped to MITRE ATT&CK with normalization guidance

### 🛡️ [edr-response-scripts](https://github.com/blizzardinfosec/edr-response-scripts)
Python scripts to automate host isolation, evidence collection, and containment across:

- Falcon (CrowdStrike)
- SentinelOne
- Microsoft Defender for Endpoint
- Kubernetes & Docker
- Linux/macOS live triage

### 📘 [incident-response-checklists](https://github.com/blizzardinfosec/incident-response-checklists)
Markdown-based IR playbooks designed for speed and clarity during real-world breaches.

- 📧 Business Email Compromise
- 💥 Ransomware
- ☁️ AWS / Okta / O365 / Kubernetes incidents
- 🔐 Host-level EDR triage

### 🧱 [log-source-onboarding](https://github.com/blizzardinfosec/log-source-onboarding)
Step-by-step onboarding guides and ECS normalization maps for:

- AWS CloudTrail, Okta, Office 365, Sysmon, Netskope
- CrowdStrike Falcon, Kubernetes Audit Logs, FleetDM
- Each guide focuses on visibility, mapping, and detection quality

---

## 🧠 Philosophy

This library favors **real-world coverage** over theoretical completeness. Everything here is:

- 🧩 Designed to be plugged into SIEM pipelines
- 📉 Tuned for low false positives
- 🔍 Built with threat-informed context
- 🛠️ Modular and reusable for blue team engineers

---

## 🚧 In Progress

This content is alive and growing. Future expansions include:

- ✅ More SaaS coverage (Atlassian, Zoom, GitHub)
- 🔧 Terraform detection CI/CD pipelines
- 🌐 Integration with Splunk, Datadog, CrowdStrike
- 🧪 Sigma rule test samples and ECS unit validation

---

## 👋 Contact

If you're a blue teamer looking to collaborate, discuss detections, or swap war stories—feel free to connect.

Built for defenders, by a defender.
