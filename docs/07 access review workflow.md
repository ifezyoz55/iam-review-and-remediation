# 07 — Access Review Workflow
Project: Northwind Health | IAM Access Review  
Document Reference: IAM-DOC-07-WF  
Version: 1.0  
Status: Draft — Portfolio Case Study  
Assessment Date: 5 October 2026  
Classification: Public — Fictional Data  

# 1. Workflow Overview
This workflow shows how Northwind Health reviews user access, investigates risks, and verifies corrective actions.

# 2. Access Review Process

```mermaid
flowchart TD
    A([Start]) --> B[Collect HR and Portal Records]
    B --> C[Match Users and Accounts]
    C --> D[Review Roles and Permissions]
    D --> E{Is Access Appropriate?}
    E -->|Yes| F[Document Decision]
    E -->|Unclear| G[Investigate and Validate]
    G --> E
    E -->|No| H[Assess Risk and Business Impact]
    H --> I[Prioritize Remediation]
    I --> J[Correct or Revoke Access]
    J --> K[Verify Changes]
    K --> L[Record Evidence and Close Finding]
    F --> M([Review Complete])
    L --> M
```

    
  # 3. Key Control Points
  
| Control | Purpose |
|---|---|
| Identity Reconciliation | Match HR records against application accounts. |
| Access Validation | Confirm permissions match job responsibilities. |
| Risk Assessment | Prioritize issues by severity and business impact. |
| Remediation | Correct inappropriate or excessive access. |
| Verification | Confirm changes and retain supporting evidence. |

# 4. Expected Outcome
A consistent review process that reduces unnecessary access, improves accountability, 
and helps protect sensitive healthcare information.

---


Next Document: 08-executive-summary.md
