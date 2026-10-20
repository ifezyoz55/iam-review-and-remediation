# 02 — Access Review Methodology

**Project:** Northwind Health | IAM Access Review  
**Document Reference:** IAM-DOC-02-AM  
**Version:** 1.0  
**Status:** Draft — Portfolio Case Study  
**Assessment Date:** 5 October 2026  

---
# 1. Review Approach
The review reconciles five HR records against seven administration portal accounts to 
identify access discrepancies, excessive privileges, and identity lifecycle weaknesses.
# 2. Review Criteria
| Criteria | Assessment Focus |
|---|---|
| Employment Status | Termination dates, contract end dates, and account activity. |
| Least Privilege | Whether assigned roles match job responsibilities. |
| Privileged Access | Admin permissions, account ownership, and business justification. |
| Accountability | Shared credentials and accounts with unclear ownership. |
| Lifecycle Management | Provisioning, role changes, and timely deprovisioning. |

# 3. Risk Assessment
Findings are rated based on the available evidence, privilege level, potential security exposure, 
and business impact.

| Severity | Assessment Guidance |
|---|---|
| Critical | Potentially severe exposure requiring urgent investigation. |
| High | Significant access risk requiring prompt action. |
| Medium | Meaningful control weakness requiring remediation. |
| Low | Limited risk suitable for routine improvement. |

# 4. Evidence Validation
HR records, portal roles, last-login dates, and account notes provide the basis for the review. 
Where evidence is incomplete, further investigation is required before reaching a definitive conclusion.

A recorded login does not prove an account remains enabled or that ePHI was accessed. 
Likewise, administrative access is not automatically inappropriate without considering authorization 
and business need.

---

**Next Document:** 03-identity-and-system-inventory.md
