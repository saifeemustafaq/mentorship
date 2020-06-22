## Date June 22, 2020.

 # What is scaling in cloud computing?

Scaling is defined as the ability for an IT resource to handle growing or decreasing demands in a capable manner. It is one of the most popular and beneficial features of cloud computing, as businesses can scale up or down to meet demands based on season, projects, growth and more. By implementing cloud scalability, you enable your resources to grow as your traffic or organization grows, and vice versa.

 ![](https://www.dummies.com/wp-content/uploads/274803.image0.jpg)

### **_There are a few main ways to scale in the cloud :-_**

## Vertical Scaling :-

- To understand vertical scaling, envision a 20-story hotel. Within this hotel, there are countless rooms that guests constantly move in and out of. There are often spaces available, as not all of the rooms are occupied at the same time. People can easily come and go because there is space to accommodate them. As long as the capacity of this hotel is not exceeded, there is no issue. This is vertical scaling.

- With computing, you can add or subtract resources, including memory or storage, within a server as long as the resources do not exceed the capacity of the machine itself. Similar to the hotel example, resources can come and go easily and quickly, as long as there is room for them. Though it has limitations, this is a way to beef up your server and avoid latency and extra management.

## Horizontal Scaling :-

- Horizontal scaling is a bit different. This time, imagine a two-lane highway. Cars easily travel in each direction without huge traffic issues. But then the area surrounding the highway is developed – new buildings are built and traffic increases. Pretty soon, this two-lane highway is clogged with cars, and accidents become commonplace. It’s clear that two-lanes are no longer enough. In order to avoid these issues, more lanes are added and an overpass is constructed. While this takes a significant amount of time, it solves the problem.

- Horizontal scaling refers to adding more servers to your network, rather than simply adding resources like with vertical scaling. This method tends to take more time and is more complex, but it allows you to connect servers together, handle traffic efficiently and execute concurrent workloads.

## Diagonal Scaling :-

- So what happens if you combine the two scaling methods? Well, you get diagonal scaling, which allows you to experience the most efficient infrastructure scaling. When you combine vertical and horizontal, you simply grow within your existing server until you hit the capacity. Then, you can clone that server as necessary and continue the process, allowing you to deal with a lot of requests and traffic concurrently.

## Scale in the Cloud :-

- When you move scaling into the cloud, you experience an enormous amount of flexibility that saves both money and time for a business. When your demand booms, it’s easy to scale up to accommodate the new load. As things level out again, you can scale down accordingly. This is so significant because cloud computing uses a pay-as-you-go model. Traditionally, professionals guess their maximum capacity needs and purchase everything up front. If they overestimate, they pay for unused resources. If they underestimate, they don’t have the services and resources necessary to operate effectively. With cloud scaling, though, businesses get the capacity they need when they need it, and they simply pay based on usage. This on-demand nature is what makes the cloud so appealing. You can start small and adjust as you go. It’s quick, it’s easy, and you’re in control.

- The benefits of the scalable cloud are clear. You can support business growth without making expensive or timely changes to your current setup. With a managed cloud provider, it’s quick and easy to get the resources you need as you need them, and you’re not bound by the size of your server closet. The cloud provider will ensure that overloading is never a concern, as their team will manage the servers within the data center. When you grow, the cloud will grow.

## What is Serverless Computing?

- Serverless computing is a method of providing backend services on an as-used basis. Servers are still used, but a company that gets backend services from a serverless vendor is charged based on usage, not a fixed amount of bandwidth or number of servers.

- A Serverless architecture allows users to write and deploy code without the hassle of worrying about the underlying infrastructure. A company that gets backend services from a serverless vendor is charged based on their computation and do not have to reserve and pay for a fixed amount of bandwidth or number of servers, as the service is auto-scaling. Note that although called serverless, physical servers are still used but developers do not need to be aware of them.

- In the early days of the web, anyone who wanted to build a web application had to own the physical hardware required to run a server, which is a cumbersome and expensive undertaking.

- Then came the cloud, where fixed numbers of servers or amounts of server space could be rented remotely. Developers and companies who rent these fixed units of server space generally over-purchase to ensure that a spike in traffic or activity wouldn’t exceed their monthly limits and break their applications. This meant that much of the server space that was paid for usually went to waste. Cloud vendors have introduced auto-scaling models to address the issue, but even with auto-scaling an unwanted spike in activity, such as a DDoS Attack, could end up being very expensive.

![](https://www.cloudflare.com/resources/images/slt3lc6tev37/7nyIgiecrfe9W6TfmJRpNh/dfc5434659e31300d1918d4163dfb263/benefits-of-serverless.svg)

- Serverless computing allows developers to purchase backend services on a flexible ‘pay-as-you-go’ basis, meaning that developers only have to pay for the services they use. This is like switching from a cell phone data plan with a monthly fixed limit, to one that only charges for each byte of data that actually gets used.

- The term ‘serverless’ is somewhat misleading, as there are still servers providing these backend services, but all of the server space and infrastructure concerns are handled by the vendor. Serverless means that the developers can do their work without having to worry about servers at all.

## What are backend services? What’s the difference between frontend and backend?

- Application development is generally split into two realms: the frontend and the backend. The frontend is the part of the application that users see and interact with, such as the visual layout. The backend is the part that the user doesn’t see; this includes the server where the application's files live and the database where user data and business logic is persisted.

![](https://www.cloudflare.com/img/learning/serverless/what-is-serverless/frontend-vs-backend.svg)

## What are the advantages of serverless computing?

- **Lower costs** - Serverless computing is generally very cost-effective, as traditional cloud providers of backend services (server allocation) often result in the user paying for unused space or idle CPU time.

- **Simplified scalability** - Developers using serverless architecture don’t have to worry about policies to scale up their code. The serverless vendor handles all of the scaling on demand.

- **Simplified backend code** - With FaaS, developers can create simple functions that independently perform a single purpose, like making an API call.

- **Quicker turnaround** - Serverless architecture can significantly cut time to market. Instead of needing a complicated deploy process to roll out bug fixes and new features, developers can add and modify code on a piecemeal basis.
