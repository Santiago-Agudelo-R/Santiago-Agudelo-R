<h1 align="center">Santiago Agudelo</h1>
<p align="center">
  <b>Security Operations Analyst</b> · EDR &amp; Incident Response · Microsoft Identity &amp; Intune · PowerShell &amp; Python Automation
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/santiago-agudelo-/">LinkedIn</a> ·
  <a href="mailto:santiagudero@outlook.com">santiagudero@outlook.com</a> ·
  Medellín, Colombia (Open to Remote) ·
  English C1 / Spanish Native
</p>

---

### About me

Security Operations Analyst with 5+ years of enterprise IT experience, including hands-on experience in endpoint security, incident response, vulnerability remediation, and security automation. Every week I triage EDR detections in **CrowdStrike Falcon** and **Microsoft Defender**, contain hosts with Real Time Response, remediate endpoint vulnerabilities, and help keep **1,000+ endpoints** patched and compliant across North America, LATAM, and Europe with **Intune**, **Entra ID**, and **PowerShell**.

This is where I publish the tools and runbooks I build around that work. The tooling repositories include automated tests and CI, the PowerShell tools ship versioned releases, and all sample data is anonymized.

---

### Security tooling

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [**IR-Triage-Collector**](https://github.com/Santiago-Agudelo-R/IR-Triage-Collector) | Live-response collector for Windows endpoints (local, WinRM, CrowdStrike RTR, Defender Live Response): processes, network connections, persistence (Run keys, scheduled tasks, services), Authenticode checks, and SHA256-hashed JSON evidence. | PowerShell · Pester · GitHub Actions |
| [**M365-Entra-Audit-Toolkit**](https://github.com/Santiago-Agudelo-R/M365-Entra-Audit-Toolkit) | Governance auditor for Microsoft 365, Entra ID, and Intune: stale guests, privileged roles with live PIM and MFA verification, Conditional Access posture, device encryption, and license reclamation. | PowerShell · Microsoft Graph · Pester |
| [**Intune-Proactive-Remediations**](https://github.com/Santiago-Agudelo-R/Intune-Proactive-Remediations) | Detection and remediation script pairs for BitLocker key escrow, local administrator hygiene, and VSS / Windows Update health. Safe by default and language-independent. | PowerShell · Intune · Pester |
| [**SecOps-Field-Playbooks**](https://github.com/Santiago-Agudelo-R/SecOps-Field-Playbooks) | Troubleshooting and RCA runbooks for Intune BitLocker escrow, hybrid AD replication, and EDR sensor health, plus clearly labeled self-directed lab runbooks (AWS Systems Manager, SentinelOne, M365 BEC/AiTM triage, vulnerability management). | Markdown · Intune · AD · EDR |

### Other projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [**physics-class-analyzer**](https://github.com/Santiago-Agudelo-R/physics-class-analyzer) | Pipeline that transcribes lectures and uses pluggable LLM providers to segment content, extract LaTeX formulas, and generate DOCX/PDF study guides, with an offline mock provider for cost-free testing. | Python · LLM APIs · Whisper · pytest |

---

### Technical focus

- **Security Operations:** CrowdStrike Falcon (EDR & Real Time Response), Microsoft Defender for Endpoint, incident triage, host containment, vulnerability remediation, Mimecast Email Security, CIS & NIST CSF.
- **Identity & Endpoint Management:** Microsoft Entra ID (PIM, Conditional Access), Active Directory, Microsoft Intune (compliance policies, BitLocker escrow, Proactive Remediations), Microsoft 365.
- **Automation & Engineering:** PowerShell, Python, Microsoft Graph API, Power Automate, Pester, pytest, PSScriptAnalyzer, GitHub Actions CI.
- **Infrastructure:** Windows 10/11 Enterprise, Windows Server, Linux, VMware vSphere, Cisco networking.

---

### Currently learning

- **Microsoft Sentinel and KQL** detection labs (SC-200 track)
- **AWS** (Systems Manager, IAM) and **SentinelOne** threat hunting in self-directed labs

---

### Certifications

Microsoft SC-900 · Anthropic Claude Platform 101 · Mimecast Email Security (Advanced) · Cisco CCNA I · EF SET English C1
<br><sub>Full list on <a href="https://www.linkedin.com/in/santiago-agudelo-/">LinkedIn</a>.</sub>

---

### Development approach

I work with AI coding agents (Claude Code, Gemini, Google Antigravity) for design, refactoring, and review. I own the architecture decisions and verify every change with linting, unit tests, and CI.
