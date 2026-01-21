# Security Controls Cheat Sheet (Security+ SY0-701)

## 1) Control Categories (Type)
| Category | What it means | Examples |
|---|---|---|
| Administrative | Policies/process/people controls | Security policy, background checks, awareness training, change management |
| Technical (Logical) | Technology controls | MFA, firewall rules, EDR, encryption, ACLs |
| Physical | Protects buildings/hardware | Locks, badges, guards, cameras, mantraps |

---

## 2) Control Functions
| Function | What it does | Examples |
|---|---|---|
| Preventive | Stops an incident from happening | MFA, least privilege, secure configs, patching |
| Detective | Identifies an incident happening/has happened | IDS alerts, SIEM correlation, log monitoring |
| Corrective | Fixes after something happens | Reimage host, remove malware, restore configs |
| Deterrent | Discourages attacks | Warning banners, visible cameras, security patrols |
| Compensating | Alternative control when you can’t use the ideal one | Extra monitoring when MFA isn’t possible |
| Recovery | Restores systems/data | Backups, DR site, snapshots, restore procedures |
| Directive | Tells users what to do / sets rules | Policies, standards, SOPs, guidelines |

---

## 3) “Exam Trap” Quick Rules
- **MFA** = Technical + Preventive (usually)  
- **Logging/SIEM** = Technical + Detective  
- **Policies** = Administrative + Directive  
- **Backups** = Technical + Recovery  
- **Guards/Locks** = Physical + Preventive/Deterrent  

---

## 4) Practice: classify these controls
Fill this in yourself:

| Control | Type | Function |
|---|---|---|
| Security awareness training | Administrative | Directive |
| EDR (endpoint detection & response) | Technical | Detective |
| CCTV cameras | Physical | Detective |
| Daily backups | Technical | Recovery |
| Firewall rule blocking inbound SMB | Technical | Preventing |
| Incident response playbook | Administrative | Directive |

