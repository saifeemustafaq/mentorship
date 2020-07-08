> # This blog is part of the **[Cloudyman Mentorship Program](https://t.co/78sRvCvYiO?amp=1)** under the mentorship of *[Mustafa Saifee](https://www.linkedin.com/in/saifeemustafaq/)*

## Date: June  15, 2020

# Amazon web services (AWS)


![](https://www.comparethecloud.net/wp-content/uploads/2017/11/Amazon-Web-Services-2-min.jpg)



--------
- **AWS** (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage and content delivery services.

- **AWS** launched in 2006 from the internal infrastructure that Amazon.com built to handle its online retail operations. AWS was one of the first companies to introduce a pay-as-you-go cloud computing model that scales to provide users with compute, storage or throughput as needed.

- **AWS** offers many different tools and solutions for enterprises and software developers that can be used in data centers in up to 190 countries. Groups such as government agencies, education institutions, nonprofits and private organizations can use AWS services.
--------


|CEO:| Andy Jassy (Apr 2016–)|
|-------|---------------|
|Founder: |[Amazon.com]( |
|Founded:| 2006|
|Headquarters: |Seattle, Washington, United States|
|Subsidiaries:| CloudEndure, TeamSQL, Inc., AWS Elemental, Sqrrl, OpenSCG, Inc., Harvest.ai, more|
|Parent organization: |Amazon.com|

-------

## How AWS works.

- AWS is separated into different services; each can be configured in different ways based on the user's needs. Users should be able to see configuration options and individual server maps for an AWS service.

- More than 100 services comprise the Amazon Web Services portfolio, including those for compute, databases, infrastructure management, application development and security. These services, by category, include:



------
- **Computer
- **Storage databases
- **Data management
- **Migration
- **Hybrid cloud
- **Networking
- **Development tools
- **Management
- **Monitoring
- **Security
- **Governance
- **Big data management
- **Analytics
- **Artificial intelligence (AI)
- **Mobile development
- **Messages and notification

------+

### Availability:

- Amazon Web Services provides services from dozens of data centers spread across availability zones (AZs) in regions across the world. An AZ is a location that contains multiple physical data centers. A region is a collection of AZs in geographic proximity connected by low-latency network links.

- A business will choose one or multiple availability zones for a variety of reasons, such as compliance and proximity to end customers. For example, an AWS customer can spin up virtual machines (VMs) and replicate data in different AZs to achieve a highly reliable infrastructure that is resistant to failures of individual servers or an entire data center.

- **Amazon Elastic Compute Cloud (EC2)** is a service that provides virtual servers -- called EC2 instances -- for compute capacity. The EC2 service offers dozens of instance types with varying capacities and sizes, tailored to specific workload types and applications, such as memory-intensive and accelerated-computing jobs. AWS also provides an Auto Scaling tool to dynamically scale capacity to maintain instance health and performance.
---------+

### Storage:

- Amazon Simple Storage Service (S3) provides scalable object storage for data backup, collection and analytics. An IT professional stores data and files as S3 objects -- which can range up to 5 gigabytes (GB) -- inside S3 buckets to keep them organized. A business can save money with S3 through its Infrequent Access storage tier or by using Amazon Glacier for long-term cold storage.

- Amazon Elastic Block Store provides block-level storage volumes for persistent data storage when using EC2 instances. Amazon Elastic File System offers managed cloud-based file storage.

- A business can also migrate data to the cloud via storage transport devices, such as AWS Snowball and Snowmobile, or use AWS Storage Gateway to enable on-premises apps to access cloud data.
---------

## Databases, data management:

- The Amazon Relational Database Service -- which includes options for Oracle, SQL Server, PostgreSQL, MySQL, MariaDB and a proprietary high-performance database called Amazon Aurora -- provides a relational database management system for AWS users. AWS also offers managed NoSQL databases through Amazon DynamoDB.

- An AWS customer can use Amazon ElastiCache and DynamoDB Accelerator as in-memory and real-time data caches for applications. Amazon Redshift offers a data warehouse, which makes it easier for data analysts to perform business intelligence (BI) tasks.
--------

### Migration, hybrid cloud:

- AWS includes various tools and services designed to help users migrate applications, databases, servers and data onto its public cloud. The AWS Migration Hub provides a location to monitor and manage migrations from on premises to the cloud. Once in the cloud, EC2 Systems Manager helps an IT team configure on-premises servers and AWS instances.

- Amazon also has partnerships with several technology vendors that ease hybrid cloud deployments. VMware Cloud on AWS brings software-defined data center technology from VMware to the AWS cloud. Red Hat Enterprise Linux for Amazon EC2 is the product of another partnership, extending Red Hat's operating system to the AWS cloud.

-------

### Networking;

- An Amazon Virtual Private Cloud (Amazon VPC) gives an administrator control over a virtual network to use an isolated section of the AWS cloud. AWS automatically provisions new resources within a VPC for extra protection.

- Admins can balance network traffic with the Elastic Load Balancing (ELB) service, which includes the Application Load Balancer and Network Load Balancer. AWS also provides a domain name system called Amazon Route 53 that routes end users to applications.

- An IT professional can establish a dedicated connection from an on-premises data center to the AWS cloud via AWS Direct Connect.
-------

### Developer tools:

- A developer can take advantage of AWS command-line tools and software development kits (SDKs) to deploy and manage applications and services. This includes:

- The AWS Command Line Interface, which is Amazon's proprietary code interface.
A developer can use AWS Tools for Powershell to manage cloud services from Windows environments.
Developers can use AWS Serverless Application Model to simulate an AWS environment to test Lambda functions.
AWS SDKs are available for a variety of platforms and programming languages, including Java, PHP, Python, Node.js, Ruby, C++, Android and iOS.

- Amazon API Gateway enables a development team to create, manage and monitor custom application program interfaces (APIs) that let applications access data or functionality from back-end services. API Gateway manages thousands of concurrent API calls at once.  

- AWS also provides a packaged media transcoding service -- Amazon Elastic Transcoder -- and a service that visualizes workflows for microservices-based applications -- AWS Step Functions.

- A development team can also create continuous integration and continuous delivery pipelines with services like:

- [AWS CodePipeline](https://searchaws.techtarget.com/definition/AWS-CodePipeline-Amazon-Web-Services-CodePipeline?_gl=1*17ogg3i*_ga*cHgyZGVzeFdzSWY5ZkJfa0xucThhTnI3eVlBdkx0b1NDaGkxaXBIc3U3QXhOcUZGd043R3hfQlFfTUxGSUNMWA)
- [AWS CodeBuild](https://searchaws.techtarget.com/definition/AWS-CodeBuild?_gl=1*1ilbk02*_ga*cHgyZGVzeFdzSWY5ZkJfa0xucThhTnI3eVlBdkx0b1NDaGkxaXBIc3U3QXhOcUZGd043R3hfQlFfTUxGSUNMWA..)
- [AWS CodeDeploy](https://searchitoperations.techtarget.com/definition/AWS-CodeDeploy-Amazon-Web-Services-CodeDeploy?_gl=1*1ilbk02*_ga*cHgyZGVzeFdzSWY5ZkJfa0xucThhTnI3eVlBdkx0b1NDaGkxaXBIc3U3QXhOcUZGd043R3hfQlFfTUxGSUNMWA..)
- [AWS CodeStar](https://searchaws.techtarget.com/definition/AWS-CodeStar?_gl=1*1ilbk02*_ga*cHgyZGVzeFdzSWY5ZkJfa0xucThhTnI3eVlBdkx0b1NDaGkxaXBIc3U3QXhOcUZGd043R3hfQlFfTUxGSUNMWA..)
A developer can also store code in Git repositories with AWS CodeCommit and evaluate the performance of microservices-based applications with AWS X-Ray.

-------

### Management and monitoring:

- An admin can manage and track cloud resource configuration via AWS Config and AWS Config Rules. Those tools, along with AWS Trusted Advisor, can help an IT team avoid improperly configured and needlessly expensive cloud resource deployments.

- AWS provides several automation tools in its portfolio. An admin can automate infrastructure provisioning via AWS CloudFormation templates, and also use AWS OpsWorks and Chef to automate infrastructure and system configurations.

- An AWS customer can monitor resource and application health with Amazon CloudWatch and the AWS Personal Health Dashboard, as well as  use AWS CloudTrail to retain user activity and API calls for auditing.

---------

### Security and governance:

-AWS provides a range of services for cloud security, including AWS Identity and Access Management, which allows admins to define and manage user access to resources. An admin can also create a user directory with Amazon Cloud Directory, or connect cloud resources to an existing Microsoft Active Directory with the AWS Directory Service. Additionally, the AWS Organizations service enables a business to establish and manage policies for multiple AWS accounts.

- Amazon Web Services has also introduced tools that automatically assess potential security risks. Amazon Inspector analyzes an AWS environment for vulnerabilities that might impact security and compliance. Amazon Macie uses machine learning (ML) technology to protect sensitive cloud data.

- AWS also includes tools and services that provide software- and hardware-based encryption, protect against DDoS attacks, provision Secure Sockets Layer (SSL) and Transport Layer Security (TLS) certificates and filter potentially harmful traffic to web applications.

- The AWS Management Console is a browser-based graphical user interface (GUI) for AWS. The Management Console can be used to manage resources in cloud computing, cloud storage and security credentials. The AWS Console interfaces with all AWS resources.
-----------

### Big data management and analytics

- AWS includes a variety of big data analytics and application services. This includes:

-Amazon Elastic MapReduce, which offers a Hadoop framework to process large amounts of data.
- Amazon Kinesis, which provides several tools to process and analyze streaming data.
- AWS Glue, which is a service that handles extract, transform and load jobs.
- Amazon Elasticsearch Serviceenables a team to perform application monitoring, log analysis and other tasks with the open source Elasticsearch tool.
- Amazon Athena for S3, which allows analysts to query data.
- Amazon QuickSight, which help analysts visualize data.

---------

### Artificial intelligence:

- AWS offers a range of AI model development and delivery platforms, as well as packaged AI-based applications. The Amazon AI suite of tools includes:

- Amazon Lex for voice and text chatbot technology;
- Amazon Polly for text-to-speech translation; and 
- Amazon Rekognition for image and facial analysis.
- AWS also provides technology for developers to build smart apps that rely on machine learning technology and complex algorithms.

- With AWS Deep Learning Amazon Machine Images (AMIs), developers can create and train custom AI models with clusters of graphics processing units (GPUs) or compute-optimized instances. AWS also includes deep learning development frameworks for MXNet and TensorFlow.

- On the consumer side, AWS technologies power the Alexa Voice Services, and a developer can use the Alexa Skills Kit to build voice-based apps for Echo devices.

-----------

### Mobile development:

- The AWS Mobile Hub offers a collection of tools and services for mobile app developers, including the AWS Mobile SDK, which provides code samples and libraries.

- A mobile app developer can also use Amazon Cognito to manage user access to mobile apps, as well as Amazon Pinpoint to send push notifications to application end users and then analyze the effectiveness of those communications.


----------

### Messages and notifications:

- AWS messaging services provide core communication for users and applications. Amazon Simple Queue Service (SQS) is a managed message queue that sends, stores and receives messages between components of distributed applications to ensure that the parts of an application work as intended.

- Amazon Simple Notification Service (SNS) enables a business to send publish/subscribe messages to endpoints, such as end users or services. SNS includes a mobile messaging feature that enables push messaging to mobile devices. Amazon Simple Email Service (SES) provides a platform for IT professionals and marketers to send and receive emails.

- AR & VR (Augmented reality and virtual reality)
AWS offers augmented reality (AR) and virtual reality (VR) development tools through the Amazon Sumerian service. Amazon Sumerian allows users to create AR and VR applications without needing to know programming or create 3D graphics. The service also enables users to test and publish applications in-browser. Amazon Sumerian can be used in:

- **[3D web applications]
- **[E-commerce & sales applications]
- **[Marketing]
- **[Online education]
- **[Manufacturing]
- **[Training simulations]
- **[Gaming]

-----------



-------+

## Date:16 June 20202
--------
## features and benefits of Amazon Web Services (EC2):


#### Functionality:

- Amazon EC2 presents a true virtual computing environment, allowing you to use web service interfaces to launch instances with a variety of operating systems, load them with your custom application environment, manage your network’s access permissions, and run your image using as many or few systems as you desire.
--------+

#### To use Amazon EC2, you simply:

- Select a pre-configured, templated Amazon Machine Image (AMI) to get up and running immediately. Or create an AMI containing your applications, libraries, data, and associated configuration settings.

- Configure security and network access on your Amazon EC2 instance.

- Choose which instance type(s) you want, then start, terminate, and monitor as many instances of your AMI as needed, using the web service APIs or the variety of management tools provided.

- Determine whether you want to run in multiple locations, utilize static IP endpoints, or attach persistent block storage to your instances.


- Pay only for the resources that you actually consume, like instance-hours or data transfer.
---------

## Features

- Amazon EC2 provides a number of powerful features for building scalable, failure resilient, enterprise class applications.

 ### Bare Metal instances
Amazon EC2 bare metal instances provide your applications with direct access to the processor and memory of the underlying server. These instances are ideal for workloads that require access to hardware feature sets (such as Intel® VT-x), or for applications that need to run in non-virtualized environments for licensing or support requirements. Bare metal instances are built on the Nitro system, a collection of AWS-built hardware offload and hardware protection components that come together to securely provide high performance networking and storage resources to EC2 instances. Bare metal instances are EC2 instances and thus offer the same robust security, reliability, capacity elasticity, and support for different operating systems and software packages as other virtual EC2 instances. You can also use bare metal instances with AWS services such as Amazon Virtual Private Cloud (VPC), Elastic Block Store (EBS), Elastic Load Balancing (ELB) and more.
Optimize Compute Performance and Cost with Amazon EC2 Fleet
With a single API call, Amazon EC2 Fleet lets you provision compute capacity across EC2 instance types, Availability Zones, and purchase models to help optimize scale, performance and cost. You can specify how much On-Demand and Spot capacity to launch via EC2 Fleet. You can also define which instance types you prefer and whether to scale capacity based on cores, instances or memory. Read FAQs and AWS blog to learn more. Now you can access EC2 Fleet capabilities via Amazon EC2 Auto Scaling to provision and automatically scale compute capacity across EC2 instance types, Availability Zones, and purchase options in a single Auto Scaling Group. Learn more>>
Pause and Resume Your Instances
You can hibernate your Amazon EC2 instances backed by Amazon EBS, and resume them from this state at a later time. Applications that take a while to bootstrap and persist state into memory (RAM) can benefit from this feature. Hibernation gives you all the benefits of Stop and Start, and additionally, data from memory (RAM) is also persisted between sessions. You will not be charged for instance usage while your instance is hibernated. Storage is charged at standard EBS rates. For more information about hibernation, and supported instance types and operating systems, visit the FAQs.
-------


### GPU Compute Instances
- Customers requiring massive floating point processing power will benefit from the next-generation of general-purpose GPU compute instances from AWS, Amazon EC2 P3 instances with up to 8 NVIDIA® V100 Tensor Core GPUs. P3 instances provide up to 1 petaFLOPS of mixed-precision, 125 teraFLOPS of single-precision and 62 teraFLOPS of double-precision floating point performance. A 300 GB/s second generation NVLink interconnect allows GPU-to-GPU communication at high speed and low latency. P3 instances also feature up to 96 vCPUs based on custom Intel processors, 768 GB of DRAM, and 100 Gbps of dedicated aggregate network bandwidth using the Elastic Network Adapter (ENA). P3 instances are ideally suited for machine learning, high-performance computing, computational fluid dynamics, computational finance, seismic analysis, molecular modeling, genomics, and rendering workloads.

------

### GPU Graphics Instances
Customers requiring high graphics capability will benefit from GPU graphics instances. The current generation GPU graphics instance, G3 instance, provides access to NVIDIA Tesla M60 GPUs, each with up to 2,048 parallel processing cores, 8 GiB of GPU memory and a hardware encoder supporting up to 10 H.265 (HEVC) 1080p30 streams and up to 18 H.264 1080p30 streams. With the latest driver releases, these GPUs provide support for OpenGL, DirectX, CUDA, OpenCL, and Capture SDK (formerly known as GRID SDK). GPU graphics instances are ideally suited for 3D visualizations, graphics-intensive remote workstation, 3D rendering, application streaming, video encoding, and other server-side graphics workloads.

--------

.
### High I/O Instances
Customers requiring very high, low latency, random I/O access to their data can benefit from High I/O instances. High I/O instances are an Amazon EC2 instance type that can provide customers with random I/O rates over 3 million IOPS. High I/O I3 and I3en instances are backed by Non-Volatile Memory Express (NVMe) based SSDs, and are ideally suited for customers running very high performance NoSQL databases, transactional systems, and Elastic Search workloads. High I/O instances also offer sequential disk throughput up to 16 GB/s, which is ideal for analytics workloads.

See Amazon EC2 Instance Types to find out more about High I/O instances.


-----;-

### Dense HDD Storage Instances
- Customers requiring very high storage density per instance, and high sequential I/O for data-intensive applications like Massively Parallel Processing (MPP) data warehouse, MapReduce and Hadoop distributed computing, and log and data processing can benefit from Dense Storage instances. Dense Storage instances are an Amazon EC2 instance type that can provide customers with sequential I/O throughout of up to 3.9 GB/s and provide customers with up to 48 TB of instance storage across 24 hard disk drives, or offer a balance with lesser storage and memory per vCPU with ENA based networking for up to 25 Gbps of Network Bandwidth within a placement group. See Amazon EC2 Instance Types to find out more about Dense Storage instances.

### Optimized CPU Configurations
The Optimize CPUs feature gives you greater control of your Amazon EC2 instances on two fronts. First, you can specify a custom number of vCPUs when launching new instances to save on vCPU-based licensing costs. Second, you can disable multithreading for workloads that perform well with single-threaded CPUs, such as certain high-performance computing (HPC) applications. To learn more about how Optimize CPUs can help you, visit the Optimize CPUs documentation here.



------------

# How AWS Shield works?




![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSCDrkSSSoMpEt1ATWDJ3jsuVKQYrPOeq_2NA&usqp=CAU)





|PDF|Kindle|RSS|
|--|---|----|


****A distributed denial of service (DDoS)**** attack is an attack in which multiple compromised systems attempt to flood a target, such as a network or web application, with traffic. A DDoS attack can prevent legitimate users from accessing a service and can cause the system to crash due to the overwhelming traffic volume.

AWS provides two levels of protection against DDoS attacks: AWS Shield Standard and AWS Shield Advanced.



## AWS Shield Standard


All AWS customers benef
it from the automatic protections of AWS Shield Standard, at no additional charge. AWS Shield Standard defends against most common, frequently occurring network and transport layer DDoS attacks that target your website or applications. While AWS Shield Standard helps protect all AWS customers, you get particular benefit if you are using Amazon CloudFront and Amazon Route 53. These services receive comprehensive availability protection against all known infrastructure (Layer 3 and 4) attacks.

### AWS Shield Advanced

For higher levels of protection against attacks, you can subscribe to AWS Shield Advanced. When you subscribe to AWS Shield Advanced and add specific resources to be protected, AWS Shield Advanced provides expanded DDoS attack protection for web applications running on the resources.

------------
- You can add protection for any of the following resources:

- Elastic Load Balancing (ELB) load balancers

- Amazon Elastic Compute Cloud (Amazon EC2) Elastic IP addresses

- Amazon CloudFront distributions

- Amazon Route 53 hosted zones

- AWS Global Accelerator accelerators


---------

For example, if you use Shield Advanced to protect an Elastic IP address, Shield Advanced automatically deploys your network ACLs to the border of the AWS network during an attack. When your network ACLs are at the border of the network, Shield Advanced can provide protection against larger DDoS events. Typically, network ACLs are applied near your Amazon EC2 instances within your Amazon VPC. The network ACL can mitigate attacks only as large as your Amazon VPC and instance can handle. If the network interface attached to your Amazon EC2 instance can process up to 10 Gbps, volumes over 10 Gbps slow down and possibly block traffic to that instance. During an attack, Shield Advanced promotes your network ACL to the AWS border, which can process multiple terabytes of traffic. Your network ACL is able to provide protection for your resource well beyond your network's typical capacity. For more information about network ACLs, see Network ACLs.

The point at which Shield Advanced detects attacks and places mitigations depends on the architecture you use for your web applications. It varies based on characteristics like the type of instance you use, your instance size, and whether you use enhanced networking.

As an AWS Shield Advanced customer, you can contact a 24x7 DDoS response team (DRT) for assistance during a DDoS attack. You also have exclusive access to advanced, real-time metrics and reports for extensive visibility into attacks on your AWS resources. With the assistance of the DRT, AWS Shield Advanced includes intelligent DDoS attack detection and mitigation for not only for ****network layer (layer 3) and transport layer (layer 4) attacks, but also for application layer (layer 7) attacks.****



-------
AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection. There are two tiers of AWS Shield - Standard and Advanced.

All AWS customers benefit from the automatic protections of AWS Shield Standard, at no additional charge. AWS Shield Standard defends against most common, frequently occurring network and transport layer DDoS attacks that target your web site or applications. When you use AWS Shield Standard with Amazon CloudFront and Amazon Route 53, you receive comprehensive availability protection against all known infrastructure (Layer 3 and 4) attacks.

For higher levels of protection against attacks targeting your applications running on Amazon Elastic Compute Cloud (EC2), Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator and Amazon Route 53 resources, you can subscribe to AWS Shield Advanced. In addition to the network and transport layer protections that come with Standard, AWS Shield Advanced provides additional detection and mitigation against large and sophisticated DDoS attacks, near real-time visibility into attacks, and integration with AWS WAF, a web application firewall. AWS Shield Advanced also gives you 24x7 access to the AWS DDoS Response Team (DRT) and protection against DDoS related spikes in your Amazon Elastic Compute Cloud (EC2), Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator and Amazon Route 53 charges.

AWS Shield Advanced is available globally on all Amazon CloudFront, AWS Global Accelerator, and Amazon Route 53 edge locations. You can protect your web applications hosted anywhere in the world by deploying Amazon CloudFront in front of your application. Your origin servers can be Amazon S3, Amazon Elastic Compute Cloud (EC2), Elastic Load Balancing (ELB), or a custom server outside of AWS. You can also enable AWS Shield Advanced directly on an Elastic IP or Elastic Load Balancing (ELB) in the following AWS Regions - Northern Virginia, Ohio, Oregon, Northern California, Montreal, São Paulo, Ireland, Frankfurt, London, Paris, Stockholm, Singapore, Tokyo, Sydney, Seoul, and Mumbai.

----

## Benefit
sSeamless integration and deployment
Your AWS resources automatically have AWS Shield Standard and are protected from common, most frequently occurring network and transport layer DDoS attacks. You can achieve a higher level of defense by simply enabling AWS Shield Advanced protection for Elastic IP, Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator, or Amazon Route 53 resources you want to protect using the management console or APIs. No routing changes are required for enabling these protections.


-----
## Customizable protection
With AWS Shield Advanced, you have the flexibility to choose the resources to protect for infrastructure (Layer 3 and 4) protection. You can write customized rules with AWS WAF to mitigate sophisticated application layer attacks. These customizable rules can be deployed instantly, allowing you to quickly mitigate attacks. You can set up rules proactively to automatically block bad traffic, or respond to incidents as they occur. You also have 24x7 access to the AWS DDoS Response Team (DRT), who can write rules on your behalf to mitigate application layer DDoS attacks#
