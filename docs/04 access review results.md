# 04 — Access Review Results
**Project:** Northwind Health | IAM Access Review  
**Document Reference:** IAM-DOC-04-AR  
**Version:** 1.0  
**Status:** Draft — Portfolio Case Study  
**Assessment Date:** 5 October 2026  
**Classification:** Public — Fictional Data  

# 1. Review Summary
The review identified potential risks involving post-employment logins, privileged access, shared credentials, and access authorization. 
Accounts were assessed using the supplied HR and portal records; unresolved issues require further validation.

# 2. Account Review Results
| Review ID | Account | Review Finding | Assessment | Recommended Action |
|---|---|---|---|---|
| IAM-AR-001 | `treyes` | Contract ended 31 July 2026; Admin role and login on 28 September. | **Critical — Investigate urgently** | Verify contract extension, account status, and post-contract activity. Revoke unauthorized access and preserve relevant logs. |
| IAM-AR-002 | `skim` | Employee terminated 15 August 2026; login on 2 September. | **High — Investigate** | Verify account status and post-termination activity. Disable unauthorized access and review logs. |
| IAM-AR-003 | `testadmin` | Admin account created by a former engineer; last login 20 November 2025. | **High — Investigate** | Confirm ownership, business purpose, account status, and dependencies before disabling or removing it. |
| IAM-AR-004 | `support-shared` | Shared Support Agent account; password stored in the team wiki. | **Medium — Remediate** | Migrate users to named accounts, remove the credential from the wiki, and rotate or revoke it after migration. |
| IAM-AR-005 | `dholt` | Active Engineering employee with Admin privileges; login on 2 October. | **Review required** | Validate business need, approval, MFA, and administrative logging. Reduce privileges if unjustified. |
| IAM-AR-006 | `pnair` | Active Finance employee with Read-only access; login on 1 October. | **No confirmed issue** | Validate business need and Read-only permissions. Retain access if appropriate. |
| IAM-AR-007 | `lgrant` | Active employee on leave since May; Support Agent role; last login 11 May. | **No confirmed issue** | Check the leave policy and expected access arrangements. Do not revoke access solely because the employee is on leave. |

# 3. Key Observations
- **Lifecycle management:** IAM-AR-001 and IAM-AR-002 have recorded logins after contract or employment end dates.  
- **Privileged access:** IAM-AR-001, IAM-AR-003, and IAM-AR-005 require investigation or justification of administrative access.  
- **Accountability:** IAM-AR-004 uses shared credentials stored in the team wiki.  
- **Access governance:** The supplied records do not establish whether all account permissions have documented approvals or periodic reviews.  

# 4. Priority Action
IAM-AR-001 —`treyes` is the priority investigation due to the expired contract, Admin privileges, and subsequent recorded login.

Confirm whether a contract extension was approved, whether the account remains enabled, and what activity occurred after the contract end date. 
Revoke access if it is unauthorized and preserve relevant logs.

---
**Next Document:** 05-findings-and-risk-register.md

