## Date: June 22, 2020

# What is Serverless Computing ?

##### Ans.

![](https://image.shutterstock.com/image-illustration/serverless-computing-concept-blurred-background-600w-1481297228.jpg)

- Serverless computing is a method of providing backend services on an as-used basis.

- A Serverless architecture allows users to write and deploy code without the hassle of worrying about the underlying infrastructure

- A company that gets backend services from a serverless vendor is charged based on their computation and do not have to reserve and pay for a fixed amount of bandwidth or number of servers, as the service is auto-scaling.

- Note that although called serverless, physical servers are still used but developers do not need to be aware of them.

# What are the advantages of serverless computing ?

### Lower costs :
Serverless computing is generally very cost-effective, as traditional cloud providers of backend services (server allocation) often result in the user paying for unused space or idle CPU time.

### Simplified scalability :
Developers using serverless architecture don’t have to worry about policies to scale up their code. The serverless vendor handles all of the scaling on demand.

### Simplified backend code :
With FaaS, developers can create simple functions that independently perform a single purpose, like making an API call.

### Quicker turnaround :
Serverless architecture can significantly cut time to market. Instead of needing a complicated deploy process to roll out bug fixes and new features, developers can add and modify code on a piecemeal basis.

_ _ _ _ _ _ _ _ _ _

# What are the benefits of using Storage in the cloud ?

##### Ans.

### 1. Cloud Storage Can Save Costs :
- Economies of scale. Cloud vendors buy a lot of storage and pass those savings onto customers. But it’s more than a low per-GB cost that provides savings.

- Moving to the cloud reduces the need to purchase hard disks, the enclosures that contain them, the RAID cards that power the data redundancy, the electricity that powers them, and the hardware warranty services that protect them

- But it also lowers management costs by reducing on-premise hardware and software management, simplifying monitoring, and reducing the need for extensive capacity planning. Instead, administrators can focus on other, more important, tasks.

### 2. Data Redundancy and Replication :
- Data redundancy is included. Most cloud storage vendors keep multiple copies of your data even within a single “data center” and offer great object durability to reduce any likelihood of data loss.

- But for those looking for even more protection, geographic replication options can make multiple copies of your data across regions.

- Some offer geo replication as a storage class option, while others offer replication services that quickly move data between data centers. Your backups are well protected.

### 3. Data Tiering for Cost Savings :
- Many cloud storage vendors offer different storage classes / data tiers. Select based on how quickly and frequently you restore backups and how long you plan to keep your backups in storage.

-  For backups that need quick and/or frequent restores, consider using the vendor’s hot storage as retrieval is fast and the most cost-effective. For long-term storage, consider moving data to archive storage.

- Restores can be slower, and there might be additional costs to retrieve data, but the storage costs are considerably lower – especially if you plan to keep the backups for years. Some vendors offer object lifecycle policies that can automatically move data between tiers, which reduces administration and lets you more easily realize cost savings.

### 4. Regulatory Compliance :
- Keeping your backups in the same region as where the data originates may be best for regulatory compliance. Many cloud vendors offer data centers options all around the globe.

- If you have a need to store your EU customer data in an EU data center, look for a cloud storage vendor that can accommodate.

- An added benefit is that moving data to cloud storage in the same region is best for performance. Even if you’re not bound by regulation, you may find the improved performance worthwhile.

### 5. Ransomware/Malware Protection :
- Ransomware is just bad. Unfortunately, it’s also in the news with great frequency. One of the more sinister ransomware attributes is that the malware will look beyond the locally infected computer to the network for shares that have documents and files to encrypt.

-  If you’re hit by ransomware or some other malware that is encrypting or destroying files, you might be happy that your cloud storage can help to protect against ransomware by offering some backup security advantages as it’s more difficult to access without proper authentication.

_ _ _ _ _ _ _ _ _ _

# Types of Storage :

There are three types of cloud data storage : object storage, file storage, and block storage. Each offers their own advantages and have their own use cases:

### Object Storage :
Applications developed in the cloud often take advantage of object storage's vast scalablity and metadata characteristics.

### File Storage :
Some applications need to access shared files and require a file system. This type of storage is often supported with a Network Attached Storage (NAS) server. File storage solutions like Amazon Elastic File System (EFS) are ideal for use cases like large content repositories, development environments, media stores, or user home directories.

### Block Storage :
Other enterprise applications like databases or ERP systems often require dedicated, low latency storage for each host. This is analagous to direct-attached storage (DAS) or a Storage Area Network (SAN). Block-based cloud storage solutions like Amazon Elastic Block Store (EBS) are provisioned with each virtual server and offer the ultra low latency required for high performance workloads.

_ _ _ _ _ _ _ _ _ _

# What is Latency ?

##### Ans. 

![](https://akfpartners.com//uploads/blog/latency-definition.jpg)

- Latency is a time interval between the stimulation and response, or, from a more general point of view, a time delay between the cause and the effect of some physical change in the system being observed.

- Latency is physically a consequence of the limited velocity with which any physical interaction can propagate. The magnitude of this velocity is always less than or equal to the speed of light.

- Therefore, every physical system with any physical separation (distance) between cause and effect will experience some sort of latency, regardless of the nature of stimulation that it has been exposed to.

- The precise definition of latency depends on the system being observed and the nature of stimulation. In communications, the lower limit of latency is determined by the medium being used for communications.

- In reliable two-way communication systems, latency limits the maximum rate that information can be transmitted, as there is often a limit on the amount of information that is "in-flight" at any one moment. In the field of human–machine interaction, perceptible latency has a strong effect on user satisfaction and usability.

_ _ _ _ _ _ _ _ _ _

# What are Load Balancers ?

##### Ans.

![](https://vexxhost.com/wp-content/uploads/2017/08/load-balancer-blog.jpg)

- Cloud load balancing is defined as the method of splitting workloads and computing properties in a cloud computing.

- It enables enterprise to manage workload demands or application demands by distributing resources among numerous computers, networks or servers.

- Cloud load balancing includes holding the circulation of workload traffic and demands that exist over the Internet.

- Load balancing solutions can be categorized into two types :

#### 1.Software-based load balancers :
Software-based load balancers run on standard hardware (desktop, PCs) and standard operating systems.

#### 2. Hardware-based load balancer :
Hardware-based load balancers are dedicated boxes which include Application Specific Integrated Circuits (ASICs) adapted for a particular use.

_ _ _ _ _ _ _ _ _ _

# What is a VNet ?

##### Ans.

- An Azure Virtual Network (VNet) is a representation of your own network in the cloud. It is a logical isolation of the Azure cloud dedicated to your subscription.

- Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. VNet enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks.

- VNet is similar to a traditional network that you'd operate in your own data center, but brings with it additional benefits of Azure's infrastructure such as scale, availability, and isolation.

## VNet concepts :

#### 1. Address space :
When creating a VNet, you must specify a custom private IP address space using public and private (RFC 1918) addresses. Azure assigns resources in a virtual network a private IP address from the address space that you assign.

#### 2. Subnets :
Subnets enable you to segment the virtual network into one or more sub-networks and allocate a portion of the virtual network's address space to each subnet. You can then deploy Azure resources in a specific subnet.

#### 3. Regions :
VNet is scoped to a single region/location; however, multiple virtual networks from different regions can be connected together using Virtual Network Peering.

#### 4. Subscription :
VNet is scoped to a subscription. You can implement multiple virtual networks within each Azure subscription and Azure region.

_ _ _ _ _ _ _ _ _ _
