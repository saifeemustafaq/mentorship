## Date: June 17, 2020

# 1. Serverless Computing: 
Serverless computing is a cloud computing execution model in which the cloud provider runs the server, and dynamically manages the allocation of machine resources. Pricing is based on the actual amount of resources consumed by an application, rather than on pre-purchased units of capacity. It can be a form of utility computing.

Serverless computing can simplify the process of deploying code into production. Scaling, capacity planning and maintenance operations may be hidden from the developer or operator. Serverless code can be used in conjunction with code deployed in traditional styles, such as microservices. Alternatively, applications can be written to be purely serverless and use no provisioned servers at all.

This should not be confused with computing or networking models that do not require an actual server to function, such as peer-to-peer (P2P).

# 2. Serverless Runtimes: 
Most, but not all, serverless vendors offer compute runtimes, also known as function as a service (FaaS) platforms, which execute application logic but do not store data. The first "pay as you go" code execution platform was Zimki, released in 2006, but it was not commercially successful. In 2008, Google released Google App Engine, which featured metered billing for applications that used a custom Python framework, but could not execute arbitrary code. PiCloud, released in 2010, offered FaaS support for Python. 
Kubeless and Fission are two Open Source FaaS platforms which run with Kubernetes.

AWS Lambda, introduced by Amazon in 2014, was the first public cloud infrastructure vendor with an abstract serverless computing offering. It is supported by a number of additional AWS serverless tools such as AWS Serverless Application Model (AWS SAM) Amazon CloudWatch, and others.


Google Cloud Platform offers Google Cloud Functions since 2016.

IBM offers IBM Cloud Functions in the public IBM Cloud since 2016.

Microsoft Azure offers Azure Functions, offered both in the Azure public cloud or on-premises via Azure Stack. 

# 3. Serverless Databases: 
Several serverless databases have emerged in the last few years. These systems extend the serverless execution model to the RDBMS, eliminating the need to provision or scale virtualized or physical database hardware.

Nutanix offers a solution named Era which turns an existing RDMS such as Oracle, MariaDB, PostgreSQL or Microsoft SQL Server into a serverless service.

Amazon Aurora offers a serverless version of its databases, based on MySQL and PostgreSQL, providing on-demand, auto-scaling configurations.

Azure Data Lake is a highly scalable data storage and analytics service. The service is hosted in Azure, Microsoft's public cloud. Azure Data Lake Analytics provides a distributed infrastructure that can dynamically allocate or de-allocate resources so customers pay for only the services they use.

Google Cloud Datastore is an eventually-consistent document store. It offers the database component of Google App Engine as a standalone service. Firebase, also owned by Google, includes a hierarchical database and is available via fixed and pay-as-you-go plans.

# 4. Advantages: 
- **Cost:**  
Serverless can be more cost-effective than renting or purchasing a fixed quantity of servers, which generally involves significant periods of underutilization or idle time. It can even be more cost-efficient than provisioning an autoscaling group, due to more efficient bin-packing of the underlying machine resources.
This can be described as pay-as-you-go computing or bare-code as you are charged based solely upon the time and memory allocated to run your code; without associated fees for idle time.

- **Elasticity vs Scalability:**   
In addition, a serverless architecture means that developers and operators do not need to spend time setting up and tuning autoscaling policies or systems; the cloud provider is responsible for scaling the capacity to the demand. As Google puts it: ‘from prototype to production to planet-scale.’
As cloud native systems inherently scale down as well as up, these systems are known as elastic rather than scalable.

- **Productivity:**  
With function as a service, the units of code exposed to the outside world are simple event driven functions. This means that typically, the programmer does not have to worry about multithreading or directly handling HTTP requests in their code, simplifying the task of back-end software development.

# 5. Disadvantages:  
- **Performance:**  
Infrequently-used serverless code may suffer from greater response latency than code that is continuously running on a dedicated server, virtual machine, or container. This is because, unlike with autoscaling, the cloud provider typically "spins down" the serverless code completely when not in use. This means that if the runtime (for example, the Java runtime) requires a significant amount of time to start up, it will create additional latency. 

- **Resource limits:**  
Serverless computing is not suited to some computing workloads, such as high-performance computing, because of the resource limits imposed by cloud providers, and also because it would likely be cheaper to bulk-provision the number of servers believed to be required at any given point in time. 

- **Monitoring and debugging:**  
Diagnosing performance or excessive resource usage problems with serverless code may be more difficult than with traditional server code, because although entire functions can be timed, there is typically no ability to dig into more detail by attaching profilers, debuggers or APM tools. Furthermore, the environment in which the code runs is typically not open source, so its performance characteristics cannot be precisely replicated in a local environment.






