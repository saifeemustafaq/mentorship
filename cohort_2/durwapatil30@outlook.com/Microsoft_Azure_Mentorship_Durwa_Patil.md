> # This blog is part of the **[Cloudyman Mentorship Program](https://t.co/78sRvCvYiO?amp=1)** under the mentorship of *[Mustafa Saifee](https://www.linkedin.com/in/saifeemustafaq/)*

## Date: June 23, 2020

# What is Microsoft Azure ?

##### Ans.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS7Vy8ZU0f_EE921wogieyZ_SiYfqrW4gqR4Ypy_h17H46eIEAP&usqp=CAU)

- Microsoft Azure, commonly referred to as Azure, is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

- It provides software as a service (SaaS), platform as a service (PaaS) and infrastructure as a service (IaaS) and supports many different programming languages, tools, and frameworks, including both Microsoft-specific and third-party software and systems.

- Azure was announced in October 2008, started with codename "Project Red Dog", and released on February 1, 2010, as Windows Azure before being renamed to Microsoft Azure on March 25, 2014.

_ _ _ _ _ _ _ _ _ _

## Services :

Microsoft lists over 600 Azure services, of which some are covered below :

### Computer services :

- Virtual machines, infrastructure as a service (IaaS) allowing users to launch general-purpose Microsoft Windows and Linux virtual machines, as well as preconfigured machine images for popular software packages.

- Most users run Linux on Azure, some of the many Linux distributions offered, including Microsoft's own Linux-based Azure Sphere.

- App services, platform as a service (PaaS) environment letting developers easily publish and manage websites.

- Websites, high density hosting of websites allows developers to build sites using ASP.NET, PHP, Node.js, or Python and can be deployed using FTP, Git, Mercurial, Team Foundation Server or uploaded through the user portal. This feature was announced in preview form in June 2012 at the Meet Microsoft Azure event. Customers can create websites in PHP, ASP.NET, Node.js, or Python, or select from several open source applications from a gallery to deploy. This comprises one aspect of the platform as a service (PaaS) offerings for the Microsoft Azure Platform. It was renamed to Web Apps in April 2015.

- WebJobs, applications that can be deployed to an App Service environment to implement background processing that can be invoked on a schedule, on demand, or run continuously. The Blob, Table and Queue services can be used to communicate between WebApps and WebJobs and to provide state.

### Mobile services :

- Mobile Engagement collects real-time analytics that highlight users’ behavior. It also provides push notifications to mobile devices.

- HockeyApp can be used to develop, distribute, and beta-test mobile apps.

### Storage services :

- Storage Services provides REST and SDK APIs for storing and accessing data on the cloud.

- Table Service lets programs store structured text in partitioned collections of entities that are accessed by partition key and primary key. It's a NoSQL non-relational database.

- Blob Service allows programs to store unstructured text and binary data as blobs that can be accessed by an HTTP(S) path. Blob service also provides security mechanisms to control access to data.

- Queue Service lets programs communicate asynchronously by message using queues.

- File Service allows storing and access of data on the cloud using the REST APIs or the SMB protocol.

## Data management :

- Azure Data Explorer provides big data analytics and data-exploration capabilities

- Azure Search provides text search and a subset of OData's structured filters using REST or SDK APIs.

- Cosmos DB is a NoSQL database service that implements a subset of the SQL SELECT statement on JSON documents.

- Redis Cache is a managed implementation of Redis.

- StorSimple manages storage tasks between on-premises devices and cloud storage.

## Messaging :

The Microsoft Azure Service Bus allows applications running on Azure premises or off-premises devices to communicate with Azure. This helps to build scalable and reliable applications in a service-oriented architecture (SOA). The Azure service bus supports four different types of communication mechanisms:

#### 1. Event Hubs :
which provide event and telemetry ingress to the cloud at massive scale, with low latency and high reliability. For example, an event hub can be used to track data from cell phones such as a GPS location coordinate in real time.

#### 2. Queues :
which allow one-directional communication. A sender application would send the message to the service bus queue, and a receiver would read from the queue. Though there can be multiple readers for the queue only one would process a single message.

#### 3. Topics :
which provide one-directional communication using a subscriber pattern. It is similar to a queue, however, each subscriber will receive a copy of the message sent to a Topic. Optionally the subscriber can filter out messages based on specific criteria defined by the subscriber.

#### 4. Relays :
which provide bi-directional communication. Unlike queues and topics, a relay doesn't store in-flight messages in its own memory. Instead, it just passes them on to the destination application.

## Media services :

- A PaaS offering that can be used for encoding, content protection, streaming, or analytics.

## CDN :

- A global content delivery network (CDN) for audio, video, applications, images, and other static files. It can be used to cache static assets of websites geographically closer to users to increase performance. The network can be managed by a REST-based HTTP API.

- Azure has 54 point of presence locations worldwide (also known as Edge locations) as of August 2018.

## Developer :

- Application Insights

- Azure DevOps

## Management :

- Azure Automation, provides a way for users to automate the manual, long-running, error-prone, and frequently repeated tasks that are commonly performed in a cloud and enterprise environment. It saves time and increases the reliability of regular administrative tasks and even schedules them to be automatically performed at regular intervals. You can automate processes using runbooks or automate configuration management using Desired State Configuration.

