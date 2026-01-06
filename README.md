<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Windows Server Virtual Machine in Azure
- Install the Active Directory Domain Services (AD DS) Role
- Promote the server to a Domain Controller
- Configure networking and join devices to the domain

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/CFGUHgl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When runnimg Active Directory Domain Services(AD DS) on a Windows Server VM in Azure, compute reqirements are usually modest, but reliability is critical. We create a Virtual Machine (VM) in Azure for Active Directory (AD DS) because Active Directory requires a Windows Server operating system, and Azure VMs provide that server in trhe cloud.
</p>
<br />

<p>
<img src="https://i.imgur.com/qbWozsJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
PowerShell ISE is a graphical tool used to write, edit, test, and run Powershell scripts more easily than using the command line alone. Powershell ISE and Active Directory is commonly used to: Create users and groups, Reset passwords, Manage OUs, Query AD objects.
</p>
<br />

<p>
<img src="https://i.imgur.com/T2UyEJM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is where we can help our costumers to reset there passwords when locked out. For an example on how to use Powershell ISE. Step 1:Open PowerShell ISE, Step 2:Import the Active Directory Module, Step 3:Find the User (optional but recommended), Step 4:Reset the User Password, Step 5:Force User to Change Password at Next Login, Step 6:Unlock the Account (if Locked), Step 7:Verify the Account status.
</p>
<br />
