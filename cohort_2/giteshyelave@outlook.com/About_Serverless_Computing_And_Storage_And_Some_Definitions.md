## Date: June 22, 2020

# What is Serverless Computing ?

##### Ans.

![](https://image.shutterstock.com/image-illustration/serverless-computing-concept-blurred-background-600w-1481297228.jpg)

- Serverless computing is a cloud computing execution model in which the cloud provider runs the server, and dynamically manages the allocation of machine resources. Pricing is based on the actual amount of resources consumed by an application, rather than on pre-purchased units of capacity. It can be a form of utility computing.

- Serverless computing can simplify the process of deploying code into production.

- Scaling, capacity planning and maintenance operations may be hidden from the developer or operator.

- Serverless code can be used in conjunction with code deployed in traditional styles, such as microservices. Alternatively, applications can be written to be purely serverless and use no provisioned servers at all.

# Advantages :

### Cost :
Serverless can be more cost-effective than renting or purchasing a fixed quantity of servers, which generally involves significant periods of underutilization or idle time. It can even be more cost-efficient than provisioning an autoscaling group, due to more efficient bin-packing of the underlying machine resources.

### Elasticity versus scalability :
In addition, a serverless architecture means that developers and operators do not need to spend time setting up and tuning autoscaling policies or systems; the cloud provider is responsible for scaling the capacity to the demand. As Google puts it: from prototype to production to planet-scale.

### Productivity
With function as a service, the units of code exposed to the outside world are simple event driven functions.

_ _ _ _ _ _ _ _ _ _

# What are the benefits of using Storage in the cloud ?

##### Ans.

### 1. Usability and Accessibility :
- Users can easily drag and drop the files in the coud storage. It is easy to save all the files and data in the cloud, no technology is required for this purpose.

- The stored files can be easily accessed from anywhere in the world with just a few clicks and an internet connection.

### 2. Disaster recovery :
- It is recommended for every business to have a backup plan in case of any emergency.

- After all, losing important business data can cause huge losses to any business.

- Cloud storage is the perfect backup plan for business. It creates a backup of the files stored.

- These files are stored at a remote location and they can be retrieved and accessed at any time.

### 3. Security :
- Business owners can be sure that once the data is stored in the cloud, it is safe.

- The best thing about using cloud storage is that server data is distributed across redundant servers and the data stored in the cloud is safeguard against any type of hardware failure.

- Cloud servers also provide automated backups and snapshots in order to make sure that your data is safe.

### 4. Cost Sharing :
- Business and organizations can reduce annual operating costs by utilising cloud storage.

- Affordability can be ensured if data is stored online in the cloud. 

- Users can ensure additional cost savings because internal power and resources are not required separately for storing the data.

### 5. Easy sharing :
- Data stored in cloud storage can be easily shared with clients and colleagues in an easy and secure way.

- You can easily share access to a particular cloud environment or to a complete account with some other user.

_ _ _ _ _ _ _ _ _ _

# Types of Storage :

There are three types of cloud data storage :

### File Storage :
Some applications need to access shared files and require a file system. This type of storage is often supported with a Network Attached Storage (NAS) server. File storage solutions like Amazon Elastic File System (EFS) are ideal for use cases like large content repositories, development environments, media stores, or user home directories.

### Block Storage :
Other enterprise applications like databases or ERP systems often require dedicated, low latency storage for each host. This is analagous to direct-attached storage (DAS) or a Storage Area Network (SAN). Block-based cloud storage solutions like Amazon Elastic Block Store (EBS) are provisioned with each virtual server and offer the ultra low latency required for high performance workloads.

### Object Storage :
Applications developed in the cloud often take advantage of object storage's vast scalablity and metadata characteristics.

_ _ _ _ _ _ _ _ _ _

# What is Latency ?

##### Ans. 

![](https://akfpartners.com//uploads/blog/latency-definition.jpg)

- In computing, "latency" describes some type of delay. It typically refers to delays in transmitting or processing data, which can be caused by a wide variety of reasons.

- Two examples of latency are network latency and disk latency, which are explained below.

#### 1. Network latency :
Network latency describes a delay that takes place during communication over a network (including the Internet).  
The "ping" response time is a good indicator of the latency in this situation.

#### 2. Disk latency :
Disk latency is the delay between the time data is requested from a storage device and when the data starts being returned. Factors that effect disk latency include the rotational latency (of a hard drive) and the seek time.

_ _ _ _ _ _ _ _ _ _

# What are Load Balancers ?

##### Ans.

- Cloud load balancing is a type of load balancing that is performed in cloud computing. Cloud load balancing is the process of distributing workloads across multiple computing resources.

- Cloud load balancing reduces costs associated with document management systems and maximizes availability of resources.

- It is a type of load balancing and not to be confused with Domain Name System (DNS) load balancing. While DNS load balancing uses software or hardware to perform the function, cloud load balancing uses services offered by various computer network companies.

- Load balancing solutions can be categorized into two types :

#### 1. Hardware-based load balancer :
Hardware-based load balancers are dedicated boxes which include Application Specific Integrated Circuits (ASICs) adapted for a particular use.

#### 2.Software-based load balancers :
Software-based load balancers run on standard hardware (desktop, PCs) and standard operating systems.

_ _ _ _ _ _ _ _ _ _

# What is a VNet ?

##### Ans.

- Azure Virtual Network allows many types of Azure resources, such as Azure virtual machines (VMs), to communicate securely with each other, with the Internet, and with local networks.

- The scope of a virtual network is a single region; however, several virtual networks of different regions can be connected together by virtual network pairing.

- A virtual network is nothing but, like On-premises network which we use switches and routers to communicate with servers and clients as same as Azure VNet is also used for communicating with azure resources.

- Per Subscription is limited to a 100 VNets and can’t extend more than 100. 

- VNet is isolated, all resources within VNet can communicate with each other or not based on our configuration in user-defined routes and Network Security Groups.

- VNETs are at the heart of network architecture on Azure. A VNET is the address space. It hosts subnet, where you will connect resources. Subnet segment the address space into multiple subnetworks.

- The design of these VNETs for an application, a project, a subscription or for the entire enterprise is important.

- An Azure VNet is a representation of a network in the cloud and is logical isolation of the Azure cloud dedicated to a subscription.

_ _ _ _ _ _ _ _ _ _
