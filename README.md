# Active-Directory-Lab
## Description
This lab showcases Windows Server administration, identity management, DNS, Group Policy, and security controls. The purpose of this is to make a fully functional Windows Server Active Directory environment.
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
  
</ul>

### Employee Offboarding
<ul>
  
</ul>

### Department Transfer
<ul>
  
</ul>

### Account Lockout
<ul>
  
</ul>

### Password Reset
<ul>
  
</ul>

### DNS Troubleshooting
<ul>
  
</ul>
