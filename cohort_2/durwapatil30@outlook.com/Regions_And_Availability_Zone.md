> ## Date: June 12, 2020

# What is a region ?

##### Ans.

- The simplest explanation is that a “cloud region” describes the actual, real-life geographic location where your public cloud resources are located.

- It’s a common misconception that the “cloud” is just that—an intangible, ethereal storage space that exists only as a concept somewhere in the sky. But the cloud is just a prettier name for actual devices that process data. They’re data centers, and those data centers live in places.

![](https://mordorintelligence.com/images_db/RD_Images/1551343108287_cc4.png)

_ _ _ _ _ _ _ _ _ _

# How are regions different ?

- Comparing regions across providers is not an apples-to-apples comparison. To really understand the differences, you need to know how each provider defines a region and how that can affect the resources available to you.

_ _ _ _ _ _ _ _ _ _

# Why are regions important ?

- Regions allow you to locate your cloud resources close to your customers, both internal or external. 

- The closer your customers are to the region where your cloud resources are located, the faster and better their experience will be.

- For example, if your customers are located in Germany, it makes sense to choose a European region for your cloud region, even if your office is in Delaware.

_ _ _ _ _ _ _ _ _ _

# How to choose a region :

#### Latency :

- If you’re a gamer, you know how vital latency is. If you have a low latency connection, when you pull the trigger in your game, there’s little to no lag. But if you have a high latency connection, when you pull the trigger, other people in the game with faster connections have killed your character before you’ve even had a chance to reload.

#### Cost :

- It costs money to run data centers, and depending on real estate costs, energy costs, and taxes, a cloud region can cost more money in some areas than in others.

#### Compliance and security :

- Every company has different security requirements based on its industry, location, etc. It’s also important to know what the compliance laws are in your country so that you aren’t fined and so you don’t lose the trust of your customers.

#### Compute and processor features :

- What’s inside the data center matters as much as where the center is located. If you require the latest, most up-to-date compute and processing, you may not want to choose a cloud provider that relies on hardware that’s five years old.

#### Services and features :

- Services vary region by region.

#### Disaster recovery :

- Having a down network could cost your business millions, so redundancy is important. Some companies have redundant data centers in the same region, and the two data centers may only be separated by a few miles.

- That means if a tsunami hits, both centers are likely to be affected. When you’re searching for a cloud region, see where the backup cloud is located.

_ _ _ _ _ _ _ _ _ _

# Region and service categories :

- Azure's approach on availability of Azure services across regions is best described by expressing services made available in recommended regions and alternate regions.

1.) Recommended region - A region that provides the broadest range of service capabilities and is designed to support Availability Zones now, or in the future. These are designated in the Azure portal as Recommended.

2.) Alternate (other) region - A region that extends Azure's footprint within a data residency boundary where a recommended region also exists. Alternate regions help to optimize latency and provide a second region for disaster recovery needs. They are not designed to support Availability Zones (although Azure conducts regular assessment of these regions to determine if they should become recommended regions). These are designated in the Azure portal as Other.

_ _ _ _ _ _ _ _ _ _

# Geography :

- An area of the world containing at least one Azure region.

- Geographies define a discrete market that preserve data residency and compliance boundaries.

- Geographies allow customers with specific data-residency and compliance needs to keep their data and applications close.

- Geographies are fault-tolerant to withstand complete region failure through their connection to our dedicated high-capacity networking infrastructure.

_ _ _ _ _ _ _ _ _ _

# Information about top cloud providers :

  When researching cloud regions, look at the closest regions first, determine if you can afford those regions, and then look at security and redundancy features.

  To help out, we’ve gathered useful info about some of the top cloud providers.

## Amazon Web Services :

- Region : Amazon defines its region as a geographic location, though it’s somewhat arbitrary.

- Local regions : A single data center, in close proximity to a region, but not part of that region.

- Availability zone : Multiple availability zones (AZs) per region are physically separated and connected with private low latency, high throughput, and redundant network connections.

- The first AWS regions were launched with two AZs, except Singapore, which launched with a single AZ. New regions typically launch with three or more AZs. AWS currently has 18 regions composed of 55 AZs, one local region in Osaka, and plans for five more regions and 15 more AZs.

## Google Cloud Platform

- Regions : Regions are built of zones, usually close to each other, within P95 RT latencies less than 1MS and generally less than 5MS.

- Zones : Zones should be considered independent failure domain within the region. Zones don't always map to a single data center.

- Google currently has 18 regions and 55 zones. All regions have three or more zones, and one zone is in development.

## Oracle Cloud :

- Region: A region is a localized area. Regions are made of several availability domains. Availability domains do not share infrastructure like power or cooling and are connected with high speed/bandwidth networking.

- Availability domains: Made of one or more data centers. Each availability domain has three fault domains. Fault domains allow you to ensure the same hardware within a single avail domain is not used for all your resources. This provides additional resiliency against failure.

_ _ _ _ _ _ _ _ _ _

# Availability zones (AZs) :

- Availability zones (AZs) are isolated locations within data center regions from which public cloud services originate and operate.

- Regions are geographic locations in which public cloud service providers' data centers reside. 

- Businesses choose one or multiple worldwide availability zones for their services depending on business needs.

- Businesses select availability zones for a variety of reasons, including compliance and proximity to end customers.

