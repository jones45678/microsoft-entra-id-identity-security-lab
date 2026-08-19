Microsoft Entra ID Identity & Security Lab

This lab provided hands-on experience with user management, authentication troubleshooting, and access control using Microsoft Entra ID.

Objectives:

Create and manage user accounts and groups
Assign roles and permissions
Configure Multi-Factor Authentication (MFA)
Implement Conditional Access Policies
Analyze sign-in logs for troubleshooting
Simulate basic security incident investigation
Users Created:

John Carter (IT admin)
Marcus Hill (SOC Team)
Sarah Lee (Finance)
David Kim (Contractor)
Groups Created:

Help Desk
SOC-Team
Finance
Contractors
Each group was assigned to reflect the

Security Configuration:

Configured MFA to strengthen account security for administrative users and reduce the risk of unauthorized access.
Implemented two Conditional Access policies based on identity and security requirements: Require MFA for Admins & Block Legacy Authentication.
Troubleshooting & Log Analysis:

Performed investigation of authentication events using sign-in logs, including:

Failed login attempts
Incorrect password entries
Location and IP address
Basic access troubleshooting
Failed Authentication Attempt Incident Simulation:

Multiple login attempts were detected for a user due to incorrect credentials. The event was analyzed using sign in logs and was investigated for further risk.

Outcome:

No account compromise detected.
Activity classified as a password-related issue.
MFA and access controls helped protect account security.
This project demonstrated practical experience in IT support fundamentals, authentication security and administrative troubleshooting tasks commonly used in professional IT environments.

Screenshots

The screenshots are organized in the /screenshots folder. Captions below describe what each shoows:

All Users View: The Entra ID user shows the four lab accounts (David Kim, John Carter, Marcus Hill, Sarah Lee) with assigned roles.

All Groups View: The Security Groups created for the lab (Contractor, Finance, Help Desk, SOC Team) with object IDs.
MFA Overview: MFA configuration for the tenant.

Conditional Access policy list: Two user-created policies: "Block Legacy Authentication" and "Require MFA for Admins".

Marcus Hill sign-in logs - These logs show the failed sign-in attempts used in the incident simulation.

Incident Report: A written summary of the failed authentication investigation, including event details and resolution.

<img width="1276" height="828" alt="unnamed" src="https://github.com/user-attachments/assets/55ddd920-38ac-4d7f-af53-847d198c3d84" />
<img width="1280" height="831" alt="image" src="https://github.com/user-attachments/assets/0016ad92-d3cc-46d1-b60d-d0d5052856a2" />
<img width="1280" height="405" alt="image" src="https://github.com/user-attachments/assets/4d23ac8c-efa0-4aca-8110-3acd2a9ad9ab" />
<img width="1280" height="405" alt="image" src="https://github.com/user-attachments/assets/95f87513-8a33-4e4b-b77f-be3ed6fe8194" />
<img width="1280" height="831" alt="image" src="https://github.com/user-attachments/assets/e5b992e9-8593-4a5b-a703-f638c0686dfc" />
<img width="1268" height="823" alt="image" src="https://github.com/user-attachments/assets/e2abcc2b-c353-44b8-8a82-7848f531bfa8" />
<img width="1280" height="405" alt="image" src="https://github.com/user-attachments/assets/3d4d3392-80da-4c0a-9a17-ca5327ae3f7a" />


