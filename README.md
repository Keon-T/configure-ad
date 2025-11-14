# configure-ad
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

- Virtual Network and Subnet
- Domain controller vm (windows server 2022)
- Azure Portal
- PowerShell

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/dIhy0ea.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Create resource group as active directory and virtual machine joining with domain controller VM (windows server 2022) named dc-1'and set NIC private IP address to static then create the following client virtual machines (windows 10) named "client-1"
</p>
<br />

<p>
<img src="https://i.imgur.com/zeHeKxe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Change DNS settings and the NIC to point to DC-1 IP private IP -address from virtual machine pasting to client-1 network settings ip address to dns server
</p>
<br />

<p>
<img src="https://i.imgur.com/ASSjIMe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to client-1  attempt to ping dc private IP address from virtual machine and open powershell and pasting IP address then enter to ping
<br />
