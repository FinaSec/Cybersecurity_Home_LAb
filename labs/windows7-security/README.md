# Windows 7 Security Lab Collection

**Francisca Tupkeyi | Guided security lab work**

[Back to home lab](../../README.md)

This collection documents vulnerability assessment, controlled exploitation testing, and firewall validation using Windows 7 and Kali Linux in a training environment. The walkthroughs were adapted from my lab records, with selected screenshots and evidence-based descriptions. No scans or exploitation were performed during publication.

| Walkthrough | Objective | Recorded result |
| --- | --- | --- |
| [Lab 3: Nessus assessment](03-nessus-assessment/README.md) | Identify exposed services and review SMB findings | 32 scanner entries; MS17-010 finding reviewed |
| [Lab 4: Exploitation testing](04-exploitation-testing/README.md) | Validate exploitability and inspect a session | Meterpreter session, system information, and test keystroke output |
| [Lab 6: Firewall validation](06-firewall-validation/README.md) | Compare external scan visibility after firewall changes | Later scans show three informational entries |

## Recorded environment

- Windows 7 target: `172.16.1.111`
- Kali callback address in exploitation evidence: `172.16.1.108`
- Nessus interface shown at `172.16.1.110:8834`
- Tools: Nessus Essentials Plus, Metasploit Framework, Windows Firewall, Windows command prompt

These are separate recorded sessions. Their numbering organizes the collection and does not establish a single uninterrupted scan-to-exploit timeline. The Windows 7 VM is a historical training target, separate from the Windows 11 ARM home lab.

## Evidence handling

Identical duplicate uploads of Labs 3 and 4 were excluded. Selected original screenshot images were extracted without changing terminal output. Classroom prompts were replaced by objectives, observations, results, and limitations. Raw PDFs, payloads, and extracted credentials are not distributed here.
