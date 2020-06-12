## Date: June 12, 2020

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
