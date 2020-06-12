## Date: June 12, 2020

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
