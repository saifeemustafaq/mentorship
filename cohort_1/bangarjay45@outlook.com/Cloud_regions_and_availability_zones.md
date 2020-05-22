> # **Cloud regions and availability zones**


- Region, like the name indicates, is a separate geographic area.
- Within each region there are multiple, isolated locations: Availability Zones. 
- AZs have independent power sources, computing, networking, and cooling resources. 
- Typically, especially if you’re new to the public cloud, your presence will be on a single AZ.

## What is a region?
- The simplest explanation is that a “cloud region” describes the actual, real-life geographic location where your public cloud resources are located.
- Regions allow you to locate your cloud resources close to your customers, both internal or external. 
- The closer your customers are to the region where your cloud resources are located, the faster and better their experience will be.

### How to choose a *region*


#### Latency

- Latency is ex. 
  - If you have a low latency connection, there’s little to no lag.
  - But if you have a high latency connection, there's continuous lagging which can be troublesome.
- If your data center is in Thailand and your customers are in Arizona, they’re going to experience latency simply due to distance.
- So, the first thing you need to do is determine where most of your customers are and choose a region that’s closest to them.
- On such basis regions are determined.

#### Cost

- It costs money to run data centers, energy costs, and taxes, a cloud region can cost more money in some areas than in others.
- For instance, a cloud region in the X area may cost more than a cloud region in Y because all those differences in real estate prices.
- A few cloud region can be less expensive.
- So a more expensive region will equal higher costs on your pocket.

#### Compliance and security

- Every company has different security requirements based on its industry, location, etc. 
- It’s also important to know what the compliance laws in your country so that you donnt face any difficulty. 

#### Computing and processor features

- What’s inside the data center matters as much as where the center is located. 
- If you require the latest, most up-to-date compute and processing, you would wannt a cloud provider that has the most lastest hardware. 
- If you really want cutting-edge speed and power, you may need to look for a provider that uses Top-notch processors.

#### Services and features

- Services vary region by region. 
- You’ll notice the difference in features that cloud provides varies widely.
- Therefore the features and services should be checked as you begin your cloud provider hunt

#### Disaster recovery

- Having a down network could cost your business a huge amount of money, so Disaster recovery is important. 
- Some companies have many data centers in the same region.
- Regions are also commonly used as part of disaster recovery (DR) strategy
- Each region is designed to be completely isolated from the other regions. 
- If a earthquake like disaster hit's AWS’s US any region, say 'west' region, the other regions would be still running.


**Important points:**
- A region is not an Availability zone.
- A region must have at least one AZ within it, but they’re often made up of multiple ones. 
- For example, Amazon Web Services (AWS)‘s US East region is made up of six availability zones.
