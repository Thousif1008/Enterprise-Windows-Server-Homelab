\# Enterprise Windows Server 2022 Active Directory Homelab



A Windows Server 2022 Active Directory homelab built in VMware Workstation Pro with an enterprise-style Organizational Unit (OU) structure, PowerShell automation, Group Policy, and file sharing.



\---



\## Network Topology



!\[Network Topology](Network%20Diagram/Homelab-Network-Topology.png)



\---



\## Environment



| Component | Details |

|-----------|---------|

| Hypervisor | VMware Workstation Pro |

| Server | Windows Server 2022 |

| Domain Controller | DC01 |

| Client | Windows 11 |

| Domain | thousiflab.com |

| Network | VMnet0 (Bridged) |



\---



\## Project Structure



```text

Enterprise-Windows-Server-Homelab/

│

├── Documentation/

├── Network Diagram/

├── PowerShell/

├── Screenshots/

└── README.md

```



\---



\## Features



\- Active Directory Domain Services (AD DS)

\- DNS

\- Organizational Units

\- Security Groups

\- Distribution Groups

\- Bulk user provisioning

\- Group Policy

\- File sharing

\- NTFS permissions

\- Drive mapping

\- Windows 11 domain join



\---



\## Documentation



\- \[01 - Server Setup](Documentation/01\_Server\_Setup.md)

\- \[02 - Network Configuration](Documentation/02\_Network\_Configuration.md)

\- \[03 - Active Directory](Documentation/03\_Active\_Directory.md)

\- \[04 - Users and Groups](Documentation/04\_Users\_and\_Groups.md)

\- \[05 - Group Policy](Documentation/05\_Group\_Policy.md)

\- \[06 - File Server](Documentation/06\_File\_Server.md)

\- \[07 - Drive Mapping](Documentation/07\_Drive\_Mapping.md)

\- \[08 - Client Testing](Documentation/08\_Client\_Testing.md)

\- \[09 - Conclusion](Documentation/09\_Conclusion.md)



\---



\## PowerShell



PowerShell scripts used during the deployment:



\- Create Organizational Units

\- Create Security Groups

\- Import users from Excel



\---



\## Screenshots



\### Server Manager



!\[Server Manager](Screenshots/01%20-%20Server%20Setup/01\_Server\_Manager.png)



\---



\### Active Directory



!\[Active Directory](Screenshots/03%20-%20Active%20Directory/04\_OU\_Hierarchy.png)



\---



\### Group Policy



!\[Group Policy](Screenshots/05%20-%20Group%20Policy/01\_Group\_Policy\_Management.png)



\---



\### Windows 11 Client



!\[Windows 11 Client](Screenshots/08%20-%20Client%20Testing/02\_Domain\_User\_Login.png)



\---



\## Technologies



\- VMware Workstation Pro

\- Windows Server 2022

\- Windows 11

\- Active Directory Domain Services

\- DNS

\- Group Policy

\- PowerShell



\---



\## Notes



The \*\*Documentation\*\* folder contains the complete setup and validation for the project.

