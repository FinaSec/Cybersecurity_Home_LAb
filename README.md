# Cybersecurity Home Lab

## Overview
This repository documents the design and implementation of a cybersecurity home lab
built to develop practical skills in Security Operations (SOC), log analysis, detection
engineering, and incident response.

## Objectives
- Practice analyzing security logs
- Build and test detection use cases
- Simulate basic attack scenarios
- Perform incident response investigations

## Environment
- Host OS: macOS Sequoia
- Hardware: MacBook Air (Apple M3, 24 GB RAM)
- Hypervisor: VMware Fusion (Apple Silicon)

## Status
- GitHub repository initialized
- VMware Fusion 25H2 installed and configured
- Windows 11 Pro ARM VM created
- Hostname set to WIN11-LAB1
- Windows installation completed and desktop reached
- Windows hardening in progress (auditing configuration)
Account lockout policy configured (5 failed attempts, 15-minute lockout, 15 Reset lockout counter, and Enable Amin account lockout )

## Guided Security Labs

These walkthroughs document a separate Kali Linux and Windows 7 training environment. They are distinct from the Windows 11 ARM home lab described above.

| Lab | Focus | Documentation |
| --- | --- | --- |
| Lab 3 | Nessus assessment and MS17-010 finding review | [Windows 7 vulnerability assessment](labs/windows7-security/03-nessus-assessment/README.md) |
| Lab 4 | Controlled SMB exploitation and session validation | [Windows 7 exploitation testing](labs/windows7-security/04-exploitation-testing/README.md) |
| Lab 6 | Windows Firewall rules and scan comparison | [Firewall exposure reduction](labs/windows7-security/06-firewall-validation/README.md) |

[Windows 7 lab collection](labs/windows7-security/README.md) · [Metasploitable assessment and exploitation labs](https://github.com/FinaSec/Metasploitable-Vulnerability-Assessment)
