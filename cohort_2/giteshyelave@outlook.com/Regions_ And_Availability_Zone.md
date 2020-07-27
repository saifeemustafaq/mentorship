> ## Date: June 12, 2020

# What is a region ?

##### Ans.

- A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network. 

- Azure gives you the flexibility to deploy applications where you need to, including across multiple regions to deliver cross-region resiliency.

![](https://mordorintelligence.com/images_db/RD_Images/1551343108287_cc4.png)

_ _ _ _ _ _ _ _ _ _

# Geography :

- An area of the world containing at least one Azure region.

- Geographies define a discrete market that preserve data residency and compliance boundaries.

- Geographies allow customers with specific data-residency and compliance needs to keep their data and applications close.

- Geographies are fault-tolerant to withstand complete region failure through their connection to our dedicated high-capacity networking infrastructure.

_ _ _ _ _ _ _ _ _ _

# How are regions different?

- Comparing regions across providers is not an apples-to-apples comparison. To really understand the differences, you need to know how each provider defines a region and how that can affect the resources available to you.

_ _ _ _ _ _ _ _ _ _

# Why are regions important?

- Regions are commonly used as part of disaster recovery (DR) strategy.

- While many public cloud users depend on the reliability and redundancy of inter-region resources for DR, some use multiple regions to achieve the same result.

- Sometimes this is required for regulatory or compliance reasons, but sometimes it’s simply company policy.

- For example, if your customers are located in Germany, it makes sense to choose a European region for your cloud region, even if your office is in Delaware.

_ _ _ _ _ _ _ _ _ _

# Choosing a region :

- You choose which region or zone hosts your resources, which controls where your data is stored and used. Choosing a region and zone is important for several reasons :

#### Handling failures :

- Distribute your resources across multiple zones and regions to tolerate outages.

- Google designs zones to be independent from each other: a zone usually has power, cooling, networking, and control planes that are isolated from other zones, and most single failure events will affect only a single zone. 

- Thus, if a zone becomes unavailable, you can transfer traffic to another zone in the same region to keep your services running.

- Similarly, if a region experiences any disturbances, you should have backup services running in a different region.

#### Decreased network latency :

- To decrease network latency, you might want to choose a region or zone that is close to your point of service. 

- For example, if you mostly have customers on the East Coast of the US, then you might want to choose a primary region and zone that is close to that area and a backup region and zone that is also close by.

_ _ _ _ _ _ _ _ _ _

#Region and service categories :

## Recommended Region :

- A region that provides the broadest range of service capabilities and is designed to support Availability Zones now, or in the future.

- These are designated in the Azure portal as Recommended.

## Alternate(other) Region :

- A region that extends Azure's footprint within a data residency boundary where a recommended region also exists.

- Alternate regions help to optimize latency and provide a second region for disaster recovery needs.

- They are not designed to support Availability Zones (although Azure conducts regular assessment of these regions to determine if they should become recommended regions).

- These are designated in the Azure portal as Other.

_ _ _ _ _ _ _ _ _ _

# Information about top cloud providers :

  When researching cloud regions, look at the closest regions first, determine if you can afford those regions, and then look at security and redundancy features.

  To help out, we’ve gathered useful info about some of the top cloud providers.

## Google Cloud Platform :

- Regions: Regions are built of zones, usually close to each other, within P95 RT latencies less than 1MS and generally less than 5MS.

- Zones: Zones should be considered independent failure domain within the region. Zones don't always map to a single data center.

- Google currently has 18 regions and 55 zones. All regions have three or more zones, and one zone is in development.

## Microsoft Azure :

- Region: A region is a set of data centers connected within a latency perimeter.

- Microsoft has 42 regions. 12 more regions are planned, 5 current regions have availability zones, and two have AZs in preview.

- Geography: Azure defines a “geography” to contain multiple regions to help maintain data residency and compliance.

- Availability zones: These are one or more data centers built on independent infrastructure with a minimum of three AZs in regions that support it.

## Alibaba Cloud :

- Regions: Regions are composed of zones. All Chinese zones have two or more zones. International zones have one (Tokyo) or more zones, though most have two. One region has three zones (Singapore).

- Zones: Zones are composed of one or multiple scattered data centers, each of which has independent supporting facilities, including redundant power supplies, networks, and connections.

_ _ _ _ _ _ _ _ _ _

# Availability Zones :

- An Availability Zone is a high-availability offering that protects your applications and data from datacenter failures. Availability Zones are unique physical locations within an Azure region.

- Each zone is made up of one or more datacenters equipped with independent power, cooling, and networking. To ensure resiliency, there's a minimum of three separate zones in all enabled regions.

![](https://docs.aws.amazon.com/documentdb/latest/developerguide/images/RegionsAndAZs.png)

- The physical separation of Availability Zones within a region protects applications and data from datacenter failures. Zone-redundant services replicate your applications and data across Availability Zones to protect from single-points-of-failure.

- An Availability Zone in an Azure region is a combination of a fault domain and an update domain.

- Build high-availability into your application architecture by co-locating your compute, storage, networking, and data resources within a zone and replicating in other zones. Azure services that support Availability Zones fall into two categories:

1. Zonal services – where a resource is pinned to a specific zone (for example, virtual machines, managed disks, Standard IP addresses), or

2. Zone-redundant services – when the Azure platform replicates automatically across zones (for example, zone-redundant storage, SQL Database).

_ _ _ _ _ _ _ _ _ _

> ## Date: June 16,2020

#  What is a region pair ?

##### Ans.

- An Azure Region Pair is a relationship between 2 Azure Regions within the same geographic region for disaster recovery purposes.

- If one of the regions were to experience a disaster or failure, then the services in that region will automatically failover to that regions secondary region in the pair. For example, North Central US region’s pair is South Central US.

![](https://i1.wp.com/build5nines.com/wp-content/uploads/2017/01/azureregionpairgeography.png?w=1080&ssl=1)

- Almost all the Azure Regions are located within the same geographic region as at least 1 other Azure Region; it’s Region Pair.

- The only exception to this rule is the Brazil South region, which is the only Azure Region in Brazil, so it’s Region Pair is South Central US in a one-way pairing connection, as South Central US’s pair is North Central US.

- Each Azure region is paired with another region within the same geography, and this makes a regional pair except for Brazil South, which is paired with a region outside its geography.

- Among these regional pairs or Azure Region Pairs, only one paired region is updated at a time. The Azure Region pairs offer multiple benefits.

_ _ _ _ _ _ _ _ _ _

# Benefits of paired regions :

### 1. Physical isolation :
Each Azure region within a pair is located at least 300 miles apart. This helps in isolation of the pairs so that the regional disaster affects only one region within that pair.

### 2. Platform-provided replication :
There are some services within Microsoft Azure such as Geo-Redundant Storage that provides automatic replication to the paired region.

### 3. Region recovery order :
For maximum disaster recovery, one region out of every pair is prioritized for recovery Out of every pair, the recovery of one region is prioritized.

### 4. Data residency :
A region resides within the same geography for the data residency requirements for tax and judiciary purposes.

### 5. Sequential updates :
To minimize the downtime, the paired regions are sequentially updated.

----------

# What are fault domains ?

##### Ans.

- A fault domain is a collection of functionality, services or components with a shared single point of failure. A fault level is a set of one or more fault domains serving the same purpose.

- Each and every fault domain contains some racks and each rack contains virtual machine.

![](http://www.thatlazyadmin.com/wp-content/uploads/2017/10/word-image-10.png)

_ _ _ _ _ _ _ _ _ _

#Levels of fault domains:

There are four canonical levels of fault domains - site, rack, chassis, and node.

## Cascade:
Cascade warns that when this fault level fails, it is neither redundant nor ignorable, and consequently the fault level above it in the fault hierarchy must take responsibility for the failure. Any single point of failure is going to operate this way, for example a traditional MySQL setup without automated failover would cascade, as would a Cassandra cluster running with read-majority configuration which was no longer able to complete majority reads.

## Ignorable:
Ignorable requires that fault levels higher in the fault hierarchy can continue operating if this fault level fails. An example might be a website that can annotate stories with social actions by your friends, but which stops showing that social context if the database they're stored in becomes unavailable, while continuing to render the remainder of the page.

## Usage:
You can use PowerShell or XML markup to specify fault domains. Both approaches are equivalent and provide full functionality.

## Redundant:
Redundant means that fault domains within the level can take over responsibility for a failed domain's responsibilities. Some examples here are nodes in a Cassandra or Memcache cluster, or an architecture design that supports the loss of an AWS Availability Zone.

_ _ _ _ _ _ _ _ _ _

# Benefits :

### Stretch clustering uses fault domains for storage affinity :
Stretch clustering allows faraway servers to join a common cluster. For the best performance, applications or virtual machines should be run on servers that are nearby to those providing their storage. Fault domain awareness enables this storage affinity.

### The Health Service uses fault domains to provide more helpful alerts :
Each fault domain can be associated with location metadata, which will automatically be included in any subsequent alerts. These descriptors can assist operations or maintenance personnel and reduce errors by disambiguating hardware.

### Storage Spaces, including Storage Spaces Direct, uses fault domains to maximize data safety :
Resiliency in Storage Spaces is conceptually like distributed, software-defined RAID. Multiple copies of all data are kept in sync, and if hardware fails and one copy is lost, others are recopied to restore resiliency. To achieve the best possible resiliency, copies should be kept in separate fault domains.

----------
