<h1>Azure User Defined Routes</h1>

<h2>Description</h2>
This lab will configure user defined routes.<br /><br />

In Azure, user-defined routes (UDRs) are a feature of the Azure Virtual Network (VNet) that allow you to control the routing of network traffic within your virtual network. By default, Azure provides a basic routing table for your VNets, but sometimes you need more control over how traffic flows, such as routing it through a specific network appliance or directing it to a different subnet.<br/><br/>


</h4> Purpose of User-Defined Routes</h4> <br/><br/>
Custom Routing Paths: You can create routes to direct traffic to a specific virtual appliance, like a firewall or VPN gateway, instead of the default route.<br/><br/>
Control Traffic Flow: Useful for scenarios like enforcing traffic inspection or implementing complex network architectures.<br/><br/>
Override Default Routes: UDRs can override Azure’s default routing, allowing for more precise control over the network traffic.<br/><br/>



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
