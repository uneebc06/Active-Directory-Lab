# Active-Directory-Lab
## Description
This lab showcases Windows Server administration, identity management, DNS, Group Policy, and security controls. The purpose of this is to make a fully functional Windows Server Active Directory environment and a visual evidence of my knowledge and skills.
## Lab Architecture
<img src="Screenshots/1. Lab Architecture/VM Setting.png" width="50%" align=right>
<h3>Virtual Machines</h3>
Two VMs created on VMWare Workstation:<br><br>
<b>Windows Server 2019 - Domain Controller</b><br>
<ul><li>Static IP Address</li>
  <li>Active Directory Domain Services (AD DS)</li>
<li>DNS Server</li>
<li>Users, Organizational Units, Group Policy, etc.</li></ul>
    
<b>Windows 11 - Client</b>
<ul>
    <li>DHCP</li>
    <li>Joined to Active Directory domain</li></ul>
  
    
## Project Setup

### Creating The Domain


<ul>
<li>Rename computer</li>
  <li>Configure static IP address</li>
  <li>Configure DNS</li>
  <li>Install Active Directory Domain Services</li>
  <li>Promote from Standalone to Domain Controller</li>
  <li>Create a new forest as well as domain name</li>
</ul>
<div align=center>
<img src="Screenshots/2. Project Setup/1. Creating Domain/3. Static IP Assignment.png" width=30%>
<img src="Screenshots/2. Project Setup/1. Creating Domain/5. New Forest - Domain Promotion.png" width=32%>
<img src="Screenshots/2. Project Setup/1. Creating Domain/6. After Change.png" width=33%>
</div>


### Creating Organizational Units
<ul>
  <li>Create OUs</li>
  <li>Create users in OUs</li>
  <li>Create security groups</li>
  <li>Add members in security groups</li>
</ul>
<div align=center>
<img src="Screenshots/2. Project Setup/2. Creating OU's/3. User Creation Example.png" width=32%>
<img src="Screenshots/2. Project Setup/2. Creating OU's/5. Users In Security Groups.png" width=32%>
<img src="Screenshots/2. Project Setup/2. Creating OU's/6. After OU Changes.png" width=32%>
</div>


### Group Policy
<ul>
  <li>Password policy</li>
  <li>Account lockout policy</li>
  <li>RDP policies</li>
  <li>Windows Firewall settings</li>
</ul>
<div align=center>
<img src="Screenshots/2. Project Setup/3. Group Policy/1. GPO Creation.png" width=32%>
<img src="Screenshots/2. Project Setup/3. Group Policy/3. Password Policy SS.png" width=32%>
<img src="Screenshots/2. Project Setup/3. Group Policy/5. Account Lockout Policy SS.png" width=32%>
</div>

### Join Windows Client To Domain
<ul>
  <li>Setup DHCP server on Windows Server</li>
  <li>Configure DNS server to point to domain controller</li>
  <li>Change computer's domain on Windows System settings</li>
  <li>Login using account from domain</li>
</ul>
<div align=center>
<img src="Screenshots/2. Project Setup/4. Joining Windows 11 Client To Domain/1. DHCP Installation on Server.png" width=32%>
<img src="Screenshots/2. Project Setup/4. Joining Windows 11 Client To Domain/4. Account User.png" width=32%>
</div>


## Scenarios
### Employee Onboarding
<ul>
  <li>Create a user account</li>
  <li>Put it in the correct OU</li>
  <li>Add account to department security groups</li>
  <li>Configure initial password</li>
</ul>

[Watch how I did this](Screenshots/3.%20Project%20Scenarios/Employee%20Onboarding/Employee%20Onboarding.mp4)

### Employee Offboarding
<ul>
  <li>Disable user account</li>
  <li>Remove group memberships</li>
  <li>Move account to a disabled users OU</li>
</ul>

[Watch how I did this](Screenshots/3.ProjectScenarios/EmployeeOffboarding/EmployeeOffboarding.mp4)

### Department Transfer
<ul>
  <li>Change the user's OU</li>
  <li>remove old security groups</li>
  <li>Add new security groups</li>
</ul>

### Account Lockout
<ul>
  <li>Identify the locked account</li>
  <li>Unlock the account</li>
</ul>

[Watch how I did this](Screenshots/3.%20Project%20Scenarios/Account%20Lockout/Account%20Lockout.mp4)

### Password Reset
<ul>
  <li>Identify the account that needs a password reset</li>
  <li>Reset the password as admin</li>
  <li>Force a password change at next login</li>
</ul>

[Watch how I did this](Screenshots/3.%20Project%20Scenarios/Password%20Reset/Password%20Reset.mp4)

### DNS Troubleshooting
<ul>
  <li>Attempt to access the domain</li>
  <li>Use ipconfig, nslookup, and ping to diagnose the issue</li>
  <li>Restore the correct DNS configuration</li>
  <li>Verify domain authentication works again</li>
</ul>
