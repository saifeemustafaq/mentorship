## Date: June 22, 2020

# Azure Regions  
Azure has more global regions than any other cloud provider—offering the scale needed to bring applications closer to users around the world, preserving data residency and offering comprehensive compliance and resiliency options for customers. Microsoft Azure is available in 36 regions globally, with 6 additional regions in the works to be added soon. (At least at the time of writing this article; Microsoft keeps investing and building new regions. It’s growing!) These Azure Regions are basically geographic groupings of 2, 3, or more datacenters. When provisioning any cloud resource within Microsoft Azure it must be placed in, and reside within, an Azure Region.

### Understand Azure global infrastructure  

- #### Regions:  
A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network.

With more global regions than any other cloud provider, Azure gives customers the flexibility to deploy applications where they need to. Azure is generally available in 53 regions around the world, with plans announced for 7 additional regions.  

- #### Geographies: 
A geography is a discrete market, typically containing two or more regions, that preserves data residency and compliance boundaries.

Geographies allow customers with specific data-residency and compliance needs to keep their data and applications close. Geographies are fault-tolerant to withstand complete region failure through their connection to our dedicated high-capacity networking infrastructure.  

- #### Availability Zones:  
Availability Zones are physically separate locations within an Azure region. Each Availability Zone is made up of one or more datacenters equipped with independent power, cooling and networking.

Availability Zones allow customers to run mission-critical applications with high availability and low-latency replication.  

For a long time the most granular control you had of where to host resources within Microsoft Azure was at the Azure Region level. With Azure Availability Zones you can choose which Zone within that Azure Region to host a resource. This enables a more granular choice of where and how to host resources within an Azure Region.Each Zone within an Azure Region is essentially a separate datacenter. Each Zone has independent power source, networking, cooling, etc. Each Azure Region with Availability Zones made available will have at minimum 3 separate Zones. This is to ensure maximum resilience and high availability can be enabled within the Azure Region.  

- ####  Datacenters:  
A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network. Also, you can see Availability Zone might also have several datacenters. So region or AZ means there is a datacenter, but it doesn’t means there is only one datacenter.

- #### Paired Regions:  
Across the region pairs Azure serializes platform updates (planned maintenance), so that only one paired region is updated at a time. In the event of an outage affecting multiple regions, at least one region in each pair will be prioritized for recovery.

