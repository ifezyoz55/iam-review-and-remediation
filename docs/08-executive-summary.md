# 08 — Executive Summary
Project: Northwind Health | IAM Access Review  
Document Reference: IAM-DOC-08-ES  
Version: 1.0  
Status: Draft — Portfolio Case Study  
Assessment Date: 5 October 2026    
Classification: Public — Fictional Data 

# 1. Overview
This assessment reviewed seven patient administration portal accounts against five HR records to identify access-control weaknesses and recommend improvements to identity lifecycle management.

# 2. Key Findings
| Account | Finding | Priority |
|---|---|---|
| `treyes` | Admin access and login after contract expiry. | Critical |
| `skim` | Login recorded after employment termination. | High |
| `testadmin` | Admin account with unverified ownership and business purpose. | High |
| `support-shared` | Shared credentials stored in the team wiki. | Medium |
| `dholt` | Admin privileges require business justification. | Review Required |

The accounts pnair and lgrant have no confirmed access issue based on the supplied records, 
but require routine validation.

# 3. Business Impact
These weaknesses could expose sensitive information, weaken accountability, 
and increase the risk of unauthorized access or operational disruption.

# 4. Recommendations
- Prioritize investigation of former personnel accounts with recorded post-employment activity.
- Enforce timely provisioning, role changes, and deprovisioning.
- Apply least privilege and validate administrative access.
- Replace shared accounts with individual identities and secure credential storage.
- Establish periodic access reviews and documented remediation verification.

# 5. Conclusion
The assessment highlights opportunities to strengthen access governance and reduce unnecessary access. 
Further validation is required before confirming account status, unauthorized activity, or exposure of electronic protected health information (ePHI).




