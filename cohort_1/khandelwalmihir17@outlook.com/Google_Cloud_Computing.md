# Load Balancing. 
- With global Cloud Load Balancing, your application presents a single front-end to the world. You no need to worry about managing or scaling them.
- Google VPC offers a suite of load balancing options.
1. Global HTTP(S).
2. Global SSL Proxy.
3. Global TCP Proxy.
4. Regional.
5. Regional Internal.
- Google Cloud Platfrom offers many interconnect options.
1. VPN.
2. Direct Peering.
3. Carrier Peering.
4. Dedicated Interconnect.
# Cloud Storage.
- It is binary large object storage with multiple classes;
  - Multi-regional.
  - Regional.
  - Nearline.
  - Coldline.
- High performance, internet scale, simple adminstration and doesn't require capacity management.
- Storage files are organized into buckets.
- Ways to bring data into cloud.
  - Online Transfer.
  - Storage Transfer Service.
  - Transfer Appliance.
- Cloud Spanner is a horizontal scalable RDBMS, and also managed by RDBMS.
- Cloud Storage works with other GCP services such as BigQuery, Compute Engine, App Engine and Cloud SQL.
- Cloud Datastore is a horizontally scalable NoSQL database, which is designed for application backends, supports transactions and includes a free daily quota.
# Containers in the Cloud.
- Containers offer a logical packaging mechanism in which applications can be abstracted from the environment in which they actually run.
- Like virtual machines, containers allow you to package your application together with libraries and other dependencies, providing isolated environments for running your software services. 
- GKE On-Prem is the turn-key production-grade Kubernetes. Here marketplace applications are available to all clusters.
- Google Cloud Platform ans On-Prem Data Center are both linked by GCP marketplace, to reduce time loss, to access the same repository, and many more.
- Features of Kubernetes are as follows.
  - Check Automated rollouts and roll backs.
  - Check Service health monitoring.
  - Check Automatic scaling of services.
  - Check Declarative management.
  - Check Deploy anywhere, including hybrid deployments.
- Distributed systems housed on-premises are difficult as well as costly to upgrade.
- Anthos is Google's mordern solution for hybrid and multi-cloud systems by the latest innovations. A rich set of tools is provided for:-
  - Managing services on-premises and in the cloud.
  - Monitoring systems and services.
  - Migrating applications from VMs into your clusters.
# Google App Engine.
- The App Engine standard environment helps to easily deploy our applications, autoscale workloads, free daily quota, and usage based pricing.
- In it the SDK is used development, testind , and deployment.
- It requires specific versions of Java, Phyton, PHP, and Go are supported.
- Sandbox constraints has:-
  - No writing to local files.
  - All requests time out at 60 seconds.
  - Limits on third-party software.
- App Engine has very flexible environment with no sandbox constraints, can access App Engine resources and build and deploy apps. It also has standard environment. 
- A platform for making APIs available to your customers and partners is called apigee. It also has analytics, monetization, and a developer portal.
- A Cloud Endpoints helps you to create and maintain APIs.
- 
