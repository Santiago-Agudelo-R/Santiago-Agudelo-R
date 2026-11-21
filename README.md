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

This is where I publish the tools and runbooks I build around that work. Every tooling repository runs linting and tests in GitHub Actions, follows semantic versioning with a changelog, and uses anonymized sample data.

---

### Security tooling

| Project | What it does | Engineering highlights | Stack |
| :--- | :--- | :--- | :--- |
| [**IR-Triage-Collector**](https://github.com/Santiago-Agudelo-R/IR-Triage-Collector) | Windows live-response collector for local runs, WinRM, CrowdStrike RTR and Defender Live Response: processes, network endpoints, persistence (Run keys for every user hive, tasks, services, WMI), DNS/ARP, logon sessions. | Reads offline user hives from a temporary copy so evidence is never loaded; UTC timestamps that survive non-US locales; SHA256 emitted to the RTR console for off-host verification. | PowerShell · Pester |
| [**M365-Entra-Audit-Toolkit**](https://github.com/Santiago-Agudelo-R/M365-Entra-Audit-Toolkit) | Microsoft Graph auditor for Entra ID, M365 and Intune: privileged roles with PIM and MFA, stale guests, Conditional Access gaps, risky app consents, license reclamation. | Reports PIM-eligible holders of never-activated roles; reviews application permissions of third-party apps, not only delegated grants; reports `Unknown` instead of guessing when telemetry is missing; CSV export hardened against formula injection. | PowerShell · Microsoft Graph · Pester |
| [**Intune-Proactive-Remediations**](https://github.com/Santiago-Agudelo-R/Intune-Proactive-Remediations) | Detection and remediation pairs for BitLocker key escrow, local administrator hygiene, VSS / Windows Update health and Defender sensor health. | Admin approval by SID scoped to the machine and your domain, so it works on Spanish Windows and resists name spoofing; detect and remediate share one function; report-only and evidence-safe by default. | PowerShell · Intune · Pester |
| [**Defender-Sentinel-KQL-Detections**](https://github.com/Santiago-Agudelo-R/Defender-Sentinel-KQL-Detections) | Six KQL rules for Defender XDR and Sentinel: Defender tampering, AiTM inbox rules, permanent Tier-0 roles, exploitable vulnerabilities, LSASS dumping, Key Vault secret harvesting. | Every query parsed in CI by Microsoft's Kusto engine against the documented table schemas; rules carry an honest `Experimental` / `Hunting` / `Tested` status. | KQL · Python · Node · GitHub Actions |
| [**SecOps-Field-Playbooks**](https://github.com/Santiago-Agudelo-R/SecOps-Field-Playbooks) | Troubleshooting and incident runbooks: Intune BitLocker escrow, hybrid AD replication, EDR sensor health, M365 BEC/AiTM, vulnerability management. | The incident playbooks (EDR containment, SentinelOne/Defender triage, BEC/AiTM) include SHA256 evidence hashing for chain of custody; field runbooks and self-directed lab runbooks are labeled separately. | Markdown · PowerShell · KQL |

### Other projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [**physics-class-analyzer**](https://github.com/Santiago-Agudelo-R/physics-class-analyzer) | Turns recorded university physics lectures into DOCX/PDF study guides: transcription, segmentation, LaTeX formula extraction and an HTML concept map, with pluggable LLM providers (Ollama, OpenAI-compatible) and an offline provider for testing. | Python · Whisper · LLM APIs · pytest |

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

I use AI coding assistants for drafting and refactoring. Every push runs PSScriptAnalyzer and Pester or pytest in GitHub Actions, and detection queries are parsed against Microsoft's documented table schemas. No customer data or production telemetry is ever shared with these tools, and I can walk through the reasoning behind any design choice in these repos.
