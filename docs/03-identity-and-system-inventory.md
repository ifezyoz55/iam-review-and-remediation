# 03 — Identity and System Inventory
**Project:** Northwind Health | IAM Access Review  
**Document Reference:** IAM-DOC-03-IA  
**Version:** 1.0  
**Status:** Draft — Portfolio Case Study  
**Assessment Date:** 5 October 2026  
**Classification:** Public — Fictional Data  

# 1. Inventory Overview
The inventory compares five HR records against seven patient administration portal accounts to identify identity discrepancies,
access risks, and records requiring further validation.
# 2. HR Identity Inventory

|  Employee  |  ID  |  Employment Status  |  Department  |
|---|---|---|---|
|  Sarah Kim |  E1021  |  Terminated: 15 Aug 2026  | Customer Success|  
|  Tom Reyes |  C3004  |  Contractor: Ended 31 Jul 2026|  Engineering  |
|  Priya Nair  |  E1033  |  Active  |  Finance  |
|  Dan Holt  |  E1040  |  Active  | Engineering  |
|  Lisa Grant  |  E1052  |  Active; on leave since May  |  HR  |

# 3. Patient Administration Portal Inventory
| Username | Assigned Role | Last Login | Recorded Notes |
|---|---|---|---|
| `skim` | Support Agent | 2 Sep 2026 | — |
| `treyes` | Admin | 28 Sep 2026 | — |
| `pnair` | Read-only | 1 Oct 2026 | — |
| `dholt` | Admin | 2 Oct 2026 | — |
| `lgrant` | Support Agent | 11 May 2026 | — |
| `support-shared` | Support Agent | 3 Oct 2026 | Shared login; password stored in team wiki |
| `testadmin` | Admin | 20 Nov 2025 | Created by an engineer who has since left |

# 4. Identity Reconciliation
| Portal Account | HR Match | Initial Review Observation |
|---|---|---|
| `skim` | Sarah Kim (E1021) | Recorded login after termination date. |
| `treyes` | Tom Reyes (C3004) | Admin access and recorded login after contract end date. |
| `pnair` | Priya Nair (E1033) | Active employee; role requires business-need validation. |
| `dholt` | Dan Holt (E1040) | Active employee with Admin privileges requiring justification. |
| `lgrant` | Lisa Grant (E1052) | Employee on leave; access should be assessed against leave policy. |
| `support-shared` | No individual HR match | Shared account; ownership and access require investigation. |
| `testadmin` | No direct HR match | Admin account; current owner and business purpose require investigation. |

_Username-to-employee matches are provisional and should be verified against reliable identity records._

# 5. Inventory Observations
- Seven Portal accounts were matched with five HR records
- Two accounts require ownership investigation: support-shared and testadmin.
- Two matched accounts have recorded logins after an employment or contract end date.
- The available export does not establish whether any account is currently enabled.

# 6. Inventory Limitations
The supplied records do not include verified account status, complete permission details, access approvals, 
or full audit logs. Additional evidence is required to confirm authorization, current access, and potential misuse.

---
**Next Document:** 04-access-review-results.md







