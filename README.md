<h1 align="center">Santiago Agudelo</h1>
<p align="center">
  <b>Security Operations Analyst</b> · EDR &amp; Incident Response · Vulnerability Management · Microsoft Entra ID &amp; Intune · PowerShell Automation
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/santiago-agudelo-/">LinkedIn</a> ·
  <a href="mailto:santiagudero@outlook.com">santiagudero@outlook.com</a> ·
  Medellín, Colombia (Open to Remote, UTC-5) ·
  English C1 / Spanish Native
</p>

---

### About me

Security Operations Analyst with 5+ years in enterprise IT, progressing from infrastructure and service desk to identity and access management (IAM) and, since 2025, dedicated security operations. Every week I triage 20–40 EDR detections in **CrowdStrike Falcon** and **Microsoft Defender**, contain hosts with Real Time Response, remediate vulnerabilities within SLA, and help keep **1,000+ endpoints** patched and compliant across North America, LATAM, and Europe with **Intune**, **Entra ID**, **GoTo Resolve**, and **PowerShell**.

This is where I publish the tools and runbooks I build around that work. The tooling repositories include automated tests and CI, the PowerShell tools ship versioned releases, and all sample data is anonymized.

---

### Security tooling

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [**IR-Triage-Collector**](https://github.com/Santiago-Agudelo-R/IR-Triage-Collector) | Live-response collector for Windows endpoints (local, WinRM, CrowdStrike RTR, Defender Live Response): processes (`T1036.005` masquerading checks), TCP/UDP endpoints, persistence (`HKLM`/`HKCU`/`HKEY_USERS` Run keys, scheduled tasks, services, WMI subscriptions), DNS/ARP caches, logon sessions, and SHA256-hashed JSON evidence. | PowerShell · Pester · GitHub Actions |
| [**M365-Entra-Audit-Toolkit**](https://github.com/Santiago-Agudelo-R/M365-Entra-Audit-Toolkit) | Governance auditor for Microsoft 365, Entra ID, and Intune: stale guests, privileged roles (active, time-bound, and inactive PIM-eligible schedules with live MFA verification), Conditional Access scope/exclusions, high-risk OAuth app consents, device encryption, and license reclamation. | PowerShell · Microsoft Graph · Pester |
| [**Intune-Proactive-Remediations**](https://github.com/Santiago-Agudelo-R/Intune-Proactive-Remediations) | Detection and remediation script pairs for BitLocker key escrow (Event ID 845), SID-based local administrator hygiene (`es-CO`/multilingual & Entra ID role SIDs), evidence-safe VSS / Windows Update health, and Microsoft Defender sensor health. | PowerShell · Intune · Pester |
| [**Defender-Sentinel-KQL-Detections**](https://github.com/Santiago-Agudelo-R/Defender-Sentinel-KQL-Detections) | KQL hunting queries and Microsoft Sentinel analytic rule templates for Defender XDR and Sentinel (field queries and SC-200 lab rules), with automated schema, MITRE ATT&CK, and entity-mapping validation. | KQL · Sentinel YAML · Python · pytest |
| [**SecOps-Field-Playbooks**](https://github.com/Santiago-Agudelo-R/SecOps-Field-Playbooks) | Troubleshooting and RCA runbooks for Intune BitLocker escrow, hybrid AD replication, and EDR sensor health, plus clearly labeled self-directed lab runbooks (AWS Systems Manager, SentinelOne, M365 BEC/AiTM triage, vulnerability management). | Markdown · Intune · AD · EDR |

### Other projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [**physics-class-analyzer**](https://github.com/Santiago-Agudelo-R/physics-class-analyzer) | Pipeline that transcribes lectures and uses pluggable LLM providers to segment content, extract LaTeX formulas, and generate DOCX/PDF study guides, with an offline mock provider for cost-free testing. | Python · LLM APIs · Whisper · pytest |

---

### Technical focus

- **Security Operations & Incident Response:** CrowdStrike Falcon (detection triage, Real Time Response, host containment, Spotlight), Microsoft Defender for Endpoint, Defender Vulnerability Management, Mimecast, Barracuda, Defender for Office 365, CIS Benchmarks & NIST CSF.
- **Identity & Endpoint Management:** Microsoft Entra ID (Conditional Access, RBAC, access reviews), Active Directory, Group Policy (GPO), Microsoft Intune (compliance policies, security baselines, BitLocker), Microsoft 365 (Exchange Online, SharePoint, Teams).
- **Scripting & Automation:** PowerShell, Microsoft Graph API, Power Automate, Python, Pester, pytest, PSScriptAnalyzer, GitHub Actions CI.
- **Infrastructure & ITSM:** Windows 10/11 Enterprise, Windows Server, Linux, VMware vSphere, GoTo Resolve, Syncro, Freshservice, Autotask, SnipeIT, Cisco networking.

---

### Currently learning

- **Microsoft Sentinel and KQL** detection labs (SC-200 track)
- **AWS** (Systems Manager, IAM) and **SentinelOne** threat hunting in self-directed labs

---

### Certifications

Microsoft SC-900 · Mimecast Email Security (Advanced) · Anthropic Claude Platform 101 · Cisco CCNA I · Scrum Fundamentals Certified (SFC) · EF SET English C1 (70/100)
<br><sub>Full list on <a href="https://www.linkedin.com/in/santiago-agudelo-/">LinkedIn</a>.</sub>

---

### Development approach

I work with AI coding agents (Claude Code, Gemini, Google Antigravity) for design, refactoring, and review. I own the architecture decisions and verify every change with linting, unit tests, and CI.
