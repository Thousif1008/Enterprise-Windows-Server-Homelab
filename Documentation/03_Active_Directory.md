\# Active Directory



\## Overview



Active Directory was configured to provide centralized management of users, computers, and resources across the lab environment. After creating the `thousiflab.com` domain, the default Active Directory structure was verified before building a custom Organizational Unit (OU) hierarchy.



The Organizational Units were created using PowerShell to automate the setup and maintain a consistent structure throughout the environment.



\---



\## Active Directory Configuration



\- Created the `thousiflab.com` Active Directory domain

\- Verified the default Active Directory structure

\- Created a custom Enterprise Organizational Unit hierarchy

\- Used PowerShell to automate OU creation

\- Verified that the Windows 11 client was registered in Active Directory



\---



\## Screenshots



\### Active Directory Domain



!\[Active Directory Domain](../Screenshots/03%20-%20Active%20Directory/01\_Active\_Directory\_Forest\_Created.png)



The Active Directory Users and Computers console shows the `thousiflab.com` domain after the server was promoted to a domain controller.



\---



\### Default Active Directory Structure



!\[Default Active Directory Structure](../Screenshots/03%20-%20Active%20Directory/02\_Default\_Active\_Directory\_Structure.png)



The default containers created by Active Directory are displayed, including \*\*Builtin\*\*, \*\*Computers\*\*, \*\*Domain Controllers\*\*, and \*\*Users\*\*.



\---



\### Organizational Units Created with PowerShell



!\[Organizational Units Created with PowerShell](../Screenshots/03%20-%20Active%20Directory/03\_Enterprise\_OUs\_Created\_PowerShell.png)



A PowerShell script was used to create the Enterprise Organizational Unit structure automatically. This approach keeps the deployment consistent and avoids creating each Organizational Unit manually.



\---



\### Enterprise Organizational Unit Structure



!\[Enterprise Organizational Unit Structure](../Screenshots/03%20-%20Active%20Directory/04\_Enterprise\_OU\_Structure.png)



The completed Organizational Unit hierarchy separates computers, groups, resources, and users into dedicated containers, making the environment easier to manage and prepare for Group Policy.



\---



\### Domain-Joined Computer



!\[Domain-Joined Computer](../Screenshots/03%20-%20Active%20Directory/05\_Client\_Computer\_Object.png)



After joining the Windows 11 client to the domain, its computer account appeared in Active Directory, confirming that the client was successfully registered with the domain.

