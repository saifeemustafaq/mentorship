## Date: June 18, 2020

> # What are containers?

### **A container 'contains' both an application and all the elements the application needs to run properly, including system libraries, system settings, and other dependencies. Like a 'just add water' pancake mix, containers only need one thing – to be hosted and run – in order to perform their function.**

![](https://www.cloudflare.com/resources/images/slt3lc6tev37/1gvXz5W1hmZwwcpIDy2LFF/6c9df86d9642b53b9ab1646d3cf9ae16/how-containers-work.svg)

- **Any kind of application can be run in a container. A containerized application will run the same way no matter where it is hosted. Containers can easily be moved around and deployed wherever needed, much like physical shipping containers, which are a standard size and can therefore be shipped anywhere via a variety of means of transport (ships, trucks, trains, etc.) regardless of their contents.**

- **Each container shares the machine's kernel with other containers (the kernel is the foundation of the operating system, and it interacts with the computer's hardware), but it runs as if it were the only system on the machine.**

> # ***What is serverless computing?***

- **Serverless computing is a method of providing backend services on an as-used basis. A Serverless architecture allows users to write and deploy code without the hassle of worrying about the underlying infrastructure.** 

- **A company that gets backend services from a serverless vendor is charged based on their computation and do not have to reserve and pay for a fixed amount of bandwidth or number of servers, as the service is auto-scaling.**

- **Serverless computing allows developers to purchase backend services on a flexible ‘pay-as-you-go’ basis, meaning that developers only have to pay for the services they use. This is like switching from a cell phone data plan with a monthly fixed limit, to one that only charges for each byte of data that actually gets used.**



> # ***Serverless computing vs. containers :***

- **Both serverless computing and containers enable developers to build applications with far less overhead and more flexibility than applications hosted on traditional servers or virtual machines.**



- **Which style of architecture a developer should use depends on the needs of the application, but serverless applications are more scalable and usually more cost-effective.**


> # Key differences between serverless computing and containers :

## Physical machines :

- **'Serverless' computing actually runs on servers, but it is up to the serverless vendor to provision server space as it is needed by the application; no specific machines are assigned for a given function or application. On the other hand, each container lives on one machine at a time and uses the operating system of that machine, though they can be moved easily to a different machine if desired.**

## Scalability:

- **In a container-based architecture, the number of containers deployed is determined by the developer in advance. In contrast, in a serverless architecture, the backend inherently and automatically scales to meet demand.**

## Cost :

- **Containers are constantly running, and therefore cloud providers have to charge for the server space even if no one is using the application at the time.**

- **There are no continued expenses in a serverless architecture because application code does not run unless it is called. Instead, developers are only charged for the server capacity that their application does in fact use.**

## Maintenance :

- **Containers are hosted in the cloud, but cloud providers do not update or maintain them. Developers have to manage and update each container they deploy.**

- **From a developer's perspective, a serverless architecture has no backend to manage. The vendor takes care of all management and software updates for the servers that run the code.**


## Time of deployment:

- **Containers take longer to set up initially than serverless functions because it is necessary to configure system settings, libraries, and so on. Once configured, containers take only a few seconds to deploy. But because serverless functions are smaller than container microservices and do not come bundled with system dependencies, they only take milliseconds to deploy.** 

![](https://www.cloudflare.com/img/learning/serverless/serverless-vs-containers/serverless-computing-deploy-speed-comparison.svg)

## Testing:

- **It is difficult to test serverless web applications because the backend environment is hard to replicate on a local environment. In contrast, containers run the same no matter where they are deployed, making it relatively simple to test a container-based application before deploying it to production.**

> # ***Advantages of serverless computing?***

## **1. Lower costs -** 

Serverless computing is generally very cost-effective, as traditional cloud providers of backend services (server allocation) often result in the user paying for unused space or idle CPU time.

## 2. Simplified scalability -

Developers using serverless architecture don’t have to worry about policies to scale up their code. The serverless vendor handles all of the scaling on demand.

## Simplified backend code -

With FaaS, developers can create simple functions that independently perform a single purpose, like making an API call.

## Quicker turnaround - 

Serverless architecture can significantly cut time to market. Instead of needing a complicated deploy process to roll out bug fixes and new features, developers can add and modify code on a piecemeal basis.
