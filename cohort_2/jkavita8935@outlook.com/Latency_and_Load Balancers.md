## Date: June 22, 2020

> # ***Latency***

### **Latency is the delay between a user’s action and a web application’s response to that action, often referred to in networking terms as the total round trip time it takes for a data packet to travel.**

![](https://networkencyclopedia.com/wp-content/uploads/2019/10/latency-1024x402.png)


- #### **The term “latency” can also refer to the delay in forming a connection, such as the 15 to 30 seconds required to establish a modem connection.**

- #### **Intrinsic latency in a transmission is caused by the finite transmission speed of the electrical signals through the wires (or the light signals through the fiber-optic cabling). Intrinsic latency cannot be eliminated but is usually quite small.**

- #### **Much greater latency is usually introduced into a network by gateway devices such as routers and bridges, which process packets and perform protocol conversion.**

- #### **The latency for a bridge is thus the time delay between the moment when the packet enters one port of the bridge and the moment when it leaves another port – usually a fraction of a millisecond.**


> # ***Latency vs bandwidth vs throughput***

- **Bandwidth** determines how narrow or wide a pipe is. The narrower it is, the less data is able to be pushed through it at once and vice-versa.

- **Latency** determines how fast the contents within a pipe can be transferred from the client to the server and back.

- **Throughput** is the amount of data which can be transferred over a given time period.

If the latency in a pipe is low and the bandwidth is also low, that means that the throughput will be inherently low. However, if the latency is low and the bandwidth is high that will allow for greater throughput and a more efficient connection. Ultimately, latency creates bottlenecks within the network thus reducing the amount of data which can be transferred over a period of time.

> # Causes of network latency

### 1.Transmission medium: 

The physical path between the start point and the end point. The type ofmedium can impact latency. For instance, old copper cable-based networks have a higher latency than modern optic fibers.

### 2. Propagation: 

The further apart two nodes are the more latency there is as latency is dependent on the distance between the two communicating nodes. Theoretically, latency of a packet going on a round trip across the world is 133ms. In actuality, such a round trip takes longer, though latency is decreased when direct connections through network backbones are achieved.

### 3. Routers: 

The efficiency in which routers process incoming data has a direct impact on latency. Router to router hops can increase latency.Storage delays: Accessing stored data can increase latency as the storage network may take time to process and return information.

> # How to reduce latency

- Latency can be reduced by addressing the aforementioned components and ensuring that they are working correctly. It can also be reduced by using dedicated networks that streamline the network path and provide direct communication between nodes.

- Content Delivery Network (CDN) providers such as StackPath provide customers with private networks that allow them to bypass the public internet. These private networks reduce latency by providing more efficient paths for data packets to travel on.


> # Other types of latency

## ***1. network latency***

Latency is a measure of delay.  In a network, latency measures the time it takes for some data to get to its destination across the network.  It is usually measured as a round trip delay - the time taken for information to get to its destination and back again.   The round trip delay is an important measure because a computer that uses a TCP/IP network sends a limited amount of data to its destination and then waits for an acknowledgement to come back before sending any more.  Thus, the round trip delay has a key impact on the performance of the network.

Latency is usually measured in milliseconds (ms).


## ***2. Fibre optic latency***

Latency in the case of data transfer through fibre optic cables can't be fully explained without first discussing the speed of light and how it relates to latency. Based on the speed of light alone (299,792,458 meters/second), there is a latency of 3.33 microseconds (0.000001 of a second) for every kilometer of path covered. Light travels slower in a cable which means the latency of light traveling in a fibre optic cable is around 4.9 microseconds per kilometer.

Based on how far a packet must travel, the amount of latency can quickly add up. Cable imperfections can also degrade the connection and increase the amount of latency incurred by a fibre optic cable.


## ***3. Audio latency***

This form of latency is the time difference between a sound being created and heard. The speed of sound plays a role in this form of latency which can vary based on the environment it travels through e.g solids vs liquids. In technology, audio latency can occur from various sources including analog to digital conversion, signal processing, hardware / software used, etc

##  ***4. Disk latency***

Disk latency is the delay between the time data is requested from a storage device and when the data starts being returned. Factors that effect disk latency include the rotational latency (of a hard drive) and the seek time. A hard drive with a rotational speed of 5400 RPM, for example, will have almost twice the rotational latency of a drive that rotates at 10,000 RPM.



### **Typical values for latency :**

- 800ms for satellite

- 120ms for 3G cellular data

- 60ms for 4G cellular data which is often used for 4G WAN and internet connections

- 20ms for an mpls network such as BT IP Connect, when using Class of Service to prioritise traffic

- 10ms for a modern Carrier Ethernet network such as BT Ethernet Connect or BT Wholesale Ethernet in the UK


## Date: June 24, 2020

# ***Load Balancer***

- A physical device, a virtualized instance running on specialized hardware or a software process.

- Incorporated into application delivery controllers (ADCs) designed to more broadly improve the performance and security of three-tier web and microservices-based applications,regardless of where they’re hosted.

- Able to leverage many possible load balancing algorithms, including round robin, server response time and the least connection method to distribute traffic in line with current requirements.


## **load balancer performs the following functions:**

- Distributes client requests or network load efficiently across multiple servers

- Ensures high availability and reliability by sending requests only to servers that are online

- Provides the flexibility to add or subtract servers as demand dictates


![](https://www.nginx.com/wp-content/uploads/2014/07/what-is-load-balancing-diagram-NGINX-768x389.png)


> # ***Load Balancing Algorithms***


**1. Round Robin –**

Requests are distributed across the group of servers sequentially.

**2. Least Connections –**

A new request is sent to the server with the fewest current connections to clients. The relative computing capacity of each server is factored into determining which one has the least connections.

**3. Least Time –**

Sends requests to the server selected by a formula that combines the fastest response time and fewest active connections. Exclusive to NGINX Plus.

**Hash –**

Distributes requests based on a key you define, such as the client IP address orthe request URL. NGINX Plus can optionally apply a consistent hash to minimize redistribution
of loads if the set of upstream servers changes.

**IP Hash –**

The IP address of the client is used to determine which server receives the request.

**Random with Two Choices –**

Picks two servers at random and sends the request to the one that is selected by then applying the Least Connections algorithm.

> # ***Benefits of Load Balancing***

- Reduced Downtime

- Scalable

- Redundancy

- Flexibility

- Efficiency

- Global Server Load Balancing

----

## Date: June 27, 2020

> # Types of load balancer :

## 1. Application Load Balancer :

Application Load Balancer is best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers. Operating at the individual request level (Layer 7), Application Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) based on the content of the request.

## 2. Network Load Balancer :

Network Load Balancer is best suited for load balancing of Transmission Control Protocol (TCP), User Datagram Protocol (UDP) and Transport Layer Security (TLS) traffic where extreme performance is required. Operating at the connection level (Layer 4), Network Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) and is capable of handling millions of requests per second while maintaining ultra-low latencies. Network Load Balancer is also optimized to handle sudden and volatile traffic patterns.

