## Date: June 8, 2020

# Disaster Recovery :-

![](https://www.ironmountain.com/-/media/images/Iron-Mountain/Resources/Multimedia/i/iron-cloud-disaster-recovery-service-cloud-with-technology-symbols-dangling-from-it.jpg)

- Cloud disaster recovery (cloud DR) is a combination of strategies and services intended to back up data,applications and other resources to public cloud or dedicated service providers.

- When disaster occurs, the affected data, applications and other resources can be restored to the local data center -- or a cloud provider -- and resume normal operation for the enterprise.

_ _ _ _ _ _ _ _ _ _

## Selecting a cloud DR provider :-

Selecting a cloud DR provider typically involves six separate considerations: location, reliability, scalability, security and compliance.

- First, a business must consider the cloud DR provider's physical distance and latency -- putting DR too close increases the risk of shared physical disaster, but putting the DR too far away increases latency and network congestion,making it harder to access DR content.

- Location can be particularly tricky when the DR content must be accessible from numerous global business locations.

- Next, consider the cloud DR provider's reliability. Even a cloud experiences downtime, and service downtime during a recovery can be equally disastrous for the business.

![](https://cdn.ttgtmedia.com/rms/onlineImages/cloud-DR_sbs_desktop.jpg)

- Also, consider the scalability of the cloud DR offering.It must be able to protect selected data, applications and other resources, but it must also be able to accommodate additional resources as needed and be able to provide adequate performance as other global customers use the services.

- Understand the security requirements of the DR contentand be sure that the provider can offer authentication, virtual private networks (VPNs), encryption and other toolsneeded to safeguard the business's valuable resources.

- Finally, consider how the DR platform must be architected.There are three fundamental approaches to DR: cold, warm and hot. These terms loosely relate to the ease with which asystem can be recovered.

#### Cold DR :-

- Cold DR typically involves storage of data or virtual machine (VM) images. These resources generally aren't usable without additional work such as downloading the stored data or loading the image into a VM.

- Cold DR is usually the simplest approach -- often just storage -- and least-expensive approach, but it takes the longest to recover, leaving the business with the longest downtime in a disaster.

#### Warm DR :-

- Warm DR is generally a standby approach where duplicate data and applications are placed with a cloud DR provider and kept up to date with data and applications in the primary data center. But the duplicate resources aren't doing any processing.

- When disaster strikes, the warm DR can be brought online to resume operations from the DR provider -- often a matter of starting a VM and redirecting IP addresses and traffic to the DR resources. Recovery can be quite short, but still imposes some downtime for the protected workloads.

#### Hot DR :-

- Hot DR is typically a live parallel deployment of data and workloads running together in tandem. That is, both the primary data center and the DR site use the same workload and data running in synchronization -- both sites sharing part of the overall application traffic.

- When disaster strikes one site, the remaining site continues without disruption to handle the work. Users are ideally unaware of the disruption. Hot DR has no downtime but can be the most expensive and complicated approach.

_ _ _ _ _ _ _ _ _ _ 

# Benefits of cloud DR :-

1. Pay-as-you-go options :-)  
          Organizations that deployed do-it-yourself (DIY)  DR facilities faced significant capital costs, while engaging managed colocation 
   providers for off-site DR services often locked organizations into long-term service agreements.                   

2. Flexibility and scalability :-)  
          Traditional DR approaches, usually implemented in local or remote data centers, often imposed limitations in flexibility and 
   scalability. 

_ _ _ _ _ _ _ _ _ _
