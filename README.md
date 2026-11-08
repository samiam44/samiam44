# <a href="https://www.linkedin.com/in/johnsamudio/">John Samudio</a>

<p align="center">
  <em>I learn how things break so I can help keep them whole.</em>
</p>

---

<div align="center">

![WGU M.S.](https://img.shields.io/badge/WGU_M.S.-Cybersecurity_%26_Information_Assurance_(In_Progress)-3FB0BF?style=flat-square&labelColor=0d1117)<br/>
![WGU B.S.](https://img.shields.io/badge/WGU_B.S.-Cybersecurity_%26_Information_Assurance-3FB0BF?style=flat-square&labelColor=0d1117)<br/>
![Certifications](https://img.shields.io/badge/Certifications-CEH_%7C_CySA%2B_%7C_Project%2B_%7C_ITIL_4-3FB0BF?style=flat-square&labelColor=0d1117)
![Cybersecurity Analyst Intern](https://img.shields.io/badge/Cybersecurity_Analyst_Intern-Log(N)_Pacific-3FB0BF?style=flat-square&labelColor=0d1117)

</div>

I love tackling complex problems through hands-on work, from building a vulnerability management program to hunting attackers through raw logs in Microsoft Sentinel. Every project here is something I built, broke, or investigated myself. Feel free to dig in.

---

## Projects

---

### 🔍 [Threat Hunt: PHP2Shell – The Hartwell Breach](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach)

[![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach)
[![KQL](https://img.shields.io/badge/KQL-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach)
[![Detection Engineering](https://img.shields.io/badge/Detection_Engineering-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach/tree/main/detections)

Hunted a web server compromise on the Log(N) Pacific cyber range from raw logs alone, solving all 18 flags. Traced the attacker from an Nmap scan through exploitation of PHP2Shell, a critical PHP flaw, to an encoded web shell hidden in a custom HTTP header, theft of database credentials and WordPress password hashes, a failed attempt to switch off Sysmon, auditd and Splunk, and cron persistence for an implant hidden in memory. The pivot: an administrator removed the web shell, and the attacker re-exploited the unpatched flaw 57 seconds later. Cleanup without patching changed nothing. Built the investigation in KQL across seven log sources (12 documented hunt queries), turned the findings into 4 detection rules, and documented every blind spot, including a 4-hour clock offset hiding in the Apache error log.

**[View Report →](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach)** &nbsp;|&nbsp; **[Detections →](https://github.com/samiam44/Threat-Hunt-Hartwell-Breach/tree/main/detections)**

---

### 🛡️ [Vulnerability Management Program](https://github.com/samiam44/Vulnerability-Management-Program)

[![Tenable Nessus](https://img.shields.io/badge/Tenable_Nessus-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Vulnerability-Management-Program)
[![Azure](https://img.shields.io/badge/Azure-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Vulnerability-Management-Program)
[![PowerShell](https://img.shields.io/badge/PowerShell-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Vulnerability-Management-Program)
[![Risk Management](https://img.shields.io/badge/Risk_Management-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Vulnerability-Management-Program)

Built a vulnerability management program end to end: drafted the policy, negotiated remediation timelines with the server team, ran authenticated Nessus scans, and pushed fixes through a change advisory board. The first remediation cycle cut total vulnerabilities by 81% (26 to 5), eliminated every critical finding, and reduced highs from 8 to 1.

**[View Program →](https://github.com/samiam44/Vulnerability-Management-Program)**

---

### ⚙️ [Windows 11 STIG Remediation](https://github.com/samiam44/Windows-11-STIG-Remediation)

[![Windows 11](https://img.shields.io/badge/Windows_11-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Windows-11-STIG-Remediation)
[![PowerShell](https://img.shields.io/badge/PowerShell-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Windows-11-STIG-Remediation)
[![DISA STIG](https://img.shields.io/badge/DISA_STIG-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Windows-11-STIG-Remediation)
[![Hardening](https://img.shields.io/badge/Hardening-3FB0BF?style=flat-square&labelColor=0d1117)](https://github.com/samiam44/Windows-11-STIG-Remediation)

Wrote PowerShell scripts that bring Windows 11 into compliance with DISA STIG controls across BitLocker, audit policy, account lockout and privilege escalation, including blocking non-admin users from installing elevated MSI packages.

**[View Scripts →](https://github.com/samiam44/Windows-11-STIG-Remediation)**

<!-- In progress, hidden until complete:
- **[Programmatic Vulnerability Remediations (PowerShell, BASH, & Shell Commands)](https://github.com/joshcybertest/programmatic-vulnerability-remediations)**
- **[Threat Hunting Scenario (Tor Browser Usage)](https://github.com/joshmadakor0/threat-hunting-scenario-tor)**
-->

---

## Currently Learning

![Threat Hunt Reporting](https://img.shields.io/badge/Threat_Hunt_Reporting-PEAK_%2F_TaHiTI-3FB0BF?style=flat-square&labelColor=0d1117)<br/>
![Cloud Security](https://img.shields.io/badge/Cloud_Security-WGU_D485-3FB0BF?style=flat-square&labelColor=0d1117)<br/>
![Cybersecurity Architecture & Engineering](https://img.shields.io/badge/Cybersecurity_Architecture_%26_Engineering-WGU%2C_up_next-3FB0BF?style=flat-square&labelColor=0d1117)<br/>
![CompTIA SecurityX](https://img.shields.io/badge/CompTIA_SecurityX-Exam_prep-3FB0BF?style=flat-square&labelColor=0d1117)

---

## Connect

💼 &nbsp;[LinkedIn](https://www.linkedin.com/in/johnsamudio/)
