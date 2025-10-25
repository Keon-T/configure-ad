# configure-ad
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Virtual Network and Subnet
- -Domain controller vm (windows server 2022)
- Azure Portal
- PowerShell

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/dIhy0ea.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create resource group with virtual machine as active directory and join it in remote desktop

</p>
<br />

<p>
<img src="https://i.imgur.com/zeHeKxe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Pasting dc 1 private IP address changes it from Vnets and points to client-1 DNS for any searches within the computer

</p>
<br />

<p>
<img src="https://i.imgur.com/ASSjIMe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>From client one open up powershell and run (IP config all) for the DNS settings to show DC ones private IP address

<br />
