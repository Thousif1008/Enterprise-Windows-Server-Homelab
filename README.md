# Enterprise Windows Server 2022 Active Directory Homelab



A Windows Server 2022 Active Directory homelab built in VMware Workstation Pro with an enterprise-style Organizational Unit (OU) structure, PowerShell automation, Group Policy, and file sharing.



---



## Network Topology



![Network Topology](Network%20Diagram/Homelab-Network-Topology.png)



---



## Environment



| Component | Details |

|-----------|---------|

| Hypervisor | VMware Workstation Pro |

| Server | Windows Server 2022 |

| Domain Controller | DC01 |

| Client | Windows 11 |

| Domain | thousiflab.com |

| Network | VMnet0 (Bridged) |



---



## Project Structure



```text

Enterprise-Windows-Server-Homelab/

│

├── Documentation/

├── Network Diagram/

├── PowerShell/

├── Screenshots/

└── README.md

```



---



## Features



- Active Directory Domain Services (AD DS)

- DNS

- Organizational Units

- Security Groups

- Distribution Groups

- Bulk user provisioning

- Group Policy

- File sharing

- NTFS permissions

- Drive mapping

- Windows 11 domain join



---



## Documentation



- [01 - Server Setup](Documentation/01_Server_Setup.md)

- [02 - Network Configuration](Documentation/02_Network_Configuration.md)

- [03 - Active Directory](Documentation/03_Active_Directory.md)

- [04 - Users and Groups](Documentation/04_Users_and_Groups.md)

- [05 - Group Policy](Documentation/05_Group_Policy.md)

- [06 - File Server](Documentation/06_File_Server.md)

- [07 - Drive Mapping](Documentation/07_Drive_Mapping.md)

- [08 - Client Testing](Documentation/08_Client_Testing.md)

- [09 - Conclusion](Documentation/09_Conclusion.md)



---



## PowerShell



PowerShell scripts used during the deployment:



- Create Organizational Units

- Create Security Groups

- Import users from Excel



---



## Screenshots



### Server Manager



![AD DS and DNS Roles Installed](Screenshots/01%20-%20Server%20Setup/01_AD_DS_and_DNS_Roles_Installed.png)


---



### Active Directory



![Enterprise OU Structure](Screenshots/03%20-%20Active%20Directory/04_Enterprise_OU_Structure.png)


---



### Group Policy



![Group Policy](Screenshots/05%20-%20Group%20Policy/01_Group_Policy_Management.png)



---



### Windows 11 Client


![Domain User Login](Screenshots/08%20-%20Client%20Testing/05_Domain_User_Login.png)


---



## Technologies



- VMware Workstation Pro

- Windows Server 2022

- Windows 11

- Active Directory Domain Services

- DNS

- Group Policy

- PowerShell



---



## Notes



The **Documentation** folder contains the complete setup and validation for the project.

