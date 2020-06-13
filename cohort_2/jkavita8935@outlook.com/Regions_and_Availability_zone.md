

## Date: June 8, 2020

# What is a region?

##  ***The simplest explanation is that a “cloud region” describes the actual, real-life geographic location where your public cloud resources are located.***

![](https://map.buildazure.com/images/ms-azure-region-map.png)


> # Importance of regions:

- **Regions allow you to locate your cloud resources close to your customers, both internal or external. The closer your customers are to the region where your cloud resources are located, the faster and better their experience will be. For example, if your customers are located in Germany, it makes sense to choose a European region for your cloud region, even if your office is in Delaware.**

- **Regions are also commonly used as part of disaster recovery (DR) strategy. While many public cloud users depend on the reliability and redundancy of inter-region resources for DR, some use multiple regions to achieve the same result. Sometimes this is required for regulatory or compliance reasons, but sometimes it’s simply company policy.**
  
# How to choose a region?

## ***Latency***

- **If your data center is in Thailand and your customers are in Arizona, they’re going to experience latency simply due to distance. So, the first thing you need to do is determine where most of your customers are and choose a region that’s closest to them.**
  
## ***Cost***
   
- **It costs money to run data centers, and depending on real estate costs, energy costs, and taxes, a cloud region can cost more money in some areas than in others. For instance, a cloud region in the Bay Area may cost more than a cloud region in Ohio because all those tech companies are competing for a small area of real estate.** 
    
## ***Compliance and security***

- **Every company has different security requirements based on its industry, location, etc. It’s also important to know what the compliance laws are in your country so that you aren’t fined and so you don’t lose the trust of your customers. As you look into different options, stick to a cloud region that makes it easier for your company to adhere to those standards.**
   
## ***Compute and processor features***
  
- **If you require the latest, most up-to-date compute and processing, you may not want to choose a cloud provider that relies on hardware that’s five years old. For instance, some may use Ivy Bridge microarchitecture, which could be fine for your business. But if you really want cutting-edge speed and power, you may need to look for a provider that uses Haswell processors.**
   
## ***Services and features***

-  **Services vary region by region.  If having Alexa for Business is vital to your company, your only option is choosing a Northern Virginia region. Jot down the features and services that are non-negotiable for you as you begin your cloud provider hunt so you know what to look for.**
   
## ***Disaster recovery***
 
- **Having a down network could cost your business millions, so redundancy is important. Some companies have redundant data centers in the same region, and the two data centers may only be separated by a few miles. That means if a tsunami hits, both centers are likely to be affected. When you’re searching for a cloud region, see where the backup cloud is located.**
   
 
> # Availability zones:
 
 ### ***An Availability Zone is a high-availability offering that protects your applications and data from datacenter failures. Availability Zones are unique physical locations within an Azure region. Each zone is made up of one or more datacenters equipped with independent power, cooling, and networking.***
---

![](https://jelastic.com/blog/wp-content/uploads/2016/12/map-fb-3.png)


# ***Regions and Availability Zones in :***

### 1. Amazon Web Services:
### 2. Google Cloud Platform:
### 3. Microsoft Azure:
### 4. Alibaba Cloud:
### 5. Oracle Cloud:

# 1. Amazon Web Services:
  
## Region :

- Amazon defines its region as a geographic location, though it’s somewhat arbitrary.
  
 ## Local regions : 
 
- A single data center, in close proximity to a region, but not part of that region.

## Availability zone : 

- Multiple availability zones (AZs) per region are physically separated and connected with private low latency, high throughput, and redundant network connections.

- The first AWS regions were launched with two AZs, except Singapore, which launched with a single AZ. New regions typically launch with three or more AZs. AWS currently has 18 regions composed of 55 AZs, one local region in Osaka, and plans for five more regions and 15 more AZs.
   
# 2. Google Cloud Platform:

## Regions: 

- Regions are built of zones, usually close to each other, within P95 RT latencies less than 1MS and generally less than 5MS.

## Avilability Zones:

- Zones should be considered independent failure domain within the region. Zones don't always map to a single data center.

- Google currently has 18 regions and 55 zones. All regions have three or more zones, and one zone is in development.
 
# 3. Microsoft Azure:

## Region: 

- A region is a set of data centers connected within a latency perimeter.

- Microsoft has 42 regions. 12 more regions are planned, 5 current regions have availability zones, and two have AZs in preview.

## Geography: 

- Azure defines a “geography” to contain multiple regions to help maintain data residency and compliance.

## Availability zones: 

- These are one or more data centers built on independent infrastructure with a minimum of three AZs in regions that support it.
 
# 4. Alibaba Cloud:

## Regions: 

- Regions are composed of zones. All Chinese zones have two or more zones. International zones have one (Tokyo) or more zones, though most have two. One region has three zones (Singapore).

## Availability Zones: 

- Zones are composed of one or multiple scattered data centers, each of which has independent supporting facilities, including redundant power supplies, networks, and connections.
   
# 5. Oracle Cloud:

## Region: 

- A region is a localized area. Regions are made of several availability domains. Availability domains do not share infrastructure like power or cooling and are connected with high speed/bandwidth networking.

## Availability domains: 

- Made of one or more data centers. Each availability domain has three fault domains. Fault domains allow you to ensure the same hardware within a single avail domain is not used for all your resources. This provides additional resiliency against failure.
   
## Date: June 12, 2020

# region pair :

 ### Each region is always paired with another region within the same geography (such as US, Europe, or Asia) at least 300 miles away. This approach allows for the replication of resources such as virtual machine storage across a geography that helps reduce the likelihood of interruptions due to events such as natural disasters, civil unrest, power outages, or physical network outages affecting both regions at once.



![](https://docs.microsoft.com/en-us/azure/media/best-practices-availability-paired-regions/georegiondatacenter.png)

### An Azure region consists of a set of data centers deployed within a latency-defined perimeter and connected through a dedicated low- latency network. This ensures that Azure services within an Azure region offer the best possible performance and security.

> # Benefits of paired regions

## 1. Physical isolation :

-  **When possible, Azure prefers at least 300 miles of separation between datacenters in a regional pair, although this isn't              practical or   possible in all geographies. Physical datacenter separation reduces the likelihood of natural disasters, civil         unrest, power outages, or physical network outages affecting both regions at once. Isolation is subject to the constraints within       the  eography.**

## 2. Platform :

-  **provided replication - Some services such as Geo-Redundant Storage provide automatic replication to the paired region.**

## 3. Region recovery order :

 -  **In the event of a broad outage, recovery of one region is prioritized out of every pair. Applications that are deployed across           paired regions are guaranteed to have one of the regions recovered with priority. If an application is deployed across regions           that are not paired, recovery might be delayed – in the worst case the chosen regions may be the last two to be recovered.**

## 4. Sequential updates :

 -  #### Planned Azure system updates are rolled out to paired regions sequentially (not at the same time) to minimize downtime, the          effect of bugs, and logical failures in the rare event of a bad update.

## 5. Data residency :

 -  **A region resides within the same geography as its pair (with the exception of Brazil South) to meet data residency requirements      for tax and law enforcement jurisdiction purposes.**
 
 
 # Fault domains :
 
 ### ***A fault domain is a set of hardware components that share a single point of failure. To be fault tolerant to a certain level, you need multiple fault domains at that level. For example, to be rack fault tolerant, your servers and your data must be distributed across multiple racks.***
 
 
#### Suppose we put two VM into availability set, then Azure will set up VMs to two different racks so that if the network, power, etc. failed, then only one rack will be affected.
 
 ![](https://1.bp.blogspot.com/-hX3asi0KRSg/XBeNeRY8SGI/AAAAAAAABKY/0fA2_89Co9ISs10-snXNdmgelaC0LPpEQCLcBGAs/s640/Fault%2BDomain.PNG)
 
 #### In this image  two VMs are on the same availability set, so Azure has been provisioned them on two different racks. It always seen that only two Fault Domains are available in Azure and VMs spreads on over these two fault domains (FD0 and FD1)
 
 
 > # ***Benefits :*** 
 
 ## 1. Storage Spaces, including Storage Spaces Direct, uses fault domains to maximize data safety :
 
- **Resiliency in Storage Spaces is conceptually like distributed, software-defined RAID. Multiple copies of all data are kept in sync, and if hardware fails and one copy is lost, others are recopied to restore resiliency. To achieve the best possible resiliency, copies should be kept in separate fault domains.**
 
 ## 2. The Health Service uses fault domains to provide more helpful alerts :
 
 - **Each fault domain can be associated with location metadata, which will automatically be included in any subsequent alerts. These descriptors can assist operations or maintenance personnel and reduce errors by disambiguating hardware.**

## 3. Stretch clustering uses fault domains for storage affinity :

- **Stretch clustering allows faraway servers to join a common cluster. For the best performance, applications or virtual machines should be run on servers that are nearby to those providing their storage. Fault domain awareness enables this storage affinity.**
 
 
 > #  ***Levels of fault domains :***
 
- **There are four canonical levels of fault domains - site, rack, chassis, and node. Nodes are discovered automatically; each additional level is optional. For example, if our deployment does not use blade servers, the chassis level may not make sense for us.**

![](https://docs.microsoft.com/en-us/windows-server/failover-clustering/media/fault-domains-in-windows-server-2016/levels-of-fault-domains.png)


## Usage :

#### we can use PowerShell or XML markup to specify fault domains. Both approaches are equivalent and provide full functionality.