- Microsoft SMA

## Machine learning :

- Microsoft Azure Machine Learning (Azure ML) service is part of Cortana Intelligence Suite that enables predictive analytics and interaction with data using natural language and speech through Cortana.

- Cognitive Services (formerly Project Oxford) are a set of APIs, SDKs and services available to developers to make their applications more intelligent, engaging and discoverable. The services include face recognition and verification, celebrity recognition,computer vision, visual feature tagging, and clipart recognition.

## Azure Blockchain Workbench :

- Through Azure[28] Blockchain Workbench, Microsoft is providing the required infrastructure to set up a consortium network in multiple topologies using a variety of consensus mechanisms. Microsoft provides integration from these blockchain platforms to other Microsoft services to streamline the development of distributed applications. Microsoft supports many general-purpose blockchains including Ethereum and Hyperledger Fabric and purpose-built blockchains like Corda.

## Functions :

- Azure functions are used in serverless computing architectures where subscribers can execute code as an event driven Function-as-a-Service (FaaS) without managing the underlying server resources.

## Internet of Things (IoT) :

- Azure IoT Hub lets you connect, monitor, and manage billions of IoT assets. On February 4, 2016, Microsoft announced the General Availability of the Azure IoT Hub service.

- Azure IoT Edge is a fully managed service built on IoT Hub that allows for cloud intelligence deployed locally on IoT edge devices.

- Azure IoT Central is a fully managed SaaS app that makes it easy to connect, monitor, and manage IoT assets at scale. On December 5, 2017, Microsoft announced the Public Preview of Azure IoT Central; its Azure IoT SaaS service.

- On October 4, 2017, Microsoft began shipping GA versions of the official Microsoft Azure IoT Developer Kit (DevKit) board; manufactured by MXChip.

- On April 16, 2018, Microsoft announced the launch of the Azure Sphere, an end-to-end IoT product that focuses on microcontroller-based devices and uses Linux.

- On June 27, 2018, Microsoft launched Azure IoT Edge, used to run Azure services and artificial intelligence on IoT devices.

- On November 20, 2018, Microsoft launched the Open Enclave SDK for cross-platform systems such as ARM TrustZone and Intel SGX.

_ _ _ _ _ _ _ _ _ _

# Regional expansion and examples :

- Azure is generally available in 54 regions around the world. Microsoft has announced an additional 12 regions to be opened soon (as of October 2018). Microsoft is the first hyper-scale cloud provider that has committed to building facilities on the continent of Africa with two regions located in South Africa.

- An Azure geography contains multiple Azure Regions, such as for example “North Europe” (Dublin, Ireland), “West Europe” (Amsterdam, Netherlands). Where a location represents the city or area of the Azure Region. Each Azure Region is paired with another region within the same geography; this makes them a regional pair. In this example, Amsterdam and Dublin are the locations which form the regional-pair.

- Microsoft has some Gold partners available across the globe to sell its products. In August 2018, Toyota Tsusho began a partnership with Microsoft to create fish farming tools using the Microsoft Azure application suite for IoT technologies related to water management.

- Developed in part by researchers from Kindai University, the water pump mechanisms use artificial intelligence to count the number of fish on a conveyor belt, analyze the number of fish, and deduce the effectiveness of water flow from the data the fish provide. The specific computer programs used in the process fall under the Azure Machine Learning and the Azure IoT Hub platforms.

_ _ _ _ _ _ _ _ _ _

# Design :

- Microsoft Azure uses a specialized operating system, called Microsoft Azure, to run its "fabric layer": A cluster hosted at Microsoft's data centers that manage computing and storage resources of the computers and provisions the resources (or a subset of them) to applications running on top of Microsoft Azure.

- Microsoft Azure has been described as a "cloud layer" on top of a number of Windows Server systems, which use Windows Server 2008 and a customized version of Hyper-V, known as the Microsoft Azure Hypervisor to provide virtualization of services.

- Scaling and reliability are controlled by the Microsoft Azure Fabric Controller, which ensures the services and environment do not fail if one or more of the servers fails within the Microsoft data center, and which also provides the management of the user's Web application such as memory allocation and load balancing.

- Azure provides an API built on REST, HTTP, and XML that allows a developer to interact with the services provided by Microsoft Azure. Microsoft also provides a client-side managed class library that encapsulates the functions of interacting with the services. It also integrates with Microsoft Visual Studio, Git, and Eclipse.

- In addition to interacting with services via API, users can manage Azure services using the Web-based Azure Portal, which reached General Availability in December 2015. The portal allows users to browse active resources, modify settings, launch new resources, and view basic monitoring data from active virtual machines and services.

## Deployment models :

- Microsoft Azure offers two deployment models for cloud resources: the "classic" deployment model and the Azure Resource Manager.

- In the classic model, each Azure resource (virtual machine, SQL database, etc.) was managed individually.

- The Azure Resource Manager, introduced in 2014, enables users to create groups of related services so that closely coupled resources can be deployed, managed, and monitored together.

_ _ _ _ _ _ _ _ _ _
