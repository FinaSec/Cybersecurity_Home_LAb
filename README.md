# Cybersecurity Home Lab

**Francisca Tupkeyi | Windows hardening, security auditing, and vulnerability assessment**

## Overview

This repository documents my Windows 11 ARM home lab and a separate collection of guided Windows 7 security labs. The work covers virtual machine setup, authentication controls, logon auditing, vulnerability assessment, controlled exploitation testing, and firewall validation.

## Start here

| Work | Focus | Documentation |
| --- | --- | --- |
| Windows 11 hardening | Logon auditing and account lockout configuration | [Hardening walkthrough](windows-hardening/README.md) |
| Lab 3: Windows 7 assessment | Nessus results and MS17-010 finding review | [Assessment walkthrough](labs/windows7-security/03-nessus-assessment/README.md) |
| Lab 4: Exploitation testing | Controlled SMB testing and session validation | [Testing walkthrough](labs/windows7-security/04-exploitation-testing/README.md) |
| Lab 6: Firewall validation | Firewall rules and scan comparison | [Firewall walkthrough](labs/windows7-security/06-firewall-validation/README.md) |

[Windows 7 lab collection](labs/windows7-security/README.md)

## Windows 11 home lab

| Component | Configuration |
| --- | --- |
| Host | MacBook Air, Apple M3, 24 GB RAM |
| Host operating system | macOS Sequoia |
| Virtualization | VMware Fusion 25H2 for Apple Silicon |
| Guest | Windows 11 Pro ARM |
| Guest hostname | WIN11-LAB1 |

### Documented progress

- Installed Windows 11 and reached the desktop.
- Configured account lockout after five failed attempts, with a 15-minute lockout duration and a 15-minute counter reset.
- Enabled auditing of successful and failed logon attempts.

[Windows desktop evidence](screenshots/windows11-desktop.png) · [Account lockout evidence](screenshots/account-lockout-policy.png) · [Logon auditing evidence](screenshots/audit-logon-success-failure-enabled.png)

### Planned extensions

Use the configured auditing to review authentication events, test detection use cases, and practice incident investigations. These are development goals; completed work is linked above.

## Guided Windows 7 security labs

The Kali Linux and Windows 7 walkthroughs describe a separate training environment from the Windows 11 ARM setup. Each walkthrough records its observations, screenshots, and limitations.

## Complete security lab index

Labs 1, 2, and 5 are in my Metasploitable repository; Labs 3, 4, and 6 are in this repository. The numbering follows the training sequence.

| Lab | Walkthrough |
| --- | --- |
| 1 | [Samba exploitation](https://github.com/FinaSec/Metasploitable-Vulnerability-Assessment/tree/main/labs/01-samba-exploitation) |
| 2 | [Session and password auditing](https://github.com/FinaSec/Metasploitable-Vulnerability-Assessment/tree/main/labs/02-session-password-auditing) |
| 3 | [Windows 7 Nessus assessment](labs/windows7-security/03-nessus-assessment/README.md) |
| 4 | [Windows 7 exploitation testing](labs/windows7-security/04-exploitation-testing/README.md) |
| 5 | [Nikto and DVWA web scanning](https://github.com/FinaSec/Metasploitable-Vulnerability-Assessment/tree/main/labs/05-web-scanning-information-exposure) |
| 6 | [Windows Firewall validation](labs/windows7-security/06-firewall-validation/README.md) |

## Skills demonstrated

- Virtual machine setup and Windows security configuration
- Authentication policy and logon auditing
- Vulnerability finding review
- Controlled security testing and session validation
- Firewall rule validation through scan comparisons
- Technical documentation with supporting evidence
