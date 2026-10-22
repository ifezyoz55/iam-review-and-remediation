# 06 — Remediation and Preventive Controls
Project: Northwind Health | IAM Access Review  
Document Reference: IAM-DOC-06-RP  
Version: 1.0  
Status: Draft — Portfolio Case Study   
Assessment Date: 5 October 2026  
Classification: Public — Fictional Data  

# 1. Remediation Plan
The following actions address the identified access risks while protecting business operations and sensitive healthcare information.

| Review ID | Account | Priority | Remediation Action |
|---|---|---|---|
| IAM-AR-001 | `treyes` | Immediate | Verify contract extension and account status. Review post-contract activity; revoke unauthorized access and preserve logs. |
| IAM-AR-002 | `skim` | High | Confirm account status and post-termination activity. Revoke unauthorized access and review relevant logs. |
| IAM-AR-003 | `testadmin` | High | Identify the account owner and business purpose. Disable safely if no legitimate need exists. |
| IAM-AR-004 | `support-shared` | Medium | Migrate users to individual accounts, remove the credential from the wiki, and rotate or revoke it after migration. |
| IAM-AR-005 | `dholt` | Review Required | Validate administrative access and approval. Reduce privileges if they exceed business requirements. |
| IAM-AR-006 | `pnair` | Routine Validation | Confirm the business need for Read-only access and retain it if appropriate. |
| IAM-AR-007 | `lgrant` | Routine Validation | Check the leave policy and expected access arrangements before making changes. |

## 2. Preventive Controls

| Control Area | Recommended Improvement | Business Benefit |
|---|---|---|
| Identity Lifecycle | Automate provisioning, role changes, contractor expiry, and deprovisioning. | Prevents unnecessary access and offboarding delays. |
| Access Governance | Enforce least privilege, approvals, and periodic access reviews. | Reduces excessive access and business risk. |
| Privileged Accounts | Require named owners, MFA, logging, and documented business justification. | Limits the impact of account compromise. |
| Account Security | Replace shared accounts with individual accounts and store credentials securely. | Improves accountability and credential protection. |

# 3. Remediation Verification
| Verification Step | Evidence Required |
|---|---|
| Access Revoked or Modified | Updated account status and role assignment. |
| Suspicious Activity Investigated | Relevant audit logs and documented review outcome. |
| Ownership Confirmed | Named owner and approved business purpose. |
| Shared Credentials Retired | Individual accounts created and old credentials invalidated. |
| Preventive Control Implemented | Documented procedure, approval record, or review evidence. |

---
Next Document: 07-iam-access-review-workflow.md
