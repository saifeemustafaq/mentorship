## Date: June 14, 2020

## What is a region? 

 - The simplest explanation is that a "cloud region" describes the actual, real-life geographic location where your public cloud resources are located. 

 - It's a common misconception that the "cloud" is just that- an intangible, ethereal storage space that exists only as a concept somewhere in the sky. But the cloud is just a prettier name for actual devices that process data. They're **data centers**, and those data centers live in places.

 - When you choose a cloud provider, you're also choosing a "region", which is where your data centers physically exist. However, while providers all define what a region is in a similar way, they differ in implementation. 

## How are regions different? 

 - Comparing regions across providers is not an apples-to-apples comparison. To really understand the differences, you need to know how each provider defines a region and how that can affect the resources available to you. 

## Why are regions important? 

 - Regions allow you to locate your cloud resources close to your customers, both internal or external. The closer your customers are to the region where your cloud resources are located, the faster and better their experience will be. For example, if your customers are located in Germany, it makes sense to choose a European region for your cloud region, even if your office is in Delaware. 

 - Regions are also commonly used as part of disaster recovery of (DR) strategy. While many public cloud users depend on the reliability and redundancy of inter-region resources for DR, some use multiple regions to achieve the same result. Sometimes this is required for regulatory or compliance reasons, but sometimes it's simply company policy. 

## How to choose a region? 

### Latency:


   If you're a gamer, you know how vital latency is. If you have a low latency connection, when you pull the trigger in your game, there's little to no lag. But if you have a high latency connection, when you pull the trigger, other people in the game with faster connections have killed your character before you've even had a chance to reload. 

   If your data center is in Thailand and your customers are in Arizona, they're going to experience latency simply due to distance. So, the first thing you need to do is determine where most of your customers are and choose a region that's closest to them. 

### Cost:


   It costs money to run data centers, and depending on real-estate costs, energy costs, and taxes, a cloud region cost more money in some areas than in others. For instance, a cloud region in the Bay Area may cost more than a cloud region in Ohio because all those tech companies are competing for a small area of real estate. On the other hand, there's plenty of open land in Ohio, so the cloud region is less expensive. The costs to maintain data centers are passed on to you, so a more expensive region will equal higher costs on your end. 

### Compliance and Security:


   Every company has different security requirements based on its industry, location, etc. It's also important to know what the compliance laws are in your country so that you aren't fined and so you don't lose the trust of your customers. As you look into different options, stick to a cloud region that makes it easier for your company to adhere to those standards. 

### Compute and Procesor Features:


   What's inside the data center matters as much as where the center is located. If you require the latest, most up-to-date compute and processing, you may not want to choose a cloud provider that relieson hardware that's five years old. For instance, some may use lvy Bridge microarchitecture, which could be fine for your business. But if you really want cutting-edge speed and power, you may need to look for a provider that uses Haswell processors. 

### Services and features:


   Services vary region by region. For instance, check out this chart from AWS. You'll notice the difference in features varies widely. If having Alexa for Business is vital to your company, your only option is choosing a Northern Virginia region. Jot down the features and services that are non-negotiable for you as you begin your cloud provider hunt so you know what to look for. 

### Disaster Recovery:


   Having a down network could cost your business millions, so redundancy is important. Some companies have redundant data centers may only be separated by a few miles. That means if a tsunami hits, both centers are likely to be affected. When you're searching for a cloud region, see where the backup cloud is located. 

## Information about top Cloud Providers

   Here's the cheat sheet summary to regions: When researching cloud regions, look at the closest regions first, determine if you can afford those regions, and then look at security and redundancy features. 
   To help out, we've gathered useful info about some of the top cloud providers. 

### Amazon Web Services

   **Region**: Amazon defines its region as a geographic location, through it's somewhat arbitrary. 

   **Local Regions**: A single data center, in closely proximity to a region, but not part of that region. 

   **Availability Zone**: Multiple availability zones (AZs) per region are physically separated and connected with private low latency, high throughput, and redundant network connections. 

### Google Cloud Platform

   **Region**: Regions are built of zones, usually close to each other, within P95 RT latencies less than 1MS and generally less than 5MS.

   **Zones**: Zones should be considered independent failure domain within the region. Zones don't always map to a single data center. 

   Google currently has 18 regions and 55 zones. All regions have three or more zones, and one zone is in development. 

### Microsoft Azure

   **Region**: A region is a set of data centers connected within a latency perimeter. 

   Microsoft has 42 regions. 12 most regions are planned, 5 current regions have availability zones, and two have AZs in preview. 

   **Geography**: Azure defines a "geography" to contain multiple regions to help maintain data residency and compliance. 

   **Availability Zones**: These are one or more data centers built on independent infrastructure with a minimum of three AZs in regions that support it. 

### Alibaba Cloud

   **Regions**: Regions are composed of zones. All Chinese zones have two or more zones. International zones have one (Tokyo) or more zones, through most have two. One region has three zones (Singapore). 
  
   **Zones**: Zones are composed of one or multiple scattered data centers, each of which has independent supporting facilities, including redundant power supplies, networks, and connections.

### Oracle Cloud

   **Region**: A region is a localized area. Regions are made of several availability domains. Availability domains do not share infrastructure like power or cooling and are connected with high speed/bandwidth networking.

   **Availability domains**: Made of one or more data centers. Each availability domain has three fault domains. Fault domains allow you to ensure the same hardware within a single avail domain is not used for all your resources. This provides additional resiliency against failure.

## Regional Pairs:

 - Each Region is paired with another region within the same geographical location, and this makes a regional pair.

 - These regional pairs are always located greater than 300 miles apart.

 - These Azure Region pairs are directly connected and so far away that any disaster affects only one region.

 - If one of the regions experience a disaster, then the services of the primary region will automatically fail, and the secondary region is available as a backup.

### Benefits of paired regions

 1. **Physical isolation**: When possible, Azure prefers at least 300 miles of separation between datacenters in a regional pair, although this isn't practical or possible in all geographies. Physical datacenter separation reduces the likelihood of natural disasters, civil unrest, power outages, or physical network outages affecting both regions at once. Isolation is subject to the constraints within the geography (geography size, power/network infrastructure availability, regulations, etc.).

 2. **Platform-provided replication**: Some services such as Geo-Redundant Storage provide automatic replication to the paired region.

 3. **Region recovery order**: In the event of a broad outage, recovery of one region is prioritized out of every pair. Applications that are deployed across paired regions are guaranteed to have one of the regions recovered with priority. If an application is deployed across regions that are not paired, recovery might be delayed – in the worst case the chosen regions may be the last two to be recovered.

 4. **Sequential updates**: Planned Azure system updates are rolled out to paired regions sequentially (not at the same time) to minimize downtime, the effect of bugs, and logical failures in the rare event of a bad update.

 5. **Data residency**: A region resides within the same geography as its pair (with the exception of Brazil South) to meet data residency requirements for tax and law enforcement jurisdiction purposes.

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



