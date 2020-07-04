> # **Cloud regions and availability zones**

1. Cloud computing allows users to store large databases and develop complex applications.
2. It also offers several benefits such as- instant scalability, low costs, security, anytime anywhere access, high availability, etc.
3. To store all of this data and manage all these 
4. Region, like the name indicates, is a separate geographic area.
5. Within each region there are multiple, isolated locations: Availability Zones. 
6. AZs have independent power sources, computing, networking, and cooling resources. 
7. Typically, especially if you’re new to the public cloud, your presence will be on a single AZ.

## What is a region?
- The simplest explanation is that a “cloud region” describes the actual, real-life geographic location where your public cloud resources are located.
- Regions allow you to locate your cloud resources close to your customers, both internal or external. 
- The closer your customers are to the region where your cloud resources are located, the faster and better their experience will be.

 Datacenters are sometimes called availability zones. An availability zone, has its own independent power and networking. It is set up to be an isolation boundary. If one availability zone goes down, the other continues working. The availability zones are typically connected to each other through very fast, private fiber-optic networks.

### How to choose a *region*


- #### Latency

  - Latency is ex. 
    - If you have a low latency connection, there’s little to no lag.
    - But if you have a high latency connection, there's continuous lagging which can be troublesome.
  - If your data center is in Thailand and your customers are in Arizona, they’re going to experience latency simply due to distance.
  - So, the first thing you need to do is determine where most of your customers are and choose a region that’s closest to them.
  - On such basis regions are determined.

- #### Cost

  - It costs money to run data centers, energy costs, and taxes, a cloud region can cost more money in some areas than in others.
  - For instance, a cloud region in the X area may cost more than a cloud region in Y because all those differences in real estate prices.
  - A few cloud region can be less expensive.
  - So a more expensive region will equal higher costs on your pocket.

- #### Compliance and security

  - Every company has different security requirements based on its industry, location, etc. 
  - It’s also important to know what the compliance laws in your country so that you donnt face any difficulty. 

- #### Computing and processor features

  - What’s inside the data center matters as much as where the center is located. 
  - If you require the latest, most up-to-date compute and processing, you would wannt a cloud provider that has the most lastest hardware. 
  - If you really want cutting-edge speed and power, you may need to look for a provider that uses Top-notch processors.

- #### Services and features

  - Services vary region by region. 
  - You’ll notice the difference in features that cloud provides varies widely.
  - Therefore the features and services should be checked as you begin your cloud provider hunt

- #### Disaster recovery

  - Having a down network could cost your business a huge amount of money, so Disaster recovery is important. 
  - Some companies have many data centers in the same region.
  - Regions are also commonly used as part of disaster recovery (DR) strategy
  - Each region is designed to be completely isolated from the other regions. 
  - If a earthquake like disaster hit's AWS’s US any region, say 'west' region, the other regions would be still running.


- **Important points:**
  - A region is not an Availability zone.
  - A region must have at least one AZ within it, but they’re often made up of multiple ones. 
  - For example, Amazon Web Services (AWS)‘s US East region is made up of six availability zones.

> ## Region Pairs:
- Each Region is paired with another region within the same geographical location, and this makes a regional pair.
- These regional pairs are always located greater than 300 miles apart. 
- These Azure Region pairs are directly connected and so far away that any disaster affects only one region.
- If one of the regions experience a disaster, then the services of the primary region will automatically fail, and the secondary region is available as a backup.


## Benefits of paired regions
**1. Physical isolation:** 

Each Azure region within a pair is located at least 300 miles apart. This helps in isolation of the pairs so that the regional disaster affects only one region within that pair.

**2. Platform-provided replication:**

There are some services within Microsoft Azure such as Geo-Redundant Storage that provides automatic replication to the paired region.

**3. Region recovery order:**

For maximum disaster recovery, one region out of every pair is prioritized for recovery Out of every pair, the recovery of one region is prioritized.

**4. Sequential updates:**

To minimize the downtime, the paired regions are sequentially updated.

**5. Data residency**: 
 
A region resides within the same geography as its pair (with the exception of Brazil South) to meet data residency requirements for tax and law enforcement jurisdiction purposes.

### More about Availability Zones:

Within the availability zone, the VMs are deployed on machines, that are organized in racks. Each rack has its own router. The virtual machines on one single physical machine may run multiple containers.

When an incoming request comes to the endpoint, it is usually first delivered to a load balancer to route the traffic to an instance of a service.

