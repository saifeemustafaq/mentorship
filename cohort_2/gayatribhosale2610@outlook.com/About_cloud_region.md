# What is a region?

The simplest explanation is that a “cloud region” describes the actual, real-life geographic location where your public cloud 
resources are located.It’s a common misconception that the “cloud” is just that—an intangible, ethereal storage space that 
exists only as a concept somewhere in the sky. But the cloud is just a prettier name for actual devices that process data. 
They’re data centers, and those data centers live in places.

![](https://zdnet2.cbsistatic.com/hub/i/r/2016/03/22/350dd301-824d-4cec-8c0a-63f6dd70696a/resize/770xauto/614d752563af233063c42836a1a7791d/gcp-regions1.jpg)

## Why are regions important?

- Regions allow you to locate your cloud resources close to your customers, both internal or external. The closer your customers 
are to the region where your cloud resources are located, the faster and better their experience will be. For example, if your 
customers are located in Germany, it makes sense to choose a European region for your cloud region, even if your office is in 
Delaware.

- Regions are also commonly used as part of disaster recovery (DR) strategy. While many public cloud users depend on the
reliability and redundancy of inter-region resources for DR, some use multiple regions to achieve the same result. Sometimes 
this is required for regulatory or compliance reasons, but sometimes it’s simply company policy.


# Date: June 11,2020

# What is Availability zones?

Availability zones (AZs) are isolated locations within data center regions from which public cloud services originate and operate. Regions are geographic locations in which public cloud service providers' data centers reside. Businesses choose one or multiple worldwide availability zones for their services depending on business needs.

An Availability Zone in an Azure region is a combination of a fault domain and an update domain. For example, if you create three or more VMs across three zones in an Azure region, your VMs are effectively distributed across three fault domains and three update domains. The Azure platform recognizes this distribution across update domains to make sure that VMs in different zones are not updated at the same time.

Build high-availability into your application architecture by co-locating your compute, storage, networking, and data resources within a zone and replicating in other zones. Azure services that support Availability Zones fall into two categories:

- Zonal services – where a resource is pinned to a specific zone (for example, virtual machines, managed disks, Standard IP addresses), or
- Zone-redundant services – when the Azure platform replicates automatically across zones (for example, zone-redundant storage, SQL Database).

![](https://docs.microsoft.com/en-us/azure/availability-zones/media/az-overview/az-graphic-two.png)

# What is Region Pairs?

Each Azure region is paired with another region within the same geography, and this makes a regional pair except for Brazil South, which is paired with a region outside its geography.

Among these regional pairs or Azure Region Pairs, only one paired region is updated at a time. The Azure Region pairs offer multiple benefits. These regional pairs are always located greater than 300 miles apart. These Azure Region pairs are directly connected and are far enough alone to be isolated from regional disasters so that the disaster affects only one region.

## Benefits of paired regions:

### 1. Physical isolation
Each Azure region within a pair is located at least 300 miles apart. This helps in isolation of the pairs so that the regional disaster affects only one region within that pair.

### 2. Platform-provided replication
There are some services within Microsoft Azure such as Geo-Redundant Storage that provides automatic replication to the paired region.

### 3. Region recovery order
For maximum disaster recovery, one region out of every pair is prioritized for recovery Out of every pair, the recovery of one region is prioritized.

### 4. Data residency
A region resides within the same geography for the data residency requirements for tax and judiciary purposes.

### 5. Sequential updates
To minimize the downtime, the paired regions are sequentially updated.

![](https://docs.microsoft.com/en-us/azure/media/best-practices-availability-paired-regions/georegiondatacenter.png)
