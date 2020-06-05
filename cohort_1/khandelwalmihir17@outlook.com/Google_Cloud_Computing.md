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
# Developing, Deploying and Monitoring in the Cloud.
- Deployment manager provides repeatable deployments, create a .yaml template describing your environment and use Deployment Manager to create resources.
- Cloud Functions:-
  - Create single purpose functions that respond to events without a server or runtime.
  - It is written in javascript; execute in managed Node.js environment on Google Cloud Platform.
- Google Cloud Stackdriver performs the following functions and offers the 6 capabilities.
  - Monotoring.
  - Logging.
  - Debugging.
  - Error Reporting.
  - Trace.
  - Profiler(Beta).
# Big Data and Machine Learning in the Cloud.
- Google Cloud Big Data services are fully managable and scalable. It includes:-
1. Cloud Dataproc:- It is managed by Hadoop. Fast, easy, managed way to run Hadoop and Spark/Hive/Pig on GCP. It can create clusters in 90 seconds or less, and can also scale cluster up and down when jobs are running. It is used because it easily migrates on-premises Hadoop jobs on the cloud. 
2. Cloud Dataflow:- It offers managed data pipelines. It processes data using Compute Engine instances. It has automatic scaling and clusters are sized for you. It is used for ETL(extract/transform/load) pipelines to move, filter, enrich, shape data. Also it is used for Orchestration. Integrates with GCP services like Cloud Storage, Cloud Pub/Sub, BigQuery, and Bigtable.
3. BigQuery:- It is fully managed daat warehouse. Provides near real-time interactive analysis of massive datasets. Here no cluster maintainence required. It runs on Google's high-performance infrastructure. You only pay for storage and processing used. Automatic discount for long-term data storage.
4 .Cloud Pub/Sub:- It is scalable, reliable messaging. It includes many-to-many messaging, application components make push/pull subscriptions to topics. It is used for building block for data ingestion in dataflow, IoT, Marketing Analysis, aslo foundation for Dataflow streaming. It also connect applications across Google Cloud Platform. 
5. Cloud Datalab:- It offers interactive data exploration. It has integrated open source like Jupyter(formely IPhyton), interactive tool for large-scale data exploration, transformation, analysis, and visualization. Easily deploy models to BigQuery. Analyze data in BigQuery, Compute Engine, and Cloud Storage using Python, SQL, and JavaScript.
# Cloud Vision API.
- It helps to analyze logo detection, label detection and other images with a simple REST API. Cloud Natural Language API can return text in real time, highly accurate, and can be access from any device. Uses Machine Learning models meaning and structure of text, can also be used to extract data from news, articles, and blog post. It also have the facility of Video Intellingence API. 
