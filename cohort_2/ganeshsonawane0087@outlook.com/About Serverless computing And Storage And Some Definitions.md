 Date:August 9,2020 
# What is Serverless Computing ?

- Serverless computing is a method of providing backend services on an as-used basis.

- A Serverless architecture allows users to write and deploy code without the hassle of worrying about the underlying infrastructure

- A company that gets backend services from a serverless vendor is charged based on their computation and do not have to reserve and pay for a fixed amount of bandwidth or number of servers, as the service is auto-scaling.

- Note that although called serverless, physical servers are still used but developers do not need to be aware of them.

## What are the advantages of serverless computing ?
### Lower costs :
Serverless computing is generally very cost-effective, as traditional cloud providers of backend services (server allocation) often result in the user paying for unused space or idle CPU time.

### Simplified scalability :
Developers using serverless architecture don’t have to worry about policies to scale up their code. The serverless vendor handles all of the scaling on demand.

### Simplified backend code :
With FaaS, developers can create simple functions that independently perform a single purpose, like making an API call.

### Quicker turnaround :
Serverless architecture can significantly cut time to market. Instead of needing a complicated deploy process to roll out bug fixes and new features, developers can add and modify code on a piecemeal basis.

# What are the benefits of using Storage in the cloud ?
Ans.
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

- For backups that need quick and/or frequent restores, consider using the vendor’s hot storage as retrieval is fast and the most cost-effective. For long-term storage, consider moving data to archive storage.

- Restores can be slower, and there might be additional costs to retrieve data, but the storage costs are considerably lower – especially if you plan to keep the backups for years. Some vendors offer object lifecycle policies that can automatically move data between tiers, which reduces administration and lets you more easily realize cost savings.

### 4. Regulatory Compliance :
- Keeping your backups in the same region as where the data originates may be best for regulatory compliance. Many cloud vendors offer data centers options all around the globe.

- If you have a need to store your EU customer data in an EU data center, look for a cloud storage vendor that can accommodate.

- An added benefit is that moving data to cloud storage in the same region is best for performance. Even if you’re not bound by regulation, you may find the improved performance worthwhile.

### 5. Ransomware/Malware Protection :
- Ransomware is just bad. Unfortunately, it’s also in the news with great frequency. One of the more sinister ransomware attributes is that the malware will look beyond the locally infected computer to the network for shares that have documents and files to encrypt.

- If you’re hit by ransomware or some other malware that is encrypting or destroying files, you might be happy that your cloud storage can help to protect against ransomware by offering some backup security advantages as it’s more difficult to access without proper authentication.

# Types of Storage :
- There are three types of cloud data storage : object storage, file storage, and block storage. Each offers their own advantages and have their own use cases:

### Object Storage :
Applications developed in the cloud often take advantage of object storage's vast scalablity and metadata characteristics.

### File Storage :
Some applications need to access shared files and require a file system. This type of storage is often supported with a Network Attached Storage (NAS) server. File storage solutions like Amazon Elastic File System (EFS) are ideal for use cases like large content repositories, development environments, media stores, or user home directories.

### Block Storage :
Other enterprise applications like databases or ERP systems often require dedicated, low latency storage for each host. This is analagous to direct-attached storage (DAS) or a Storage Area Network (SAN). Block-based cloud storage solutions like Amazon Elastic Block Store (EBS) are provisioned with each virtual server and offer the ultra low latency required for high performance workloads.
