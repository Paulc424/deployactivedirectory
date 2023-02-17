

<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This step by step guide outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- First step will be to create a resource group and two seperate virtual machines within that resource group.
- After creating your two virtual machines and resource group, verify that both virtual machines are on the same network by going to Network Watcher>Topology
- From your remote desktop, download Wireshark. Once you have Wireshark installed, start it up and scan for ICMP traffic.

Depictions of Deployment and configuration steps
<p>
  
After creating your two virtual machines and resource group, verify that both virtual machines are both on the same network.

 
 <img src="https://i.imgur.com/INUuFR9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/tNMi7IV.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  
Log into your virtual machine using remote desktop and with the public IP address of your virtual machine.

  <img src="https://i.imgur.com/hE2Gpmk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

  <img src="https://i.imgur.com/RBt89Vq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  From your remote desktop, download Wireshark. Once you have Wireshark installed, start it up and scan for ICMP traffic.
<img src="https://i.imgur.com/0BjDIra.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
Once you have Wireshark installed, start it up and scan for ICMP traffic.
 
<img src="https://i.imgur.com/XYDwIOK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Open Windows Firewall with Advanced Security and go to enable rules, and enable 3 ICMP rules that are named "Core Networking".

<img src="https://i.imgur.com/1PTc75z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
To install Active Directory, click on the yellow exclamation point on top right corner and choose Active Directory Domain Services
</p>
<br />
<p>
<img src="https://i.imgur.com/2vTbefS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
<p>
<img src="https://imgur.com/a/E4MPR6b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<img src="https://i.imgur.com/DVZCx4p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
