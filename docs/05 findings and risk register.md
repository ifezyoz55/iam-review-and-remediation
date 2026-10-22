# 05 — Findings and Risk Register
**Project:** Northwind Health | IAM Access Review  
**Document Reference:** IAM-DOC-05-RR  
**Version:** 1.0  
**Status:** Draft — Portfolio Case Study  
**Assessment Date:** 5 October 2026    
**Classification:** Public — Fictional Data  

---
# 1. Risk Register
| Review ID | Account | Finding | Severity | Potential Business Impact |
|---|---|---|---|---|
| IAM-AR-001 | `treyes` | Admin access and recorded login after contract expiry. | **Critical** | Potential unauthorized access to sensitive data or administrative functions. |
| IAM-AR-002 | `skim` | Recorded login after employment termination. | **High** | Potential unauthorized access to internal systems and information. |
| IAM-AR-003 | `testadmin` | Admin account with unverified ownership and business purpose. | **High** | Unnecessary privileged access and reduced accountability. |
| IAM-AR-004 | `support-shared` | Shared credentials stored in the team wiki. | **Medium** | Credential misuse and difficulty attributing activity to individuals. |
| IAM-AR-005 | `dholt` | Admin privileges require business justification. | **Review Required** | Excessive permissions could increase the impact of account compromise. |

# 2. Recommended Risk Treatment
| Review ID | Account | Recommended Action |
|---|---|---|
| IAM-AR-001 | `treyes` | Verify contract extension, account status, and activity. Revoke unauthorized access and preserve relevant logs. |
| IAM-AR-002 | `skim` | Verify account status and post-termination activity. Revoke unauthorized access if confirmed. |
| IAM-AR-003 | `testadmin` | Confirm ownership and business need. Disable safely if the account is unnecessary. |
| IAM-AR-004 | `support-shared` | Migrate users to individual accounts, remove the credential from the wiki, and rotate or revoke it after migration. |
| IAM-AR-005 | `dholt` | Validate approval and business need; reduce privileges if unjustified. |

# 3. Accounts Requiring Validation
| Review ID | Account | Assessment | Follow-up |
|---|---|---|---|
| IAM-AR-006 | `pnair` | No confirmed issue | Validate business need and Read-only permissions. |
| IAM-AR-007 | `lgrant` | No confirmed issue | Check the leave policy before changing access. |

# 4. Business Impact
These gaps could expose sensitive data and make accountability harder. 
We should first investigate former staff accounts and Admin access without a clear business need.

---
Next Document: 06-remediation-and-preventive-controls.md
