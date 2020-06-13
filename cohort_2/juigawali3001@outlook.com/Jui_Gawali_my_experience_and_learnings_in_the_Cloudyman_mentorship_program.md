> # This blog is part of the **[Cloudyman Mentorship Program](https://t.co/78sRvCvYiO?amp=1)** under the mentorship of *[Mustafa Saifee](https://www.linkedin.com/in/saifeemustafaq/)*

## Date: May 28, 2020

I learned how to use github.

Also I learned that how to submit the work on github.


## Date: May 29, 2020

- Today I learned some basic things about clout computing.
- Today I learned that why cloud computing is important in many fields.
- Today I learned that how the cloud computing makes things easy for us.
- Also cloud computing saves the time and lack of efforts.


## Date: 1 June, 2020

- Today I Learned about virtual machine.
# Virtual Machine-
In computing, a virtual machine (VM) is an emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination.
### There are different kinds of virtual machines, each with different functions:
### 1)System Virtual machines:
### 2)Process Virtual machines:
### System Virtual Machine:
- In computing, a system virtual machine is a virtual machine that provides a complete system platform and supports the execution of a complete operating system (OS).These usually emulate an existing architecture, and are built with the purpose of either providing a platform to run programs where the real hardware is not available for use (for example, executing on otherwise obsolete platforms), or of having multiple instances of virtual machines leading to more efficient use of computing resources, both in terms of energy consumption and cost effectiveness (known as hardware virtualization, the key to a cloud computing environment), or both. A VM was originally defined by Popek and Goldberg as "an efficient, isolated duplicate of a real machine".
- The desire to run multiple operating systems was the initial motive for virtual machines, so as to allow time-sharing among several single-tasking operating systems. In some respects, a system virtual machine can be considered a generalization of the concept of virtual memory that historically preceded it. IBM's CP/CMS, the first systems to allow full virtualization, implemented time sharing by providing each user with a single-user operating system, the Conversational Monitor System (CMS). Unlike virtual memory, a system virtual machine entitled the user to write privileged instructions in their code. This approach had certain advantages, such as adding input/output devices not allowed by the standard system.
- As technology evolves virtual memory for purposes of virtualization, new systems of memory overcommitment may be applied to manage memory sharing among multiple virtual machines on one computer operating system. It may be possible to share memory pages that have identical contents among multiple virtual machines that run on the same physical machine, what may result in mapping them to the same physical page by a technique termed kernel same-page merging (KSM). This is especially useful for read-only pages, such as those holding code segments, which is the case for multiple virtual machines running the same or similar software, software libraries, web servers, middleware components, etc. The guest operating systems do not need to be compliant with the host hardware, thus making it possible to run different operating systems on the same computer (e.g., Windows, Linux, or prior versions of an operating system) to support future software.
- The use of virtual machines to support separate guest operating systems is popular in regard to embedded systems. A typical use would be to run a real-time operating system simultaneously with a preferred complex operating system, such as Linux or Windows. Another use would be for novel and unproven software still in the developmental stage, so it runs inside a sandbox. Virtual machines have other advantages for operating system development and may include improved debugging access and faster reboots.
Multiple VMs running their own guest operating system are frequently engaged for server consolidation.
### Process Virtual Machine:
- A process VM, sometimes called an application virtual machine, or Managed Runtime Environment (MRE), runs as a normal application inside a host OS and supports a single process. It is created when that process is started and destroyed when it exits. Its purpose is to provide a platform-independent programming environment that abstracts away details of the underlying hardware or operating system and allows a program to execute in the same way on any platform.
- A process VM provides a high-level abstraction – that of a high-level programming language (compared to the low-level ISA abstraction of the system VM). Process VMs are implemented using an interpreter; performance comparable to compiled programming languages can be achieved by the use of just-in-time compilation.
- This type of VM has become popular with the Java programming language, which is implemented using the Java virtual machine. Other examples include the Parrot virtual machine and the .NET Framework, which runs on a VM called the Common Language Runtime. All of them can serve as an abstraction layer for any computer language.
- A special case of process VMs are systems that abstract over the communication mechanisms of a (potentially heterogeneous) computer cluster. Such a VM does not consist of a single process, but one process per physical machine in the cluster. They are designed to ease the task of programming concurrent applications by letting the programmer focus on algorithms rather than the communication mechanisms provided by the interconnect and the OS. They do not hide the fact that communication takes place, and as such do not attempt to present the cluster as a single machine.
- Unlike other process VMs, these systems do not provide a specific programming language, but are embedded in an existing language; typically such a system provides bindings for several languages (e.g., C and Fortran).Examples are Parallel Virtual Machine (PVM) and Message Passing Interface (MPI). They are not strictly virtual machines because the applications running on top still have access to all OS services and are therefore not confined to the system model.

