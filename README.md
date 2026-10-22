# IAM Review and Remediation — Northwind Health
A practical Identity and Access Management (IAM) case study focused on access reviews, least privilege, identity lifecycle management, and remediation in a fictional healthcare organization.

# Project Overview
Northwind Health is a fictional US healthcare SaaS organization supporting approximately 400 clinics. This project reviews five HR records against seven patient administration portal accounts to identify access discrepancies, assess potential risks, and recommend corrective and preventive controls.

| Attribute | Details |
|---|---|
| Focus | Identity and Access Management (IAM) |
| Organization | Northwind Health (fictional) |
| Assessment Date | 5 October 2026 |
| HR Records Reviewed | 5 |
| Portal Accounts Reviewed | 7 |
| Data | Fictional training records |
| Status | Portfolio case study |

# Key Areas of Review

- Identity lifecycle: Provisioning, role changes, and deprovisioning.
- Least privilege: Whether assigned permissions match business responsibilities.
- Privileged access: Administrative accounts, ownership, and justification.
- Accountability: Shared credentials and account ownership.
- Remediation: Prioritizing access risks and verifying corrective actions.

# Key Observations
| Account | Observation | Priority |
|---|---|---|
| `treyes` | Admin access and recorded login after contract expiry. | Critical |
| `skim` | Recorded login after employment termination. | High |
| `testadmin` | Admin account with unverified ownership and business purpose. | High |
| `support-shared` | Shared credentials stored in the team wiki. | Medium |
| `dholt` | Admin privileges require business justification. | Review required |

# Project Documentation
| Document | Description |
|---|---|
| 01 — Scenario and Scope | Business problem, objectives, and assessment boundaries. |
| 02 — Access Review Methodology | Review criteria, evidence validation, and risk assessment. |
| 03 — Identity and System Inventory | HR records, portal accounts, and identity reconciliation. |
| 04 — Access Review Results | Account-level observations and recommended actions. |
| 05 — Findings and Risk Register | Severity, potential business impact, and risk treatment. |
| 06 — Remediation and Preventive Controls | Corrective actions, preventive controls, and verification evidence. |
| 07 — Access Review Workflow | Visual workflow for reviewing and remediating access. |
| 08 — Executive Summary | Key findings, priorities, and management recommendations. |

# Expected Outcomes
The recommendations aim to strengthen identity lifecycle management, enforce least privilege, improve account accountability, and reduce the risk of unnecessary access to sensitive healthcare information.
