     # What is AWS (Amazon Web Service)?
 - AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage and content delivery services.
 - AWS launched in 2006 from the internal infrastructure that Amazon.com built to handle its online retail operations. AWS was one of the first companies to introduce a pay-as-you-go cloud computing model that scales to provide users with compute, storage or throughput as needed.
 - AWS offers many different tools and solutions for enterprises and software developers that can be used in data centers in up to 190 countries. Groups such as government agencies, education institutions, nonprofits and private organizations can use AWS services.

# How it works?
 - AWS is separated into different services; each can be configured in different ways based on the user's needs. Users should be able to see configuration options and individual server maps for an AWS service.
   more than 100 services comprise the Amazon Web Services portfolio, including those for compute, databases, infrastructure management, application development and security. These services, by category, include:

   - Compute
   - Storage databases
   - Data management
   - Migration
   - Hybrid cloud
   - Networking
   - Development tools
   - Management
   - Monitoring
   - Security
   - Governance
   - Big data management
   - Analytics
   - Artificial intelligence (AI)
   - Mobile development
   - Messages and notification
   
# Features of AWS?
 ## 1) Flexibility


 - The difference between AWS and traditional IT models is flexibility.
The traditional models used to deliver IT solutions that require large investments in a new architecture, programming languages, and operating system. Although these investments are valuable, it takes time to adopt new technologies and can also slow down your business.
The flexibility of AWS allows us to choose which programming models, languages, and operating systems are better suited for their project, so we do not have to learn new skills to adopt new technologies.
Flexibility means that migrating legacy applications to the cloud is easy, and cost-effective. Instead of re-writing the applications to adopt new technologies, you just need to move the applications to the cloud and tap into advanced computing capabilities.
Building applications in aws are like building applications using existing hardware resources.
The larger organizations run in a hybrid mode, i.e., some pieces of the application run in their data center, and other portions of the application run in the cloud.
The flexibility of aws is a great asset for organizations to deliver the product with updated technology in time, and overall enhancing the productivity.

## 2) Cost-effective


- Cost is one of the most important factors that need to be considered in delivering IT solutions.
For example, developing and deploying an application can incur a low cost, but after successful deployment, there is a need for hardware and bandwidth. Owing our own infrastructure can incur considerable costs, such as power, cooling, real estate, and staff.
The cloud provides on-demand IT infrastructure that lets you consume the resources what you actually need. In aws, you are not limited to a set amount of resources such as storage, bandwidth or computing resources as it is very difficult to predict the requirements of every resource. Therefore, we can say that the cloud provides flexibility by maintaining the right balance of resources.
AWS provides no upfront investment, long-term commitment, or minimum spend.
You can scale up or scale down as the demand for resources increases or decreases respectively.
An aws allows you to access the resources more instantly. It has the ability to respond the changes more quickly, and no matter whether the changes are large or small, means that we can take new opportunities to meet the business challenges that could increase the revenue, and reduce the cost.

## 3) Scalable and elastic

- In a traditional IT organization, scalability and elasticity were calculated with investment and infrastructure while in a cloud, scalability and elasticity provide savings and improved ROI (Return On Investment).
Scalability in aws has the ability to scale the computing resources up or down when demand increases or decreases respectively.
Elasticity in aws is defined as the distribution of incoming application traffic across multiple targets such as Amazon EC2 instances, containers, IP addresses, and Lambda functions.
Elasticity load balancing and scalability automatically scale your AWS computing resources to meet unexpected demand and scale down automatically when demand decreases.
The aws cloud is also useful for implementing short-term jobs, mission-critical jobs, and the jobs repeated at the regular intervals.

## 4) Secure

AWS provides a scalable cloud-computing platform that provides customers with end-to-end security and end-to-end privacy.
AWS incorporates the security into its services, and documents to describe how to use the security features.
AWS maintains confidentiality, integrity, and availability of your data which is the utmost importance of the aws.
Physical security: Amazon has many years of experience in designing, constructing, and operating large-scale data centers. An aws infrastructure is incorporated in AWS controlled data centers throughout the world. The data centers are physically secured to prevent unauthorized access.

### Secure services: 
    Each service provided by the AWS cloud is secure.

### Data privacy: 
     A personal and business data can be encrypted to maintain data privacy.

## 5) Experienced

- The AWS cloud provides levels of scale, security, reliability, and privacy.
AWS has built an infrastructure based on lessons learned from over sixteen years of experience managing the multi-billion dollar Amazon.com business.
Amazon continues to benefit its customers by enhancing their infrastructure capabilities.
Nowadays, Amazon has become a global web platform that serves millions of customers, and AWS has been evolved since 2006, serving hundreds of thousands of customers worldwide.

# disadvantage of AWS 

  

These are the limitations of Amazon Web Services:

   ## - i. Limitations OF Amazon EC2

                AWS sets default limits on resources which vary from region to region. These resources consist of                   images, volumes, and snapshots. You can launch the limited number of instance per area. It also                     provides limited information for the resources managed by Amazon EC2and Amazon VPC console. However,                 you can request to increase the limit 

  ## - ii. Security Limitations

                  As security is one of the main features so AWS limits some of its features which cannot be changed                   at all are-

        ### - EC-2 classic- Maximum of 500 per instance and each Security Group can have a maximum of 100                                       permissions.
        ### - EC2-VPC- Up to 100 security groups per VPC.

  ## - iii. Technical Support Fee

              AWS charges you for immediate support and you can opt for any packages among 3 which are-

          - Developer
          - Business
          - Enterprise


             AWS does have general cloud computing issues when you move to a cloud such as a downtime, limited                    control, and backup protection. However, these flaws can be overcome after some time. This makes them      

          the temporary issue.
