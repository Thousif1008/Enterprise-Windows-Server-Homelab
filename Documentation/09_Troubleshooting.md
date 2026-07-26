## Troubleshooting



During the setup of this lab, I encountered several issues and resolved them as part of the deployment process.



- Reinstalled Windows 11 Home with Windows 11 Pro after discovering that the Home edition does not support joining an Active Directory domain.

- Resolved a domain join issue caused by the client's IPv6 configuration, which was using the ISP's domain settings instead of the Active Directory domain.

- Configured the virtual machine with the correct IP settings and switched the VMware network adapter from NAT to Bridged mode to restore internet connectivity.

- Enabled **Replicate physical network connection state** in VMware to maintain a stable network connection.

- Updated the PowerShell user import script to detect existing Active Directory accounts and skip duplicate users during bulk imports instead of generating errors.

