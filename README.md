# Active-Directory-Lab
## Description
This lab showcases Windows Server administration, identity management, DNS, Group Policy, and security controls. The purpose of this is to make a fully functional Windows Server Active Directory environment and a visual evidence of my knowledge and skills.
## Lab Architecture
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

### Creating Organizational Units
<ul>
  <li>Create users and groups</li>
  <li>Adding security groups</li>
</ul>

### Group Policy
<ul>
  <li>Password policy</li>
  <li>Account lockout policy</li>
  <li>Login restrictions</li>
  <li>Windows Firewall settings</li>
</ul>

### Join Windows Client To Domain
<ul>
  <li>Configure DNS server to point to domain controller</li>
  <li>Change computer's domain on Windows System settings</li>
  <li>Login using account from domain</li>
</ul>

## Scenarios
### Employee Onboarding
<ul>
  <li>Create a user account</li>
  <li>Put it in the correct OU</li>
  <li>Add account to department security groups</li>
  <li>Configure initial password</li>
</ul>

### Employee Offboarding
<ul>
  <li>Disable user account</li>
  <li>Remove group memberships</li>
  <li>Move account to a disabled users OU</li>
</ul>

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

### Password Reset
<ul>
  <li>Identify the account that needs a password reset</li>
  <li>Reset the password as admin</li>
  <li>Force a password change at next login</li>
</ul>

### DNS Troubleshooting
<ul>
  <li>Attempt to access the domain</li>
  <li>Use ipconfig, nslookup, and ping to diagnose the issue</li>
  <li>Restore the correct DNS configuration</li>
  <li>Verify domain authentication works again</li>
</ul>
