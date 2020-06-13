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


# Date: June 13, 2020

# What is Fault Domain?

- Fault domains define the group of virtual machines that share a common power source and network switch.
- Each and every fault domain contains some racks and each rack contains virtual machine.
- Each of these Fault domain shares a power supply and a network switch.
- If there is a failure in the fault domain then all the resources in the fault domain become unavailable.
- You should place your vms such a way that each fault domain get one web server, one database server and like that.

Here we have arranged web server vm and database server vm in such a way that if one Fault Domain fails, still your vms would be available.

![](https://www.c-sharpcorner.com/article/availability-set-fault-domains-and-update-domains-in-azure-virtual-machie/Images/Screenshot_26.png)

## Levels of fault domains:

There are four canonical levels of fault domains - site, rack, chassis, and node. Nodes are discovered automatically; each additional level is optional. For example, if your deployment does not use blade servers, the chassis level may not make sense for you.

A fault domain is a collection of functionality, services or components with a shared single point of failure. A fault level is a set of one or more fault domains serving the same purpose, for example if you ran active-active across multiple AWS Regions, then "AWS Region" would be your fault level and the specific regions such as "us-east1" and "us-east2" would be your fault domains.

Each fault level exists within a fault hierarchy, where smaller fault levels (a database replica) nest under larger (a database cluster). This nesting allows larger levels to provide defense in depth against failures within those smaller levels.

Each fault level has one of three failure policies that describe the correct behavior when the level fails:

### Redundant:

Redundant means that fault domains within the level can take over responsibility for a failed domain's responsibilities. Some examples here are nodes in a Cassandra or Memcache cluster, or an architecture design that supports the loss of an AWS Availability Zone. (With one or fewer health domains in within a redundant level, it follows the behavior described below under the cascade policy.)

### Ignorable:

Ignorable requires that fault levels higher in the fault hierarchy can continue operating if this fault level fails. An example might be a website that can annotate stories with social actions by your friends, but which stops showing that social context if the database they're stored in becomes unavailable, while continuing to render the remainder of the page.

### Cascade:

Cascade warns that when this fault level fails, it is neither redundant nor ignorable, and consequently the fault level above it in the fault hierarchy must take responsibility for the failure. Any single point of failure is going to operate this way, for example a traditional MySQL setup without automated failover would cascade, as would a Cassandra cluster running with read-majority configuration which was no longer able to complete majority reads.

## Usage: 
You can use PowerShell or XML markup to specify fault domains. Both approaches are equivalent and provide full functionality.


## Design decision: 

When designing very large vSAN clusters, consider using fault domains as a way of avoiding single rack failures impacting all replicas belonging to a virtual machine. Also, consider the additional resources and capacity requirements needed to rebuild components in the event of a failure.

There should be a strategy and an operational run book for how maintenance will be performed for the environment. Design for one of the following:

If Total Fault Domains = Required Fault Domains to satisfy policy:
- Only one host at a time should enter maintenance mode.
- Capacity Used on any one host in the fault domain must be less than Total Free Space across all other hosts in that same fault domain.

Spare capacity may be calculated as follows, where:

D= number of hosts in Fault Domain
T= number of hosts to put into maintenance (or hosts to tolerate the failure of... the ‘Tolerance’ value)
A= active data per host
(Active data per host x Number of hosts to put into maintenance)
divided by
(number of hosts in the fault domain – hosts to be put in maintenance mode)

## Calculating Capacity Tolerance – Across Fault Domains
If the number of configured Fault Domains exceeds the required Fault Domains as indicated by policy, and there is insufficient capacity within the fault domain to ingest evacuated data, it is possible to burden the additional fault domains with the extra capacity. Therefore capacity calculations must include the number of available or extra fault domains, and determine the amount of spare capacity the hosts in those fault domains must have to ingest the data from the hosts in maintenance mode.

Spare capacity may be calculated as follows, where:

F= number of total Fault Domains
R= number of required fault domains to satisfy the policy
D= number of hosts in Fault Domain
T= number of hosts to put into maintenance (or hosts to tolerate the failure of... your ‘Tolerance’ value)
A= active data per host
(Active data per host x Number of hosts to put into maintenance)
divided by
(total fault domains – fault domains required) x (number of hosts in each fault domain)

## Benefits:

### - Storage Spaces, including Storage Spaces Direct, uses fault domains to maximize data safety.
Resiliency in Storage Spaces is conceptually like distributed, software-defined RAID. Multiple copies of all data are kept in sync, and if hardware fails and one copy is lost, others are recopied to restore resiliency. To achieve the best possible resiliency, copies should be kept in separate fault domains.

### - The Health Service uses fault domains to provide more helpful alerts.
Each fault domain can be associated with location metadata, which will automatically be included in any subsequent alerts. These descriptors can assist operations or maintenance personnel and reduce errors by disambiguating hardware.

### - Stretch clustering uses fault domains for storage affinity. 
Stretch clustering allows faraway servers to join a common cluster. For the best performance, applications or virtual machines should be run on servers that are nearby to those providing their storage. Fault domain awareness enables this storage affinity.
