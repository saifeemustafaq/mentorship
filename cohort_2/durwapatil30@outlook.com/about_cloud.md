> ## Date: June 8, 2020

# Disaster Recovery :-

![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQVXIVXtK7H0wRh-obZjRdLGcjtcR5e1Oqz1w&usqp=CAU)

- Cloud disaster recovery (cloud DR) is a combination of strategies and services intended to back up data,applications and other resources to public cloud or dedicated service providers.

- When disaster occurs, the affected data, applications and other resources can be restored to the local data center -- or a cloud provider -- and resume normal operation for the enterprise.

- Users have the ability to add, edit and delete systems and storage capacity, without having to consider the back-end supported infrastructure.

- A cloud-based disaster recovery solution enables the user to scale up the entire cloud DRP solution from some-to-many. The user is normally billed on a monthly basis only for the storage and client software licenses.

- Most Cloud DR also provisions backup and recovery for critical server machines that host enterprise-level applications like MS-SQL, Oracle, etc.

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

> ## Date: June 9, 2020

# What is Capital expenditure (CapEx) ?

##### Ans.

- Capital expenditure occurs when the company acquires new assets or adds some value to the existing one which would be useful beyond the current financial year.

- Capex or expenses are depreciated or amortized over a span of years. For example, it can buy equipment/ buildings or add value to an existing asset to upgrade beyond the current financial year.

- Once the asset is put to use, it is depreciated over the period of time to spread the cost of the asset over its useful span of life. Every year, a part of the asset is put to use.

- Depreciation is the amount of depletion on the fixed asset, and the amount of depreciation which happens each year is used as a tax deduction.

- Most often capital expenses are mostly depreciated over a five to ten years period, but sometimes may be depreciated over twenty years in the case of real estate properties.

- Capital expenditure is therefore used for a future benefit like for the growth of the company.

