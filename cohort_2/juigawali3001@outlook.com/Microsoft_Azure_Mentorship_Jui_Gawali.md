> # This blog is part of the **[Cloudyman Mentorship Program](https://t.co/78sRvCvYiO?amp=1)** under the mentorship of *[Mustafa Saifee](https://www.linkedin.com/in/saifeemustafaq/)*

## Date: June 10,2020.

# Cloud Deployment Model

##### To start with, there are many different models for deployment in cloud computing to choose from. Your cloud infrastructure and placement of each workload depend on your business needs—for example, balancing short-term costs with long-term total cost of ownership (TCO), addressing any data governance regulations, and ensuring uptime for mission-critical applications.

### Public cloud:
Since public cloud services are set up as pay-per-use, there’s minimal investment to get started. They’re also easy to scale, since you can simply buy more capacity as it’s needed. Public cloud services are especially useful for workloads that may run for a short period of time—for example, a start-up that can’t afford to wait months to prove its viability can get just the right amount of compute it needs, for just as long as it needs it. Plus, your IT team won’t need to maintain the hardware.
The largest cloud service providers today include Amazon Web Services, Microsoft Azure, Alibaba Cloud, Google Cloud, and IBM. There are a range of providers to choose from, both large and small, each offering its own menu of services.
However, there are some workloads that simply won’t work in the public cloud—for example, legacy applications that are too difficult or risky to migrate. As such, the private cloud remains a critical part of your cloud strategy.

### Private cloud:
A private cloud is hosted in your data center and maintained by your IT team. Because your organization purchases and installs the hardware, this involves a substantial capital expenditure. It also requires ongoing management and operational costs. However, running workloads on a private cloud can deliver a lower TCO as you deliver more computing power with less physical hardware. It also gives you support for legacy applications that cannot be moved to the public cloud.
Having your own private cloud also lets you control how data is shared and stored. This is often the best option if cloud security is a concern, since you can manage data governance, ensure compliance with any regulations, and protect valuable intellectual property.
Additionally, your private cloud gives you on-demand data availability, ensuring reliability and support for mission-critical workloads. And because you can control how resources are used, you can respond quickly to changing workload demands.

### Hybrid cloud:
A hybrid cloud combines public cloud and private cloud environments by allowing data and applications to be shared between them. This helps businesses seamlessly scale services back and forth between their own infrastructure and the public cloud. 

#### Multicloud:
Because there are so many different types of workloads, each with its own requirements, many businesses end up using a combination of services from different cloud service providers, including their own private cloud resources. This is known as a multicloud approach.
Multicloud gives you more flexibility over different price points, service offerings, capabilities, and geographic locations. With careful planning, a multicloud strategy can create consistency across your organization, independent of the services being consumed. Multicloud requires a software layer to deliver management and orchestration across cloud environments—for example, Google Cloud’s Anthos*.
In short, a multicloud, hybrid cloud approach gives you the best of both the private cloud and public cloud with the flexibility to run workloads where they make the most sense.

## Date: June 14,2020.
## What is Fault Domain?
> A fault domain is a logical group of underlying hardware that share a common power source and network switch, similar to a rack within an on-premises datacenter. As you create VMs within an availability set, the Azure platform automatically distributes your VMs across these fault domains. This approach limits the impact of potential physical hardware failures, network outages, or power interruptions.

![alt.fault domain](http://www.thatlazyadmin.com/wp-content/uploads/2017/10/word-image-10.png)

## What is update Domain?
> An update domain is a logical group of underlying hardware that can undergo maintenance or be rebooted at the same time. As you create VMs within an availability set, the Azure platform automatically distributes your VMs across these update domains. This approach ensures that at least one instance of your application always remains running as the Azure platform undergoes periodic maintenance. The order of update domains being rebooted may not proceed sequentially during planned maintenance, but only one update domain is rebooted at a time.

![alt.update domain](http://www.thatlazyadmin.com/wp-content/uploads/2017/10/word-image-11.png)









