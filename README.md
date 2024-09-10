<h1>Azure User Defined Routes</h1>

<h2>Description</h2>
This lab will configure user defined routes.<br /><br />

Azure Bastion is a fully managed Platform as a Service (PaaS) offering from Microsoft Azure that provides secure and seamless RDP and SSH connectivity to your virtual machines (VMs) directly from the Azure portal. It eliminates the need to expose VMs to the public internet or to maintain jump servers or bastion hosts in your virtual network.
<br /><br />
Azure Bastion acts as a bridge between your virtual network and the Azure management portal, allowing you to securely connect to your VMs over Remote Desktop Protocol (RDP) or Secure Shell (SSH) directly within the Azure portal interface, without the need for a public IP address on the VMs or VPN connections. This enhances security by reducing exposure to the public internet and simplifies remote access management for administrators.
<br /><br />
Key features of Azure Bastion include:
<br /><br />
<b>Secure Access:</b> Azure Bastion provides secure and seamless RDP and SSH access to your VMs in Azure without exposing them to the public internet.<br />
<b>Fully Managed Service:</b> Azure Bastion is a fully managed PaaS offering, eliminating the need for you to manage bastion hosts or jump servers in your virtual network.<br />
<b>Integrated Experience:</b> You can access your VMs using RDP or SSH directly from the Azure portal interface, providing a centralized and streamlined management experience.<br />
<b>Zero Public IP Requirement:</b> VMs do not require a public IP address for RDP or SSH access, reducing the attack surface and simplifying network security.
<br />
<br />
Overall, Azure Bastion simplifies and enhances the security of remote access to VMs in Azure, providing a convenient and secure way for administrators to manage their virtual infrastructure.



<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Topology</h4>
Below, we have created a VM. This VM has no public IP address. Ware going to use Azure to log onto the VM<br/>
<img src="https://i.imgur.com/bhbcrm3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Step 1</h4> 
Create a Bastion subnet.<br/>
<img src="https://i.imgur.com/M5MkGaP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h4>Step 3</h4> 

<h4>Step 2</h4> 
Configure Bastion.<br/>
<img src="https://i.imgur.com/YnUlt3I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h4>Step 3</h4>

<h4>Step 3</h4> 
Log into the VM.<br/>
<img src="https://i.imgur.com/tmw9F3Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Vtbz3yY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
