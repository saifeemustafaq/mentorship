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


## Date: June 18,2020.

## What is serverless computing?
> Serverless computing enables developers to build applications faster by eliminating the need for them to manage infrastructure. With serverless applications, the cloud service provider automatically provisions, scales and manages the infrastructure required to run the code.
In understanding the definition of serverless computing, it is important to note that servers are still running the code. The serverless name comes from the fact that the tasks associated with infrastructure provisioning and management are invisible to the developer. This approach enables developers to increase their focus on the business logic and deliver more value to the core of the business. Serverless computing helps teams increase their productivity and bring products to market faster and it allows organisations to better optimise resources and stay focused on innovation.

![alt.serverless computing](https://blog.sysfore.com/wp-content/uploads/2018/02/Enhance-developer-productivity-2.png)

## Benefits of serverless computing:

- No infrastructure Management:
Using fully managed services enables developers to avoid administrative tasks and focus on core business logic. With a serverless platform, you simply deploy your code and it runs with high availability.
- Dynamic Scalability:
With serverless computing, the infrastructure dynamically scales up and down within seconds to match the demands of any workload.
- Faster Time to Market:
Serverless applications reduce the operations dependencies on each development cycle, increasing development teams’ agility to deliver more functionality in less time.
- More Efficient Use of Resources:
Shifting to serverless technologies helps organisations reduce TCO and reallocate resources to accelerate the pace of innovation.

## Serverless Application Patterns:

![alt.pattern](https://azurecomcdn.azureedge.net/cvt-766476b1d11c55c04f5caea524dfd4f117de6df31ff650db4fa65ac534715da7/images/page/overview/serverless-computing/serverless-platform.svg)
> Developers build serverless applications using a variety of application patterns—many of which align with approaches that are already familiar—to meet specific requirements and business needs.

- Serverless Functions:
> Serverless functions accelerate development by using an event-driven model, with triggers that automatically execute code to respond to events and bindings to seamlessly integrate additional services. A pay-per-execution model with sub-second billing charges only for the time and resources it takes to execute the code.

- Serverless Kubernetes:
> Developers bring their own containers to fully managed, Kubernetes-orchestrated clusters that can automatically scale up and down with sudden changes in traffic on spiky workloads.

- Serverless Workflows:
> Serverless workflows take a low-code/no-code approach to simplify orchestration of combined tasks. Developers can integrate different services (either cloud or on-premises) without coding those interactions, having to maintain glue code or learning new APIs or specifications.

- Serverless Application Environment:
> With a serverless application environment, both the back end and front end are hosted on fully managed services that handle scaling, security and compliance requirements.

- Serverless API Gateway:
> A serverless API gateway is a centralised, fully managed entry point for serverless backend services. It enables developers to publish, manage, secure and analyse APIs at global scale.