## Advantages of VM:
- Can use multiple operating system environments on the same computer.
- Virtual machines can provide an instruction set architecture, or ISA, structure different than the actual computer. The ISA serves as the interface between software and hardware.
- When you create your virtual machine, you create a virtual hard disk. So, everything on that machine can crash, but if it does, it won’t affect the host machine.
- There are security benefits to running virtual machines. For example, if you need to run an application of questionable security, you can run it in a guest operating system. So, if the application causes damage, then it will be only temporary after the guest is shut down. Virtual machines also allow for better security forensics by monitoring guest operating systems for deficiencies and allowing the user to quarantine it for analysis.
## Disadvantages of VM:
- Virtual machines are less efficient than real machines because they access the hardware indirectly. Running software on top of the host operating system means that it will have to request access to the hardware from the host. That will slow the usability.
- When several virtual machines are running on the same host, performance may be hindered if the computer it’s running on lacks sufficient power. Your virtual machine still uses the resources of your host machine. The more powerful the host computer, the more quickly the virtual machine will run.
- A virtual machine can be infected with the weaknesses of the host machine. As an example, process isolation is a feature usually employed by operating systems. However, there are bugs that violate it. A regular computer devoid of virtual machines would then only be affected. But, a computer with a number of virtual machines would then infect each of those “machines” as well.


## Date: June 5, 2020

## Benefits of Cloud Computing:
> Cloud computing offers your business many benefits. It allows you to set up what is essentially a virtual office to give you the flexibility of connecting to your business anywhere, any time. With the growing number of web-enabled devices used in today's business environment (e.g. smartphones, tablets), access to your data is even easier.

There are many benefits to moving your business to the cloud:
## Reduced IT Costs:
> Moving to cloud computing may reduce the cost of managing and maintaining your IT systems. Rather than purchasing expensive systems and equipment for your business, you can reduce your costs by using the resources of your cloud computing service provider. You may be able to reduce your operating costs because:
- the cost of system upgrades, new hardware and software may be included in your contract
- you no longer need to pay wages for expert staff
- your energy consumption costs may be reduced
- there are fewer time delays.

## Scalability:
> Your business can scale up or scale down your operation and storage needs quickly to suit your situation, allowing flexibility as your needs change. Rather than purchasing and installing expensive upgrades yourself, your cloud computer service provider can handle this for you. Using the cloud frees up your time so you can get on with running your business.

## Business Continuity:
> Protecting your data and systems is an important part of business continuity planning. Whether you experience a natural disaster, power failure or other crisis, having your data stored in the cloud ensures it is backed up and protected in a secure and safe location. Being able to access your data again quickly allows you to conduct business as usual, minimising any downtime and loss of productivity.

## Collaboration Efficiency:
> Collaboration in a cloud environment gives your business the ability to communicate and share more easily outside of the traditional methods. If you are working on a project across different locations, you could use cloud computing to give employees, contractors and third parties access to the same files. You could also choose a cloud computing model that makes it easy for you to share your records with your advisers (e.g. a quick and secure way to share accounting records with your accountant or financial adviser).

## Flexibility of work practices:
> Cloud computing allows employees to be more flexible in their work practices. For example, you have the ability to access data from home, on holiday, or via the commute to and from work (providing you have an internet connection). If you need access to your data while you are off-site, you can connect to your virtual office, quickly and easily.

## Access to automatic updates:
> Access to automatic updates for your IT requirements may be included in your service fee. Depending on your cloud computing service provider, your system will regularly be updated with the latest technology. This could include up-to-date versions of software, as well as upgrades to servers and computer processing power.


## Date: June 6,2020.

## What is cloud computing?
> To be precise, cloud computing is the delivery of computing services like servers, storages and more over the Internet. The companies that offer these computing services are called cloud providers. They charge for cloud computing services based on usage.
Cloud computing is usually classified on the basis of location, or on the service that the cloud is offering.