![](https://docs.aws.amazon.com/documentdb/latest/developerguide/images/RegionsAndAZs.png)

- Cloud administrators can also choose to replicate services across multiple availability zones to decrease latency or protect resources.

- Admins can move resources to another availability zone in the event of an outage. Certain cloud services may also be limited to particular regions or AZs.

- Amazon Web Services (AWS) operates regions in the United States, South America, Europe and Asia Pacific. Each region contains between two and five availability zones that are geographically separate from one another. Regions are connected to one another through the internet. Each availability zone holds one or more data centers.

- Microsoft Azure assembles availability sets -- VMs linked together for continuous operability -- into regions that are grouped into six geographies: United States, Europe, Asia Pacific, Japan, Brazil and Australia. Azure customers choose between Locally Redundant Storage, in which data is stored locally in the end users' primary region, or Geo Redundant Storage where data is stored more than 250 miles away from the primary region, but in the same geography.

- Similar to AWS, Google Cloud Platform gathers data centers in regions comprised of zones. Google operates regions of data centers in central United States, Western Europe and East Asia.

_ _ _ _ _ _ _ _ _ _

> ## Date: June 16,2020

#  What is a region pair ?

##### Ans.

- A regional pair consists of two regions within the same geography. Azure serializes platform updates (planned maintenance) across regional pairs, ensuring that only one region in each pair updates at a time.

- If an outage affects multiple regions, at least one region in each pair will be prioritized for recovery.

![](https://docs.microsoft.com/en-us/azure/media/best-practices-availability-paired-regions/georegiondatacenter.png)

- Each Azure region is paired with another region within the same geography, and this makes a regional pair except for Brazil South, which is paired with a region outside its geography.

- Among these regional pairs or Azure Region Pairs, only one paired region is updated at a time. The Azure Region pairs offer multiple benefits.

- These regional pairs are always located greater than 300 miles apart. These Azure Region pairs are directly connected and are far enough alone to be isolated from regional disasters so that the disaster affects only one region.

- These Azure Regions are paired together, within the same geographic regions, for retrieving our data even after the experience of disaster, and also for the Business Continuity and Disaster Recovery (BCDR) purpose.

_ _ _ _ _ _ _ _ _ _

# Benefits of paired regions :

### Physical isolation :
When possible, Azure prefers at least 300 miles of separation between datacenters in a regional pair, although this isn't practical or possible in all geographies. Physical datacenter separation reduces the likelihood of natural disasters, civil unrest, power outages, or physical network outages affecting both regions at once. Isolation is subject to the constraints within the geography (geography size, power/network infrastructure availability, regulations, etc.).

### Platform-provided replication :
Some services such as Geo-Redundant Storage provide automatic replication to the paired region.

### Region recovery order :
In the event of a broad outage, recovery of one region is prioritized out of every pair. Applications that are deployed across paired regions are guaranteed to have one of the regions recovered with priority. If an application is deployed across regions that are not paired, recovery might be delayed – in the worst case the chosen regions may be the last two to be recovered.

### Sequential updates :
Planned Azure system updates are rolled out to paired regions sequentially (not at the same time) to minimize downtime, the effect of bugs, and logical failures in the rare event of a bad update.

### Data residency :
A region resides within the same geography as its pair (with the exception of Brazil South) to meet data residency requirements for tax and law enforcement jurisdiction purposes.

_ _ _ _ _ _ _ _ _ _

# What are fault domains ?

##### Ans.

- A fault domain is a set of hardware components that share a single point of failure. To be fault tolerant to a certain level, you need multiple fault domains at that level.

- When you put VMs on an Availability Set, then to protect VMs from failure, Azure spread them on fault domain and update domain.

![](https://1.bp.blogspot.com/-hX3asi0KRSg/XBeNeRY8SGI/AAAAAAAABKY/0fA2_89Co9ISs10-snXNdmgelaC0LPpEQCLcBGAs/s640/Fault%2BDomain.PNG)

_ _ _ _ _ _ _ _ _ _

# Levels of fault domains:

There are four canonical levels of fault domains - site, rack, chassis, and node. Nodes are discovered automatically; each additional level is optional. For example, if your deployment does not use blade servers, the chassis level may not make sense for you.

## Ignorable:
Ignorable requires that fault levels higher in the fault hierarchy can continue operating if this fault level fails. An example might be a website that can annotate stories with social actions by your friends, but which stops showing that social context if the database they're stored in becomes unavailable, while continuing to render the remainder of the page.

## Usage:
You can use PowerShell or XML markup to specify fault domains. Both approaches are equivalent and provide full functionality.

## Redundant:
Redundant means that fault domains within the level can take over responsibility for a failed domain's responsibilities. Some examples here are nodes in a Cassandra or Memcache cluster, or an architecture design that supports the loss of an AWS Availability Zone.

## Cascade:
Cascade warns that when this fault level fails, it is neither redundant nor ignorable, and consequently the fault level above it in the fault hierarchy must take responsibility for the failure. Any single point of failure is going to operate this way, for example a traditional MySQL setup without automated failover would cascade, as would a Cassandra cluster running with read-majority configuration which was no longer able to complete majority reads.

_ _ _ _ _ _ _ _ _ _

# Benefits :

### Storage Spaces, including Storage Spaces Direct, uses fault domains to maximize data safety :
Resiliency in Storage Spaces is conceptually like distributed, software-defined RAID. Multiple copies of all data are kept in sync, and if hardware fails and one copy is lost, others are recopied to restore resiliency. To achieve the best possible resiliency, copies should be kept in separate fault domains.

### The Health Service uses fault domains to provide more helpful alerts :
Each fault domain can be associated with location metadata, which will automatically be included in any subsequent alerts. These descriptors can assist operations or maintenance personnel and reduce errors by disambiguating hardware.

### Stretch clustering uses fault domains for storage affinity :
Stretch clustering allows faraway servers to join a common cluster. For the best performance, applications or virtual machines should be run on servers that are nearby to those providing their storage. Fault domain awareness enables this storage affinity.

_ _ _ _ _ _ _ _ _ _