The goal is to run the code on different VMs that are not close to each other to reduce the chance of single point of failure. The unit of single point of failure is called a fault domain. With this hierarchy, when:

- A region goes down, everything inside the region is down.
- An availability zone goes down, everything inside the availability zone is lost.
- A rack goes down, it is the PCs that are lost.
- A PC goes down, it is the VMs on it that are lost.

### Azure Availability Zones:

#### Azure services that support Availability Zones fall into two categories:

1. **Zonal services** – you pin the resource to a specific zone (for example, virtual machines, managed disks, IP addresses), or
2. **Zone-redundant services** – platform replicates automatically across zones (for example, zone-redundant storage, SQL Database).

To achieve comprehensive business continuity on Azure, build your application architecture using the combination of Availability Zones with Azure region pairs. You can synchronously replicate your applications and data using Availability Zones within an Azure region for high-availability and asynchronously replicate across Azure regions for disaster recovery protection.

#### Understanding Azure Global Infrastructure


**Geographies (Geos)**

A geography is a separate market, typically containing two or more regions, that preserves data residency and compliance boundaries. Geographies allow customers with specific data-residency and compliance needs to keep their data and applications close. Geographies are fault-tolerant to withstand complete region failure through their connection to Microsoft dedicated high-capacity networking infrastructure. 
- Geos examples: US, Europe, Asia Pacific, Japan, Brazil, Australia, China. 

**Regions**

A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network. With more global regions than any other cloud provider, Azure gives customers the flexibility to deploy applications where they need to.
- Azure is generally available in 40 regions around the world, with plans announced for 10 additional regions

**Availability Zones**

Availability Zones are physically separate locations within an Azure region. Each Availability Zone is made up of one or more datacenters equipped with independent power, cooling, and networking. Availability Zones allow customers to run mission-critical applications with high availability and low-latency replication.


### [Microsoft Azure Cloud Datacentre](https://youtu.be/bqZrejosqWU)(Click Here)

### [Discover World Class Security at Microsoft’s Datacenters](https://youtu.be/r1cyTL8JqRg)(Click Here)


## Fault Domains

 - As every coin has two sides, just like that technology too offers so many advantages and good things but also comes with a bitter truth that is a hardware requires maintenance and hardware failures. 

 - Failover enables multiple servers to work together to provide high availability or put another way, to provide node fault tolerance. But now businesses demand ever greater availability from their infrastructure. To achieve cloud like uptime, even highly unlikely occurrences such as chassis failure, rack outages, or natural disasters must be protected against. Thus we need a system with chassis, rack, and site fault tolerance as well. 

### A fault domain is a set of hardware components that share a single point of failure. 

 - To be fault tolerant to a certain level, you need multiple fault domains at that level. 

 - So to be rack fault tolerant, your servers and your data must be distributed across multiple racks. 

 - Two events Unplanned Hardware Maintenance Event and Unexpected Downtime comes under the fault domain. 

 - Suppose we put two VM into availability set, then it set up VMs to two different racks so that if the network, power, etc failed, then only one rack will be affected. 

 - The fault domains define the group of virtual machines that share a common power source and network switch. 

 - Each fault domain contains some racks and each rack contains virtual machine. 

 - Each of these fault domain shares a power supply and a network switch. 

 - For example, if there is a failure in the fault domain then all the resources in the fault domain become unavailable. Therefore, you should place your VMs such a way that each fault domain get one web server, one database server and like that. 

## Levels of Fault Domains

   There are four canonical levels of fault domains - site, rack, chassis, and node. Nodes are discovered automatically; each additional level is optional. For example, if your deployment does not use blade servers, the chassis level may not make sense for you. 

## Benefits of Fault Domains

### 1. Storage Spaces, including Storage Spaces Direct, uses fault domains to maximize data safety:

   Resiliency in Storage Spaces is conceptually like distributed, software-defined RAID. Multiple copies of all data are kept in sync, and if hardware fails and one copy is lost, others are recopied to restore resiliency. To achieve the best possible resiliency, copies should be kept in seperate fault domains. 

### 2. The Health Service uses fault domains to provide more helpful alerts:

   Each fault domain can be associated with location metadata, which will automatically be included in any subsequent alerts. These descriptors can assist operations or maintenance personnel and reduce errors by disambiguating hardware. 

### 3. Sketch clustering uses fault domains for storage affinity:

   Sketch clustering allows faraway servers to join a common cluster. For the best performance, applications or virtual machines should be run on servers that are nearby to those providing their storage. Fault domain awareness enables this storage affinity. 

