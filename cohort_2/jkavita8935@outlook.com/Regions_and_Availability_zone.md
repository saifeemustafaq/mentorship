

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
   
