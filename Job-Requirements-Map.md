# IAM Job Requirements Map

Project: Northwind Health | IAM Access Review  
Focus Area: Identity and Access Management | Identity Governance  

# 1. Project Overview

The Northwind Health IAM Access Review evaluates workforce identities and patient administration portal accounts to identify access discrepancies,
excessive privileges, and identity lifecycle weaknesses.

The project demonstrates how access reviews, risk assessment, and remediation planning can help protect sensitive healthcare information 
while keeping access aligned with business responsibilities.

# 2. IAM Responsibilities and Project Evidence

| IAM Responsibility | Project Application | Supporting Evidence |
|---|---|---|
| Identity reconciliation | Compared five HR records against seven portal accounts to identify discrepancies. | [Identity and System Inventory](docs/03-identity-and-system-inventory.md) |
| User access review | Evaluated seven accounts and documented review outcomes. | [Access Review Results](docs/04%20access%20review%20results.md) |
| Least-privilege access | Identified administrative privileges requiring business justification. | [Access Review Results](docs/04%20access%20review%20results.md) |
| Identity lifecycle management | Examined recorded logins after termination and contractor expiry. | [Scenario and Scope](docs/01%20scenario%20and%20scope.md) · [Remediation Plan](docs/06%20remediation%20and%20preventive%20controls.md) |
| Account governance | Identified shared credentials and accounts with unverified ownership. | [Findings and Risk Register](docs/05%20findings%20and%20risk%20register.md) |
| Risk assessment | Classified access concerns and considered potential business impact. | [Findings and Risk Register](docs/05%20findings%20and%20risk%20register.md) |
| Remediation planning | Recommended corrective actions, preventive controls, and verification evidence. | [Remediation and Preventive Controls](docs/06%20remediation%20and%20preventive%20controls.md) |
| IAM process documentation | Mapped the access review, investigation, and remediation process. | [Access Review Workflow](docs/07%20access%20review%20workflow.md) |
| Security reporting | Summarized the main findings, risks, and management priorities. | [Executive Summary](docs/08-executive-summary.md) |

# 3. Technical Competencies
# **Identity and Access Management**
- User access reviews and identity reconciliation.
- Provisioning, role changes, and deprovisioning.
- Least privilege and privileged-access assessment.
- Account ownership and access authorization.

#  Access Governance and Risk
- Identification of orphaned and shared-account risks.
- Evidence validation and risk classification.
- Business-impact assessment and remediation prioritization.
- Preventive control recommendations.

# Documentation and Reporting
- Identity and access inventory development.
- Risk register and remediation planning.
- Access review workflow documentation.
- Management-focused security reporting.

## 4. Business and Security Alignment

| Business Requirement | IAM Security Approach |
|---|---|
| Protect sensitive healthcare information | Review access appropriateness and excessive privileges. |
| Remove access when no longer required | Strengthen employee offboarding and contractor expiry processes. |
| Maintain accountability | Replace shared accounts with individually attributable access. |
| Reduce unnecessary privileges | Validate administrative access against business requirements. |
| Improve security oversight | Introduce regular access reviews and documented remediation. |
| Maintain business continuity | Validate access before changes and avoid unjustified account removal. |

## 5. Project Deliverables

| Deliverable | Description |
|---|---|
| [01 — Scenario and Scope](docs/01%20scenario%20and%20scope.md) | Business context, objectives, and assessment boundaries. |
| [02 — Access Review Methodology](docs/02%20access%20review%20methodology.md) | Review criteria, evidence validation, and risk assessment approach. |
| [03 — Identity and System Inventory](docs/03-identity-and-system-inventory.md) | HR records, portal accounts, and identity reconciliation. |
| [04 — Access Review Results](docs/04%20access%20review%20results.md) | Account-level findings and review decisions. |
| [05 — Findings and Risk Register](docs/05%20findings%20and%20risk%20register.md) | Access risks, severity, and potential business impact. |
| [06 — Remediation and Preventive Controls](docs/06%20remediation%20and%20preventive%20controls.md) | Corrective actions, preventive controls, and verification evidence. |
| [07 — Access Review Workflow](docs/07%20access%20review%20workflow.md) | Visual workflow for reviewing and remediating access. |
| [08 — Executive Summary](docs/08-executive-summary.md) | Key findings, priorities, and management recommendations. |

# 6. Project Outcome

The case study identified potential weaknesses involving post-employment access, privileged accounts, shared credentials, 
and access authorization.

The recommendations focus on strengthening identity lifecycle management, enforcing least privilege, improving account accountability, 
and prioritizing remediation according to potential security exposure and business impact.

# 7. Project Limitations

This project uses fictional organizational and account data. 
It demonstrates IAM analysis, access review, and remediation planning; it does not establish that a real security incident occurred or demonstrate production IAM administration.

Hands-on IAM platform administration and provisioning/deprovisioning automation remain areas for further development.