AWSInsider.netThe Independent Resource for Amazon Web Services
Home
News
How-To
Whitepapers
Webcasts
Advertise
Newsletter
AWS Step-by-Step


# - Creating and Logging In to a Windows VM in AWS
Don't be fooled. While it sounds rudimentary, the process of deploying an Amazon EC2 virtual machine can be disorienting if you're coming from a native Windows Server environment.

By Brien Posey08/16/2016
Logging in to a virtual machine (VM) seems like a simple thing to do. It's so simple, in fact, that I seriously considered skipping this topic in favor of something else.

Even so, when Windows administrators use Amazon Elastic Compute Cloud (EC2) for the first time, they often find that they are not quite sure how to deploy and log in to a VM.

The process isn't difficult, but it is significantly different from a native Windows Server environment (especially logging in for the first time). As such, I wanted to take the opportunity to show you how this works.

The first thing that you need to understand about creating and logging in to Amazon Web Services (AWS) virtual machines is that Amazon does not refer to them as virtual machines. In Amazon-speak, "virtual machines" are "instances." You can access instances by logging in to the AWS console, and going into EC2. You can create a new instance by clicking on the Launch Instance button, shown in Figure 1.

 
[Click on image for larger view.]
Figure 1: Click on the Launch Instance button to create an AWS instance.
Upon clicking on the Launch Instance button, you will be taken to a screen that asks you to choose an Amazon Machine Image. Amazon Machine Image, or AMI, is another term that you need to be familiar with. An AMI is a template from which you can create a VM. Amazon provides Windows AMIs, as well as AMIs for a variety of Linux builds. At this point, you must simply select the AMI that you want to use, and click Select. For the purposes of this article, I am going to assume that you are creating a Windows VM.

Once you have chosen an AMI, you will be prompted to choose an instance type. The instance type determines the hardware resources that will be allocated to the instance that you are creating. For example, the instance type determines the number of virtual CPUs and the amount of memory that is assigned to the instance. After making your selection, click the Next: Configure Instance Details button, shown in Figure 2.

 
[Click on image for larger view.]
Figure 2: Choose your instance type.
The next screen that you will see is the Configure Instance Details screen. If you have ever created VMs using Hyper-V or Microsoft Azure, then this screen will be completely intuitive. It asks you which network you want to use, whether you want to join a domain -- that sort of thing. You can see the configuration options shown in Figure 3.

 
[Click on image for larger view.]
Figure 3: The Configure Instance Details screen provides some basic configuration options.
Click Next: Add Storage, and you will be taken to the Add Storage screen. As you would expect, this screen lets you configure the storage type and volume size. You can also create new volumes.

Click Next: Tag Instance, and you will be taken to the Tag Instance screen. You don't really have to do anything on this screen. It exists only for the purpose of applying text tags to the instance. You can use these tags as a way of identifying or categorizing the instance.

Click Next: Configure Security Group and you will be taken to the Configure Security Group screen. Security groups are essentially a collection of instances that share a common set of firewall rules. You can use the Configure Security Group screen to create or join a security group, and to configure the group's firewall rules.

Click the Review and Launch button, and you will be taken to a screen that allows you to review the configuration options that you have chosen. Assuming that everything looks good, click the Launch button. Upon doing so, EC2 will display what is arguably the most important screen used in the entire process.

As you can see in Figure 4, AWS prompts you to create a key pair. This is a crucially important step, because you won't be able to log in to the instance unless you create a key pair. Simply choose the Create a New Key pair option, and then enter a name for the key pair that you want to create. After doing so, click the Download Key Pair button, and save the resulting file to a safe location.

 
[Click on image for larger view.]
Figure 4: Be sure to create and download a key.
At this point, you can click the Launch Instance button to create your instance. The process takes some time to complete, but your new instance will eventually be ready for use. Go to the AWS home screen, click on EC2, and then click on the Instances link to see your instance.

Once the instance no longer displays an initializing message, you can log in to the VM. To do so, right-click on the instance's checkbox and choose the Get Windows Password option from the shortcut menu, as shown in Figure 5.

 
[Click on image for larger view.]
Figure 5: Right click on the instance, and choose the Get Windows Password option.
Upon doing so, you will see a dialog box prompting you for your key file. Click the Browse button and the select your key file. After doing so, click on the Decrypt Password button, shown in Figure 6. Upon doing so, your user name and password will be displayed, along with a reminder to change your password.

 
[Click on image for larger view.]
Figure 6: Provide the key file and then click Decrypt Password.
Close the dialog box, click on your instance and click the Connect button. You will now be prompted to download an .RDP file for the instance. Open the file, and you will be prompted to enter your password, as shown in Figure 7. You will now be taken into the instance. Keep in mind, however, that the first time that you log in to an instance, it may take a couple of minutes before the session displays anything other than a black screen.


