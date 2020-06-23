## Date: June 23, 2020

>## Virtual Network (VNet)

 1. An virtual network (VNet) is a representative of your own network in cloud. 

 2. It is similar to our own on-premise network which we use at home. 

 3. It is an isolation of Azure cloud network dedicated to your own subscription. 

 4. If you have your own **subscription** in Azure, this VNet is completely dedicated to you/your organization. 

 5. They are completely isolated from other virtual networks, unless you establish a connection between two virtual networks. 

## On-premise network and VNet:

 - In a on-premise network, to have accessibility to public internet, it has to have a firewall, it has to send requests and receive requests through a router. 

 - Hence a organization will have to set up a router and a firewall/multiple firewalls and physical computer machines in the organization. 

 - These physical computers would have their own unique IP addresses. 

 - Whenever a request is initiated for a particular virtual machine, it comes from a IP address. 

 - It gets divided between the different web series which are also VM's, and the program will get executed. 

 - In Azure, the equivalent of the whole network setup, is called as VNet. 

 - VNet is a service from Azure similar to the infrastructure. It is entirely a virtual setup. 

 - Azure infrastructure takes the role of the router. 

 - It allows the access from the VNet to the public internet without any need of any type of configuration. 

## Pricing in VNet:

 - There is no extra cost for using VNet in Azure. 

 - The computing usage of internet within the VNet will be charged as per the standard rates described in the Azure VM pricing. 

 - The VPN Gateways and Public IP Addresses used in the VNet will also be charged. 

## VNet Benefits:

### 1. Isolation

 - VNets are completely isolated from one another. 

 - Nobody can access that network unless the permission is granted. 

 - Also gives you the ability to create multiple environments for your organization. 

 - These environments are created for multiple reasons. 

 - You can create one environment which is purely for development, other purely for testing or production etc. 

 - They also can be entirely replica of each other for consistency. 

 - The possibilities are basically endless. 

### 2. Access to Public Internet

 - Every VM created will have a default access to public internet. 

 - You can also control the access by using **Network Security Groups (NSG) and Firewalls**.
