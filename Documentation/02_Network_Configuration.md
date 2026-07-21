\# Network Configuration



\## Overview



Before configuring Active Directory, the server was configured with a static network address. This ensures that clients and services can always locate the domain controller using the same IP address. DNS was also verified because Active Directory relies on DNS for domain name resolution.



\---



\## Configuration



\- IPv4 Address: `192.168.1.10`

\- Subnet Mask: `255.255.255.0`

\- Default Gateway: `192.168.1.1`

\- Preferred DNS Server: `127.0.0.1`



\---



\## Screenshots



\### Server IP Configuration



!\[Server IP Configuration](../Screenshots/02%20-%20Network%20Configuration/01\_Server\_IP\_Configuration.png)



The `ipconfig /all` output verifies the server's network configuration. DHCP is disabled, confirming that a static IPv4 address is being used. The output also shows the subnet mask, default gateway, and preferred DNS server configured for the domain controller.



\---



\### DNS Forward Lookup Zone



!\[DNS Forward Lookup Zone](../Screenshots/02%20-%20Network%20Configuration/02\_DNS\_Forward\_Lookup\_Zone.png)



The DNS Manager console shows the `thousiflab.com` forward lookup zone with the required DNS records created for the domain. These records allow domain-joined computers to resolve the domain controller by name, which is required for Active Directory services.

