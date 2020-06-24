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

### 3. Security

 - Internet traffic entering and exiting i.e. requests sent and received, on the VM, in the VNet can be controlled using Network Security Groups. 

### 4. Connectivity

 - If you want to connect a Secured Connection to VNet from your laptop, you can establish a VPN tunnel between your own PC to VNet, this is also possible. 

 - It is called as Point to Site Network. 

 - You can also connect multiple on-site PC's to your VNet. 

 - It is referred as Site to Site Network. 

 - Hybrid connectivity is possible. 

#### You can fully control the IP addresses, DNS servers, security policies. 

#### VNet is further broken down into subnets. 

### These are the advantages VNet offers

> VNet Overview: In the following figure, VMs are represented as web servers and database servers. Each set of VMs are assigned to separate subnets in the VNet. 

![](https://user-images.githubusercontent.com/65165798/83379660-b6f64b00-a3f9-11ea-8add-665d3f21c07d.png) 

  You can create a VNet before or as you create a VM. You create these resources to support communication with a VM:

 - Network Interfaces

 - IP Addresses

 - Virtual Network and Subnets

  In addition to those basic resources, you should also consider these optional resources:

 - Network Security Groups

 - Load Balancers

## Network Interface (NIC):

  A **network interface (NIC)** is the interconnection between a virtual machine (VM) and a virtual network (VNet). A VM must have at least one NIC, but can have more than one, depending on the size of the VM you create. 

 - Network interface is the point of interconnection between a computer and a private or public network. 

 - A network interface is generally a network interface card (NIC) but does not have to have a physical form. 

 - Instead, the network interface can be implemented in software. 

  You can create a VM with multiple NICs, and add or remove NICs through the lifecycle of a VM. Multiple NICs allow a VM to connect to different subnets and send or receive traffic over the most appropriate interface. VMs with any number of network interfaces can exist in the same availability set, upto the number supported by the VM size. 

## Subnets

>### Subnets:

 1. A subnet is a range of IP addresses in the VNet. 

 2. You can divide a VNet into multiple subnets for organization and security. 

 3. Each NIC in a VM is connected to one subnet in one VNet. 

 4. NICs connected to a subnets (same or different) within a VNet can communicate with each other without any extra configuration. 

When you set up a VNet, you specify the topology, including the available address spaces and subnets. 

If the VNet is to connected to other VNets or on-premises networks, you must select address ranges that don't overlap. The IP addresses are private and can't be accessed from the internet. 



