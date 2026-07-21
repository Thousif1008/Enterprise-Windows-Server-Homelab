# Drive Mapping

## Overview

To simplify access to shared resources, a Drive Mapping preference was configured using Group Policy Preferences (GPP). When users in the IT department sign in, the shared folder is automatically mapped as drive **I:**, eliminating the need to manually connect to the network share.

---

## Configuration

The following settings were configured:

- Created a Drive Mapping preference in **Group Policy Preferences**.
- Configured the network path `\\DC01\IT`.
- Assigned the drive letter **I:**.
- Linked the Group Policy Object (GPO) to the **IT** Organizational Unit.
- Updated Group Policy and verified the configuration on a Windows 11 domain-joined client.

---

## Screenshots

### Group Policy Drive Mapping Configuration

![Drive Mapping Configuration](../Screenshots/07%20-%20Drive%20Mapping/01_Drive_Mapping_GPO.png)

The Drive Mapping preference was configured in the Group Policy Management Editor to map the shared folder `\\DC01\IT` as drive **I:** for users in the IT Organizational Unit.

---

### Drive Mapping Verification

![Mapped Network Drive](../Screenshots/07%20-%20Drive%20Mapping/02_Mapped_Drive_Client.png)

After signing in to the domain, the **IT Drive (I:)** appeared automatically in File Explorer under **Network locations**, confirming that the Drive Mapping preference was applied successfully.

---

## Result

The shared folder was automatically mapped for users in the IT department whenever they signed in. This confirmed that the Drive Mapping preference was configured correctly and working as expected on the Windows 11 client.