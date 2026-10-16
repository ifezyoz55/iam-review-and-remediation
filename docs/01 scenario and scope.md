# 01 — Scenario and Scope

**Project:** Northwind Health | IAM Access Review  
**Document Reference:** IAM-DOC-01-SC  
**Version:** 1.0  
**Status:** Draft — Portfolio Case Study  
**Assessment Date:** 5 October 2026  
**Classification:** Public — Fictional Data

---
---
# 2. Project Overview
This project simulates an IAM access review for Northwind Health, a fictional healthcare SaaS company, to evaluate user access, identify security risks, and recommend remediation and preventive controls.
# 3. Organisation
| Project Attribute | Description |
|---|---|
| Organization | Northwind Health (fictional) |
| Industry | Healthcare Technology |
| Organization Size | Approximately 120 employees |
| Customer Base | Approximately 400 clinics |
| Primary Focus | Identity and Access Management |
| Assessment Status | In Development |
# 4. Business Problem
Northwind Health needs to ensure workforce access aligns with job responsibilities throughout the identity lifecycle. Gaps in provisioning, deprovisioning, least privilege, and access reviews could expose sensitive health data and create operational risks.

The assessment addresses four key questions:
|  Question  |  Assessment Focus  |
|---|---|
|  Who has access?  |  identify workforce identities, application accounts, roles, and account status.  |
|  Should they have access?  |  Evaluate permissions against employment status and documented job responsibilities. |
|  What needs attention?  |  identify excessive, inappropriate, shared, orphaned, or insufficiently justified access.  |
|  How do we prevent recurrence?  |  Recommend improvements to provisioning, access reviews, and offboarding.  |
## 5. Assessment Objectives

- Reconcile HR records with application accounts and assigned permissions.
- Identify excessive access, orphaned accounts, and provisioning/deprovisioning gaps.
- Evaluate least privilege, RBAC, and segregation of duties to reduce business risk.
- Prioritize remediation based on security risk, business impact, and protection of sensitive health data.
## 6. Scope of Review

The assessment covers seven patient administration portal accounts, reconciled against five HR records to evaluate access appropriateness and identity lifecycle management.

| Account | Review Focus |
|---|---|
| `skim` | Terminated employee account and potential residual access |
| `treyes` | Contractor account, Admin privileges, and contract end date |
| `testadmin` | Orphaned administrative account and account ownership |
| `support-shared` | Shared credentials and individual accountability |
| `lgrant` | Account access during extended employee leave |
| `pnair` | Finance user's access and business justification |
| `dholt` | Administrative privileges and least privilege |

# 7. Expected Deliverables

| Deliverable | Purpose |
|---|---|
| Identity & Access Inventory | Document users, accounts, roles, and permissions. |
| Access Review Results | Evaluate access appropriateness and document review decisions. |
| Findings & Risk Register | Record risks, business impact, severity, and evidence. |
| Remediation Plan | Define corrective actions, priorities, and verification. |
| IAM Workflow Diagram | Visualize the access review and remediation process. |
| Framework Mapping | Align recommendations with relevant security controls. |
| Executive Summary | Communicate key findings and priorities to management. |