> Based on a cloud location, we can classify cloud as:

- Public,
- Private,
- Hybrid
- Community Cloud
> Based on a service that the cloud is offering, we classify as:

- IaaS (Infrastructure-as-a-Service)
- PaaS(Platform-as-a-Service)
- SaaS(Software-as-a-Service)
or, Storage, Database, Information, Process, Application, Integration, Security, Management, Testing-as-a-service
### Cloud Types: Private, Public and Hybrid, Community
##### Depending on the type of data you’re working with, you’ll want to compare public, private, and hybrid clouds in terms of the different levels of security and management required.

- Public Cloud – Whole computing infrastructure is located on the premises of a cloud computing company that offers the cloud service.
- Private Cloud – Hosting all your computing infrastructure yourself and is not shared. The security and control level is highest while using a private network.
- Hybrid Cloud – using both private and public clouds, depending on their purpose. You host your most important applications on your own servers to keep them more secure and secondary applications elsewhere.
- Community Cloud – A community cloud is shared between organizations with a common goal or that fit into a specific community (professional community, geographic community, etc.).

### Types of cloud services: IaaS, PaaS, SaaS, FaaS
##### Cloud computing services fall into 4 categories: infrastructure as a service (IaaS), platform as a service (PaaS), software as a service (SaaS) and FaaS (functions as a service). These are sometimes called the cloud computing stack, because they build on top of one another.

- Infrastructure-as-a-service (IaaS)
IaaS is the most basic category of cloud computing services that allows you rent IT infrastructure (servers or VM’s) from a cloud provider on a pay-as-you-go basis.
- Platform as a service (PaaS)
Platform-as-a-service (PaaS) refers to the supply an on-demand environment for developing, testing, delivering and managing software applications. It is designed to quickly create web or mobile apps, without worrying about setting up or managing the underlying infrastructure of servers, storage, network and databases needed for development.
- Software as a service (SaaS)
Software-as-a-service (SaaS) is a method for delivering software applications over the Internet as per the demand and on a subscription basis. SaaS helps you host and manage the software application and underlying infrastructure and handle any maintenance (software upgrades and security patching).
- FaaS (functions as a service)
FaaS adds another layer of abstraction to PaaS, so that developers are completely insulated from everything in the stack below their code. Instead of handling the hassles of virtual servers, containers, and application runtimes, they upload narrowly functional blocks of code, and set them to be triggered by a certain event. FaaS applications consume no IaaS resources until an event occurs, reducing pay-per-use fees.


## Date: June 7,2020.

## What are the benefits of using Storage in the cloud? 
> Types of Storage:

MSPs should consider these benefits and drawbacks when switching their Backup-as-a-Service (BaaS) offerings to cloud storage. Each item is significant enough to warrant a dedicated article, but this should be a good primer for anyone considering moving their backups from on-premise disk to cloud storage.

> Here are your five benefits of cloud storage:
### 1. Cloud Storage Can Save Costs
Economies of scale. Cloud vendors buy a lot of storage and pass those savings onto customers. But it’s more than a low per-GB cost that provides savings. Moving to the cloud reduces the need to purchase hard disks, the enclosures that contain them, the RAID cards that power the data redundancy, the electricity that powers them, and the hardware warranty services that protect them. But it also lowers management costs by reducing on-premise hardware and software management, simplifying monitoring, and reducing the need for extensive capacity planning. Instead, administrators can focus on other, more important, tasks.

### 2. Data Redundancy and Replication
Data redundancy is included. Most cloud storage vendors keep multiple copies of your data even within a single “data center” and offer great object durability to reduce any likelihood of data loss. But for those looking for even more protection, geographic replication options can make multiple copies of your data across regions. Some offer geo replication as a storage class option, while others offer replication services that quickly move data between data centers. Your backups are well protected.

### 3. Data Tiering for Cost Savings
Many cloud storage vendors offer different storage classes / data tiers. Select based on how quickly and frequently you restore backups and how long you plan to keep your backups in storage. For backups that need quick and/or frequent restores, consider using the vendor’s hot storage as retrieval is fast and the most cost-effective. For long-term storage, consider moving data to archive storage. Restores can be slower, and there might be additional costs to retrieve data, but the storage costs are considerably lower – especially if you plan to keep the backups for years. Some vendors offer object lifecycle policies that can automatically move data between tiers, which reduces administration and lets you more easily realize cost savings.