## 3. Classic Load Balancer :

Classic Load Balancer provides basic load balancing across multiple Amazon EC2 instances and operates at both the request level and connection level. Classic Load Balancer is intended for applications that were built within the EC2-Classic network.

## 4. HTTP(S) Load Balancing: 

HTTP(S) load balancing is one of the oldest forms of load balancing. This form of load balancing relies on layer 7, which means it operates in the application layer. HTTP load balancing is often dubbed the most flexible type of load balancing because it allows you to form distribution decisions based on any information that comes with an HTTP address.

## 5. Virtual Load Balancer : 

A virtual load balancer differs from software load balancers because it deploys the software of a hardware load balancing device on a virtual machine.

> ## Hardware- vs software-based load balancers :

### **Hardware-based load balancers work as follows:**

- They are typically high-performance appliances, capable of securely processing multiple gigabits of traffic from various types of applications.

- These appliances may also contain built-in virtualization capabilities, which consolidate numerous virtual load balancer instances on the same hardware.

- That allows for more flexible multi-tenant architectures and full isolation of tenants, among other benefits.

### **software-based load balancers works as follows:**

- Can fully replace load balancing hardware while delivering analogous functionality and superior flexibility.

- May run on common hypervisors, in containers or as Linux processes with minimal overhead on bare-metal servers and are highly configurable depending on the use cases and         technical requirements in question.

- Can save space and reduce hardware expenditures.

---

# What is a VNet ?

![](https://www.rebeladmin.com/wp-content/uploads/2019/09/VNEt.jpg)

- An Azure Virtual Network (VNet) is a representation of your own network in the cloud. It is a logical isolation of the Azure cloud dedicated to your subscription.

- Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. VNet enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks.

- VNet is similar to a traditional network that you'd operate in your own data center, but brings with it additional benefits of Azure's infrastructure such as scale, availability, and isolation.


## **Use VNets to:**

- Create a dedicated private cloud-only VNet. Sometimes you don't require a cross-premises configuration for your solution. When you create a VNet, your services and VMs within your VNet can communicate directly and securely with each other in the cloud. You can still configure endpoint connections for the VMs and services that require Internet communication, as part of your solution.

- Securely extend your data center. With VNets, you can build traditional site-to-site (S2S) VPNs to securely scale your datacenter capacity. S2S VPNs use IPSEC to provide a secure connection between your corporate VPN gateway and Azure.

- Enable hybrid cloud scenarios. VNets give you the flexibility to support a range of hybrid cloud scenarios. You can securely connect cloud-based applications to any type of on-premises system such as mainframes and Unix systems.


> # VNet concepts :

## Address space: 

When creating a VNet, you must specify a custom private IP address space using public and private (RFC 1918) addresses. Azure assigns resources in a virtual network a private IP address from the address space that you assign. 

**For example -** If user deploy a VM in a VNet with address space, 10.0.0.0/16, the VM will be assigned a private IP like 10.0.0.4.

## Subnets: 

Subnets enable you to segment the virtual network into one or more sub-networks and allocate a portion of the virtual network's address space to each subnet. You can then deploy Azure resources in a specific subnet. 

Just like in a traditional network, subnets allow you to segment your VNet address space into segments that are appropriate for the organization's internal network. 

## Regions: 

VNet is scoped to a single region/location; however, multiple virtual networks from different regions can be connected together using Virtual Network Peering.

## Subscription: 

VNet is scoped to a subscription. You can implement multiple virtual networks within each Azure subscription and Azure region.

### Tools use to create a VNet :

- Azure portal

- PowerShell

- Azure CLI

- A network configuration file

---
