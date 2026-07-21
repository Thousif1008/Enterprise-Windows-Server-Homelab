# Server Setup



## Overview



The first stage of the project was preparing the Windows Server 2022 machine that would be used as the domain controller. After installing the operating system, the required server roles were installed using Server Manager.



Active Directory Domain Services (AD DS) and DNS Server were installed because they provide the core services required for a Windows domain. AD DS manages users, computers, and authentication, while DNS enables devices to locate and communicate with domain services.



With both roles installed, the server was ready to be promoted to a domain controller in the next stage of the deployment.



---



## Installed Roles



- Active Directory Domain Services (AD DS)

- DNS Server



---



## Screenshot



### AD DS and DNS Roles Installed



![AD DS and DNS Roles Installed](../Screenshots/01%20-%20Server%20Setup/01_AD_DS_DNS_Roles_Installed.png)



The Server Manager dashboard shows that the Active Directory Domain Services and DNS Server roles have been installed successfully. These roles provide the foundation for the Active Directory environment that is configured throughout the rest of the project.