### 4. Regulatory Compliance
Keeping your backups in the same region as where the data originates may be best for regulatory compliance. Many cloud vendors offer data centers options all around the globe. If you have a need to store your EU customer data in an EU data center, look for a cloud storage vendor that can accommodate. An added benefit is that moving data to cloud storage in the same region is best for performance. Even if you’re not bound by regulation, you may find the improved performance worthwhile.

### 5. Ransomware/Malware Protection
Ransomware is just bad. Unfortunately, it’s also in the news with great frequency. One of the more sinister ransomware attributes is that the malware will look beyond the locally infected computer to the network for shares that have documents and files to encrypt. If you’re hit by ransomware or some other malware that is encrypting or destroying files, you might be happy that your cloud storage can help to protect against ransomware by offering some backup security advantages as it’s more difficult to access without proper authentication.
#### And here are your three drawbacks:

##### 1. Backups May Be Slower
Internet bandwidth and cloud storage max ingest speeds may be more limited than the local network/disk. There’s also more communication latency involved. This is not normally an issue for backups of file servers and workstations, as the larger, more time-consuming full backups can usually run in the background for a longer period without any ill effects. After the initial full backup, incremental backups serve to reduce the backup size and reduce backup times. Data compression and deduplication help, too. But specialized applications like databases (for example, Microsoft SQL Server and Exchange) can be affected by longer backup times. You want those applications backed up during times of low activity and within your maintenance windows. In those cases, look to back up critical applications locally for best speed and then sweep up the backups to the cloud. Some cloud backup software will automate this process for you.

##### 2. Restores May Be Slower
It’s all about internet bandwidth and rated cloud storage speed. Restoring an entire server may take longer. But you might find file-level restores are just as fast. The important takeaway is to make sure you can meet your contracted recovery time objectives (RTOs). If you can’t restore what’s needed in the committed time, then consider performing hybrid backups on those critical servers and send your backups to both local and cloud storage. Having two backup copies provides those critical workloads with the benefit of fast local restores (with no reliance on internet and cloud storage vendor availability), and the benefit of off-site, cloud storage protection for disaster recovery.

##### 3. Higher Internet Utilization
If backups are running during business hours or times of heavy internet use, you may find internet-related activity performance suffers. Internet bandwidth may need to be controlled. Look to set up bandwidth utilization rules in your backup software (or limit via other network-controlled means) to ensure you don’t saturate your internet connection during times when access to the internet is needed for other critical business activity.


## Date: June 13,2020.

### What is Capital expenditure (CapEx) versus operational expenditure (OpEx)?

## CapEx and OpEx Defined:
> CapEx:
CapEx is defined as business expenses incurred in order to create long-term benefits in the future, such as purchasing fixed assets like a building or equipment. Some examples of IT items that fall under this category would be whole systems and servers, printers and scanners, or air conditioners and generators. You buy these items once and they benefit your business for many, many years. Maintenance of such items is also considered CapEx, as it extends their lifetime and usefulness.
> OpEx:
OpEx is your operating costs, the expenses to run day-to-day business, like services and consumable items that get used up and are paid for according to use. This includes printer cartridges and paper, electricity, and even yearly services like website hosting or domain registrations. These things are necessary for your business’s success but are not considered major long-term investments like CapEx items.

### CapEx,OpEx and The Cloud:
The financial differences of OpEx versus CapEx when adopting cloud services will affect the cloud set up you choose. If you want to avoid the difficulties of a capital expenditure, you will probably opt for public cloud services that use a pay as you go model. If you want total control of cloud services within your company, you can task your in-house IT team with setting up a private cloud where your organization is totally responsible for its services (and costs).
A third option combines resources from both private and public clouds to create a hybrid cloud when your organization buys a public cloud and makes your IT team responsible for it. This option offers the most flexibility for controlling costs.

