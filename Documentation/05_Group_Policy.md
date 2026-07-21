# Group Policy



## Overview



Group Policy was used to manage security settings and user restrictions across the domain. A baseline security policy was created for the domain, and additional policies were applied to specific Organizational Units to meet different department requirements.



---



## Configuration



- Created a Baseline Security Policy

- Configured password and account lockout policies

- Created department-specific Group Policies

- Applied Administrative Template settings

- Updated Group Policy using `gpupdate /force`

- Verified that the policies were applied successfully



---



## Screenshots



### Group Policy Management



![Group Policy Management](../Screenshots/05%20-%20Group%20Policy/01_Group_Policy_Management.png)



The Group Policy Management console displays the domain and the available Group Policy Objects.



---



### Baseline Security Policy



![Baseline Security Policy](../Screenshots/05%20-%20Group%20Policy/02_Baseline_Security_Policy.png)



A Baseline Security Policy was created to apply common security settings across the domain.



---



### Password Policy



![Password Policy](../Screenshots/05%20-%20Group%20Policy/03_Password_Policy.png)



The password policy was configured to enforce password complexity, password history, password age, and minimum password length.



---



### Account Lockout Policy



![Account Lockout Policy](../Screenshots/05%20-%20Group%20Policy/04_Account_Lockout_Policy.png)



The account lockout policy was configured to lock user accounts after multiple failed sign-in attempts.



---



### IT Security Policy



![IT Security Policy](../Screenshots/05%20-%20Group%20Policy/05_IT_Security_Policy_Linked.png)



The IT Security Policy was linked to the IT Organizational Unit so that it applies only to the IT department.



---



### IT Security Policy Settings



![IT Security Policy Settings](../Screenshots/05%20-%20Group%20Policy/06_IT_Security_Policy_Settings.png)



Administrative Template settings were configured to restrict access to tools such as Command Prompt and Registry Editor.



---



### Control Panel Policy



![Control Panel Policy](../Screenshots/05%20-%20Group%20Policy/07_Control_Panel_Policy.png)



A policy was configured to prevent users from accessing Control Panel and PC Settings.



---



### Group Policy Update



![Group Policy Update](../Screenshots/05%20-%20Group%20Policy/08_GPUpdate_Force.png)



`gpupdate /force` was run to apply the latest Group Policy changes immediately.



---



### HR Department Policy



![HR Department Policy](../Screenshots/05%20-%20Group%20Policy/09_HR_Department_Policy_Settings.png)



The HR department policy contains settings that apply only to users in the HR Organizational Unit.



---



### Finance Department Policy



![Finance Department Policy](../Screenshots/05%20-%20Group%20Policy/10_Finance_Department_Policy_Settings.png)



The Finance department policy contains settings that apply only to users in the Finance Organizational Unit.



---



### First Logon Password Change



![First Logon Password Change](../Screenshots/05%20-%20Group%20Policy/11_First_Logon_Password_Reset.png)



When a newly created user signs in for the first time, Windows requires the user to change the password before continuing. This confirms that the password policy is being applied successfully.

