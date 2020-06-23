## Date : June 18, 2020 

# Fault Domains

## What are fault domains?

- A fault domain is a set of hardware components that share a single point of failure. To be fault tolerant to a certain level, you need multiple fault domains at that level. For example, to be rack fault tolerant, your servers and your data must be distributed across multiple racks.

- If you want more granular control of application availability within a single Availability Domain, you can now achieve that by using fault domains. Fault domains enable you to distribute your compute instances so that they are not on the same physical hardware within a single Availability Domain, thereby introducing another layer of fault tolerance. In addition to host anti-affinity, you get a level of power anti-affinity since the physical hardware has independent and redundant power supplies preventing power faults within a Fault Domain from affecting other Fault Domains.

- Fault domains can protect your application against unexpected hardware failures or outages caused by maintenance on the underlying compute hardware. Additionally, you can launch instances of all shapes within a fault domain. 

- Oracle Cloud Infrastructure is typically designed with three availability domains per region, and each availability domain has three fault domains.

![](https://cdn.app.compendium.com/uploads/user/e7c690e8-6ff9-102a-ac6d-e4aebca50425/46cba44e-100e-4f99-99c5-38c37b97a5d6/Image/ca1076043409a9fabf2be649e601fa15/fault_domains.png)

# Service-Level Agreements

- A service-level agreement (SLA) is a commitment between a service provider and a client. Particular aspects of the service – quality, availability, responsibilities – are agreed between the service provider and the service user. The most common component of an SLA is that the services should be provided to the customer as agreed upon in the contract. As an example, Internet service providers and telcos will commonly include service level agreements within the terms of their contracts with customers to define the level(s) of service being sold in plain language terms.

- A service-level agreement is an agreement between two or more parties, where one is the customer and the others are service providers. This can be a legally binding formal or an informal "contract" (for example, internal department relationships). The agreement may involve separate organizations, or different teams within one organization. Contracts between the service provider and other third parties are often (incorrectly) called SLAs – because the level of service has been set by the (principal) customer, there can be no "agreement" between third parties; these agreements are simply "contracts." Operational-level agreements or OLAs, however, may be used by internal groups to support SLAs. If some aspect of a service has not been agreed with the customer, it is not an "SLA".

## Uptime

- Uptime is the amount of time that a service is online available and operational. Guaranteed uptime is expressed as SLA level and is generally the most important metric to measure the quality of a hosting provider. An SLA level of 99.99% for example equates to 52 minutes and 36 seconds of downtime per year.

- If you sell an application or service, chances are your customers have existing Service Level Agreements (commonly known as “SLA’s”) requiring you to measure and meet minimum uptime thresholds on a monthly basis.

- Typically uptime (also known as availability) is measured by “Nines”. This measurement is total expected uptime within a given period of time, calculated out to a specific percent. Here’s a common “Table of Nine” often used when it comes to measuring uptime:

## Downtime

- Downtime is the amount of time measured in days, hours, minutes, and seconds (to the thousandths of a second) that an element remains at a specified condition for a specified time interval. That is, downtime is the total elapsed time during an outage.

- The SLA Compliance Report also allows selecting between an interval and a date range and shows the downtime status as indicated by a color in a calendar view. It also indicates the data available and data relevance.

# Container

## What is a Container?

- A Container in cloud computing is an approach to operating system virtualization. By this, the user can work with a program and its dependencies using resource procedures that are isolated. The code of the application can be bundled with configurations and dependencies in a systematic manner.

- Container in cloud computing is used to build blocks, which help in producing operational efficiency, version control, developer productivity and environmental consistency. Because of this, the user is assured of reliability, consistency, and quickness regardless of the distributed platform. The infrastructure is enhanced since it provides more control over the granular activities on resources. The container usage in online services benefits storage with cloud computing information security, availability and elasticity.

## Advantages of a Container in Cloud Computing 

- **The Consistency in Cloud Storage:** The container enhances portability. It eliminates the organizational and technical frictions so that the program moves through the entire process cycle. It encapsulates the core files of an application and software server and dependencies like a building block. This can be distributed on any resource. The manual configuration of each server is thus completely avoided enabling the users to announce a new feature.

- **Application Version Control:** Through container in cloud computing, the users can look on the current version of the application code as well as their dependencies. A manifest file is managed by the Docker containers. The users can easily hold and track the editions of container, look for differences between the container editions and roll-back to earlier versions if needed.

- **Efficiency in the Operational Activities:** The users can achieve more resources through the container in cloud computing. By this, the users can also work at a time on several applications. The required memory, disk space and CPU consumed by the container have to be specified. Since each of the containers is a process of the operating system that works on an application and associated programs, the containers have a fast boot time. The users can quickly enter and exit the application and also measure it in up and down. The applications are separated from each other through the isolation procedure. This concept has no shared incompatibilities or dependencies.

- **Productivity of the Developers:** The containers deduct the dependencies and conflicts between the cross-service and thus the productivity increases. The component of the program is segregated into different entities that run a separate micro-service. There is no worry about the libraries and dependencies that are being synced for each service because the containers are isolated from each other. Each service can be upgraded independently as they are not in touch with each other.