![alt.OpEx services](https://www.10thmagnitude.com/wp-content/uploads/2019/04/OpEx-Services-Complement-a-World-Preparing-for-the-Cloud-%E2%80%93-10th-Magnitude-1200x576.jpg)

### CapEx stability or OpEx Flexibility
> CapEx stability-
- Buying capacity you don’t need today to meet tomorrow’s uncertainties. In the IT world, technology is always changing. An upfront push into establishing your own cloud might seem like an investment, but what if the equipment and skills of the workforce you invest in become irrelevant before your investment pays off?
- Getting stuck with capacity you don’t need. If you overshoot on everything needed to set up a private cloud service and your need for private cloud services doesn’t grow fast enough, you lose money on wasted goods and work.
- Entering vendor contracts that create business dependencies you can’t break. Being held hostage by those contracts. Being left high and dry when the vendor doesn’t follow through.
- Paying staff to watch over these assets and “keep the lights on,” when they could be contributing to better products and processes. Either you’re taking staff from what they were originally hired to do or paying additional staff. Either way, profits are at risk.
- Locking into long-term approaches to your IT needs, limiting your ability to adopt newer, better ways. Like we’ve said before, technology changes fast these days and you don’t want to be lagging behind just because you spent so much money on a prematurely aging setup.
- Taking a very long time, usually through a difficult process, to adopt new capacity. Time is money. The longer a setup takes, the more money you lose.
- Letting your equipment dictate your business approach, rather than your business needs driving your IT infrastructure. You sacrifice agility when you invest a lot of time, money, and manpower into a CapEx expense and can’t bear to change after investing all those resources. This is a guaranteed way for your business to become irrelevant.
> OpEx Flexibilty-
- Purchasing IT resources and services as OpEx costs make each purchase less permanent and reduces a lot of risk. If a vendor fails to meet your expectations, if technology leaps ahead, if your business identifies new markets, or if your IT budget fluctuates, you aren’t locked into one IT infrastructure that you spent a lot of resources on.
- By freeing you from basic network and equipment maintenance, your people can apply their talents to improving your products and increasing sales for higher profits.
- Because these services are provided instantly and on demand, your lead times for deploying new and improved products shorten to days and hours, versus years and months, again increasing profits.
- If an architecture or service turns out to be misconfigured, you can quickly and easily reconfigure it. If a project or program turns out to be a dud, you’re not stuck carrying infrastructure dead weight; just delete it. Minimal money wasted.
- The OpEx approach to IT expenditure gives modern businesses the agility and flexibility they need to stay relevant in ever-changing markets and meet their clients’ needs more successfully and quickly. And better products and better services delivered means higher profits for your company.
- A more flexible approach to IT infrastructures like pay-as-you-go cloud services and other IT operational expenditures allows your business to keep up with the competition by paying for only what you need when you need it, so you don’t get stuck with a huge bill for outdated infrastructure.

### Pricing and Flexibility related to OpEx and the cloud:
- Most Cloud services are priced by usage; the more you use, the more you pay. You don’t pay for what you don’t use.
- Cloud services are also often priced by service level. Just as a steak dinner costs more than a fast-food hamburger combo, your IT needs may be premium or basic.
- You might need one steak dinner to sate your appetite. Or, maybe one hamburger combo (or several hamburger combos that are still less expensive than one steak dinner) will do the trick. It all depends on your flexibility.
- Cloud providers recognize this, and they tend to have services priced according to how robust they are, on top of how much you use them.
- The quality and flexibility model of Cloud services is important for businesses like yours who are looking for vendors who aren’t going to just offer a service you can use, but one that will be in line with the up and down cycles of your business and really perform for you when you need it most.
- Before, when data storage was a CapEx investment of space, hardware, software, maintenance, and manpower, companies may have bought and valued everything with the lifespan of each item in mind. But today, the value of increasingly intangible assets like the Cloud is often found in their flexibility.
- Vendors know that companies are moving towards OpEx IT infrastructures and that they aren’t willing to invest in long-term tangible products. So, they are increasingly valuing and pricing their cloud and other IT products and services based on consumption and, often, tier of service, knowing the expiration date of what they’re offering is insignificant.
- In IT, having the newest and most on-trend technology is important and the cloud model makes this easier. But the true advantage of usage pricing (vs. a fixed fee model) is the flexibility it brings. You can better manage the model and quickly scale up or scale down a configuration based on need.
![alt.cloud](https://www.10thmagnitude.com/wp-content/uploads/2019/04/Scale-%E2%80%93-10th-Magnitude-1200x489.jpg)
Today companies still need the same tight security and oversight, but also more flexibility and more cost-effective solutions. The answer is the Cloud.

### Review of CapEx versus OpEx:
![alt.Review](https://www.10thmagnitude.com/wp-content/uploads/2019/04/OpEx-vs-CapEx.jpg)























