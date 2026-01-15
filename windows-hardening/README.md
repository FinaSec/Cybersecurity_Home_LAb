# Windows 11 Hardening and Auditing

## Objective
Configure Windows security auditing to support SOC-style monitoring,
incident detection, and investigation.

---

## Advanced Audit Policy Configuration

### Audit Logon Events

**Path**
Security Settings  
→ Advanced Audit Policy Configuration  
→ System Audit Policies  
→ Logon/Logoff  

**Configuration**
- Audit Logon: Enabled
  - Success
  - Failure

**Why this matters**
This configuration enables visibility into:
- Successful and failed logon attempts
- Brute-force authentication attempts
- Unauthorized access activity

**Evidence**
Screenshots stored in the screenshots folder.
