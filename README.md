# azure-rbac-security-lab
Built a hands-on Azure IAM lab to validate least privilege using Reader, Contributor, and Owner roles. Simulated over-permissioned access risks, tested enforcement boundaries, and documented governance recommendations.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Objectives
- Understand Azure RBAC role tiers
- Test privilege boundaries
- Demonstrate least privilege
- Identify misconfiguration risks
- Improve cloud governance skills

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Environment
- Microsoft Entra ID
- Azure Subscription
- Azure Resource Groups
- Azure RBAC
- Test Users

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Roles Tested
Role | Expected Access	| Risk
Reader |	View only |	Recon
Contributor	| Modify resources |	Abuse
Owner	| Full admin |	Critical

<img width="1405" height="650" alt="image" src="https://github.com/user-attachments/assets/df9c8255-5a79-4e85-b7ec-efc9a037c7fe" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Key Validation
Reader: Cannot Create Resource Group

<img width="594" height="293" alt="image" src="https://github.com/user-attachments/assets/e6cad49d-077e-4fa8-9583-a0d8ae8fa949" />

Contributor: Can Modify Resources
Owner: Has Full Control


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Security Findings
- Too many Owners create governance risk
- Contributor can still be dangerous
- Least privilege must be enforced
- Role reviews should occur regularly

Improvements
- Azure PIM
- Conditional Access
- Azure Policy
- Logging alerts
- Just-in-time admin access

  Skills Demonstrated

Azure • IAM • RBAC • Governance • Cloud Security • Least Privilege




