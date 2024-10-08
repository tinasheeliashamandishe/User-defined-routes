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
Below, we have 3 subnets in the same same network 10.0.0.0\16.<br/>
By default traffic moves accross all subnets in a network.<br/>
In the lab we will configure, all traffic in the network to pass through, the Central Subnet..<br/>
<img src="https://i.imgur.com/m0AicN3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>By default Azure allows traffic inside the Vnet</h4> 
<img src="https://i.imgur.com/6hfb1Vk.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>


<h4>To enable User defined routes, first create a Route table resource.</h4> 
<img src="https://i.imgur.com/TucsZEz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h4>Add route(s) to your route table</h4> 
<img src="https://i.imgur.com/7YzbUOM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h4>Associate the route table with the relevant subnets</h4> 
<img src="https://i.imgur.com/vQcrazv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h4>Enable IP forwading</h4> 
<img src="https://i.imgur.com/94vAHJC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

