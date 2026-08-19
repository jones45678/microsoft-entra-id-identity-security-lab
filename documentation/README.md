Microsoft Entra ID Identity & Security Lab

This lab provided hands-on experience with user management, authentication troubleshooting, and access control using Microsoft Entra ID. 

Objectives: 
- Create and manage user accounts and groups
- Assign roles and permissions
- Configure Multi-Factor Authentication (MFA)
- Implement Conditional Access Policies
- Analyze sign-in logs for troubleshooting
- Simulate basic security incident investigation

Users Created: 
- John Carter (IT admin)
- Marcus Hill (SOC Team)
- Sarah Lee (Finance)
- David Kim (Contractor)

Groups Created: 
- Help Desk
- SOC-Team
- Finance
- Contractors

Each group was assigned to reflect the 

Security Configuration: 
- Configured MFA to strengthen account security for administrative users and reduce the risk of unauthorized access.
- Implemented two Conditional Access policies based on identity and security requirements: Require MFA for Admins & Block Legacy Authentication.

Troubleshooting & Log Analysis: 

Performed investigation of authentication events using sign-in logs, including: 
- Failed login attempts
- Incorrect password entries
- Location and IP address
- Basic access troubleshooting

Failed Authentication Attempt Incident Simulation: 

Multiple login attempts were detected for a user due to incorrect credentials. The event was analyzed using sign in logs and was investigated for further risk. 

Outcome: 
- No account compromise detected.
- Activity classified as a password-related issue.
- MFA and access controls helped protect account security.

This project demonstrated practical experience in IT support fundamentals, authentication security and administrative troubleshooting tasks commonly used in professional IT environments. 


Screenshots

The screenshots are organized in the /screenshots folder. Captions below describe what each shoows:
1. All Users View: The Entra ID user shows the four lab accounts (David Kim, John Carter, Marcus Hill, Sarah Lee) with assigned roles.
2. All Groups View: The Security Groups created for the lab (Contractor, Finance, Help Desk, SOC Team) with object IDs.
3. MFA Overview: MFA configuration for the tenant.
4. Conditional Access policy list: Two user-created policies: "Block Legacy Authentication" and "Require MFA for Admins".
5. Marcus Hill sign-in logs - These logs show the failed sign-in attempts used in the incident simulation.
6. Incident Report: A written summary of the failed authentication investigation, including event details and resolution. 