![](https://blog.comindware.com/wp-content/uploads/2018/12/opex-650x421.png)

_ _ _ _ _ _ _ _ _ _

# What is Operational expenditure (OpeEx) ?

##### Ans. 

- Opex refers to those expenses that a business has to incur to run the daily operations. For example, the wages of the employees, leases, maintenance and repair cost, etc.

- Operating expenses are completely tax-deductible. Therefore it is more attractive for a company to lease an item and assign its cost to operating expenses rather than purchase it.

- This can be a financially attractive option for the company if the company has limited cash flow.

![](https://blog.comindware.com/wp-content/uploads/2018/12/opex-650x421.png)

_ _ _ _ _ _ _ _ _ _

## Key Differences :

- As capital expenses involve the purchase of assets that have a useful life beyond the current accounting year, these expenses cannot be recovered in the year in which capital expenses are purchased.  
  Instead, the assets are capitalized and either amortized or depreciated over the life of the assets depending on whether it is tangible or intangible assets.  
  Intangible assets like patents are amortized and tangible assets like buildings or equipment’s are depreciated over their lifespan.  

- Operating expenditure, on the other side, can be fully deducted in the current accounting year.  
  By deducted it means, the operating expenses can be subtracted from the revenue when estimating the profit/loss of the company.  
  As companies are usually taxed on the profit Operating expenditure make therefore the number of expenses you deduct will impact the tax one has to pay.  

- However tax deductible is not always the sole purpose for all the companies. If a company wants to increase its earnings, it may opt for capital expenditure instead and only subtract a small part of it as an expense over a span of years.  
  This will amount to a higher value of assets on its balance sheet and also an increase in net income that it can show to the investors. It will eventually increase the valuation of the company and also its stock price.

_ _ _ _ _ _ _ _ _ _

## IT Spending – CapEx or OpEx ?

- Traditionally technology investments most often were considered for capital expenditures over OpEx, because CFOs could take advantage of amortization these expenses over an extended period of time.

- Nowadays, more and more companies switch IT investment from CapEx to OpEx and they have a reasonable argument for this switch – moving company IT infrastructure to the cloud.

- Once this moving happens, additional CapEx benefits fall as far as the company no longer need static investments for the hardware, software and resources.

- Services and options are purchased as needed, costs are fluctuating and OpEx works better for such expenses type and supports necessary scalability.

_ _ _ _ _ _ _ _ _ _

> ## Date: June 10, 2020

# What are the Cloud deployment models ?

##### Ans.

There are 4 fundamental Deployment Models of cloud computing: Public Cloud, Private Cloud, Hybrid Cloud and Community Cloud.

# 1. Public cloud :

- In Public Cloud model, services and infrastructure are hosted on premise of cloud provider and are provisioned for open use by general public. The end users can access the services via public network like internet.

- Public Cloud services are delivered mostly on demand. Popular for hosting everyday apps like email, CRM and other business support apps.

- Public Cloud model offers high scalability, automated maintenance but more vulnerable to attacks due to high levels of accessibility.

- Public cloud is better suited for business purposes for managing the load. This type of cloud is economical due to the decrease in capital overheads.

- Common Public Cloud providers include Amazon Web Services and Microsoft Azure.

- Some of the examples of those companies which provide public cloud facilities are IBM, Google, Amazon, Microsoft, etc. This cloud service is open for use. 

![](https://www.sam-solutions.com/blog/wp-content/uploads/2017/08/a-cloud-provider@2x.png)

### Merits :

* Flexible
* Reliable
* High Scalable
* Low cost
* Place independence

### Demerits :

* Compromised reliability.
* Data security and privacy give rise to concern. 
* Less Secured
* Poor Customizable
* The lack of a bespoke service.

_ _ _ _ _ _ _ _ _ _

# 2.  Private Cloud :

- Private Cloud also termed as 'Internal Cloud'; which allows the accessibility of systems and services within a specific boundary or organization.

- The cloud platform is implemented in a cloud-based secure environment that is guarded by advanced firewalls under the surveillance of the IT department that belongs to a particular organization. Private clouds permit only authorized users, providing the organizations greater control over data and its security. 

- Many companies are migrating their data centers to Private Cloud to run core business fields like research, manufacturing human resource etc.

- The Private Cloud model offers great levels of security and control, though cost benefits ought to be sacrificed to some extent.

- Business organizations that have dynamic, critical, secured, management demand based requirement should adopt Private Cloud.

- Common Private Cloud providers include VMware and Openstack.

- Multiple public cloud service providers — including Amazon, IBM, Cisco, Dell and Red Hat — also provide private solutions along with public ones.

![](https://www.sam-solutions.com/blog/wp-content/uploads/2017/08/a-private-cloud@2x.png)

### Advantages :

* #### Highly private and secured :
  Private cloud resource sharing is highly secured.
* #### Control Oriented :
  Private clouds provide more control over its resources than public cloud as it can be accessed within the organization's boundary.

* Bespoke and flexible development and high scalability, which allows companies to customize their infrastructures in accordance with their requirements

### Disadvantages :

* #### Poor scalability :
  Private type of clouds is scaled within internal limited hosted resources.
* #### Costly :
  As it provides secured and more features, so it's more expensive than a public cloud.
* #### Pricing :
  Is inflexible; i.e., purchasing new hardware for up-gradation is more costly.
* #### Restriction :
  It can be accessed locally within an organization and is difficult to expose globally.

_ _ _ _ _ _ _ _ _ _

# 3.  Community Cloud :

- Community Cloud is another type of cloud computing in which the setup of the cloud is shared manually among different organizations that belong to the same community or area. 

- Example of such a community is where organizations/firms are there along with the financial institutions/banks. A multi-tenant setup developed using cloud among different organizations that belong to a particular community or group having similar computing concern.

- Community members generally share similar issues of privacy, performance, and security. This type of deployment model of cloud computing is managed and hosted internally or by a third-party vendor.

- Access to a community cloud environment is typically restricted to the members of the community.

- For joint business organizations, ventures, research organizations and tenders community cloud is the appropriate solution. Selection of the right type of cloud hosting is essential in this case. Thus, community-based cloud users need to know and analyze the business demand first.

- The costs are shared across all users.

![](https://www.sam-solutions.com/blog/wp-content/uploads/2017/08/community-cloud@2x.png)

### Benefits :

- Improved security, privacy and reliability
- Cost reduction
- Ease of data sharing and collaboration

### Drawbacks :

- High cost if compared to a public deployment model
- Sharing of fixed storage and bandwidth capacity
- It is not widespread so far

_ _ _ _ _ _ _ _ _ _

# 4.  Hybrid Cloud :

- Hybrid Cloud is another cloud computing type, which is integrated, i.e., it can be a combination of two or more cloud servers, i.e., private, public or community combined as one architecture, but remain individual entities. 

- Further, as part of this deployment of cloud computing model, the internal, or external providers can provide resources.

- Non-critical tasks such as development and test workloads can be done using public cloud whereas critical tasks that are sensitive such as organization data handling are done using a private cloud. 
 
- The companies using Hybrid Cloud model benefit with the security and control aspect of Private Cloud and off-hand management and cost benefits of Public Cloud.

- It allows companies to mix and match the facets of all three types that best suit their requirements.

- A perfect example of this scenario would be that of an organization who uses the private cloud to secure their data and interacts with its customers using the public cloud.

![](https://www.sam-solutions.com/blog/wp-content/uploads/2017/08/hybrid-cloud@2x.png)

### Strengths :

* Flexible
* Secure
* Cost Effective
* Rich Scalable

### Shortcomings :

* Complex networking problem
* Organization's security Compliance

_ _ _ _ _ _ _ _ _ _

> ## Date: June 11, 2020

# What are the Types of cloud services ?

![](https://blog.dwwtc.com/wp-content/uploads/2016/07/blogchart.jpg)

##### Ans. 

Cloud computing services fall into 3 categories: Infrastructure as a service (IaaS), Platform as a service (PaaS) and Software as a service (SaaS). These are sometimes called the cloud computing stack, because they build on top of one another.

![](https://whatiscloudcomputingwordpresscom.files.wordpress.com/2016/01/types-of-cloud.png?w=640)

### 1.) Infrastructure-as-a-service (IaaS) :

- IaaS is the most comprehensive and flexible type of cloud service available. Essentially, it provides a completely virtualized computing infrastructure that is provisioned and managed over the internet.

- An IaaS provider manages the physical end of the infrastructure (servers, data storage space, etc) in a data center, but allows customers to fully customize those virtualized resources to suit their specific needs.

- IaaS eliminates the capital expense of building up in-house infrastructure. It’s a great option for small companies and startups that don’t have the resources to purchase the hardware and software needed to create their own network internally.

- It also takes the day-to-day burdens of managing computing infrastructure off the hands of IT departments, freeing them to focus on core business drivers instead of troubleshooting.

- Since the IaaS provider continuously updates their system with the latest software and update patches, it’s easier to get new programs and applications up and running.

- IaaS provides the latest in security protections and usually offers services like disaster recovery to go along with their uptime reliability SLAs.

- Examples of IaaS: Microsoft Azure, Amazon Web Services (AWS), Cisco Metacloud, Google Compute Engine (GCE)

_ _ _ _ _ _ _ _ _ _

### 2.) Software as a service (SaaS) :

- Software-as-a-service (SaaS) is a method for delivering software applications over the Internet as per the demand and on a subscription basis.

- Here, the cloud service provider delivers the entire software suite as a pay-per-use model. SaaS lets users easily access software applications -- such as emails -- over the internet. 

- SaaS helps you host and manage the software application and underlying infrastructure and handle any maintenance (software upgrades and security patching).

- The SaaS provider manages the infrastructure, operating systems, middleware, and data necessary to deliver the program, ensuring that the software is available whenever and wherever customers need it. 

- Many SaaS applications run directly through web browsers, eliminating the need for downloads or installations. This greatly reduces software management issues for internal IT teams and allows companies to streamline their operations with hybrid and multi-cloud deployments.

- SaaS applications allow companies to get up and running very quickly as well as scale operations rapidly. There’s no need to purchase or deploy the hardware and software used to deliver their business services.

- Examples of SaaS: Microsoft Office 365, Salesforce, Cisco WebEx, Google Apps.

_ _ _ _ _ _ _ _ _ _

### 3.) Platform as a Service (PaaS) :

- Situated a bit higher up the cloud computing pyramid is PaaS. Whereas IaaS delivers all the tools available through the cloud and leaves it to customers to build whatever suits their needs, PaaS is a bit more specialized.

- It is designed to quickly create web or mobile apps, without worrying about setting up or managing the underlying infrastructure of servers, storage, network and databases needed for development.

- PaaS provides the framework needed to build, test, deploy, manage, and update software products. It utilizes the same basic infrastructure as IaaS, but it also includes the operating systems, middleware, development tools, and database management systems needed to create software applications.

- PaaS is extremely helpful for any company that develops software and web-based applications. Many of the tools needed to develop for multiple platforms (computers, mobile devices, browsers, etc) can be quite expensive.

- By using PaaS, customers can access the development tools they need, when they need them, without having to purchase them outright. Since the platform is accessible over the internet, remote development teams can all access the same assets to speed up product development.

- Most PaaS tools provide extensive pre-coded applications built into the platform, which can greatly reduce coding time and help companies get their products to market faster.

- Examples of PaaS: AWS Elastic Beanstalk, Apache Stratos, Google App Engine, Microsoft Azure.

_ _ _ _ _ _ _ _ _ _

![](https://image-store.slidesharecdn.com/4b612237-6442-48b9-9aa6-d731fb576ea3-large.png)

_ _ _ _ _ _ _ _ _ _
