# AWS Academy Cloud Foundations

## Module 1 - Cloud Concepts Overview

### Section 1 - Introduction to Cloud Computing

* Cloud computing presents infrastructure as software rather than infrastructure as hardware.
  * Infrastructure as a software: flexible, pay-as-you-go, low initial cost, focus on business and customers
  * Infrastructure as a hardware: acquisition, provision and maintenance = high cost

* Types of cloud computing
  * Infrastructure as a Service `IaaS` : basic building blocks
  * Platform as a Service `PaaS` : manage hardware and operating systems
  * Software as a Service `SaaS` : complete product that is run and managed by the service provider

* Deployment models
  * `Cloud` : A cloud-based application is fully deployed in the cloud and all parts of the application run in the cloud
  * `Hybrid` : A hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud
  * `On-premises` : Deploying resources on-premises, using virtualization and resource management tools, is sometimes called “private cloud” (similar to traditional physical infrastructure)

### Section 2 - Cloud Computing Advantages

* Investment in physical datacenters is based on usage forecasts, so hardware can be idle
* Physical server capacity can be overestimated or underestimated when server utilization fluctuates
* For the cloud environment, only what is consumed is paid, offering elasticity to the customer, that is, resources can be increased or reduced quickly and practically.
* Speed, agility and lower cost for applying new features
* Focus on the business and customers instead of operating in datacenters
* **Easier deployment** in different regions around the world, offering lower latency and better customer experience
* Hundreds of thousands of customers aggregated in the cloud result in **economies of scale**, that is, the customer gains from cost reduction

### Section 3 - Introduction to Amazon Web Services (AWS)

* AWS focus in operational expenses instead capital
* Main services:
  * ``AMAZON EC2`` : complete control over aws computing resources/infrastructure
  * ``AWS LAMBDA`` : run code and and not manage or provision servers
  * ``AWS ELASTIC BEANSTALK`` : provision a service tha deploys, manages and scale automatically web aplications
  * ``AMAZON LIGHTSAIL`` : cloud platform for a simple web aplication
  * ``AWS BATCH`` : to reliably run thousands of batch workloads
  * ``AWS OUTPOSTS`` : run AWS infrastructure in local datacenters
  * ``AMAZON ECS, EKS OR AWS FARGATE`` : implementation of containers or microservices architecture
  * ``VMware Cloud on AWS`` : local virtualization platform migration to AWS
* Service categories
  * Database, computing, storage, networks, content delivery, security, identity, compliance, management and governance and cost management

* 3 main ways to access and create the aws ecosystem (created using an app programming interface like REST)
  * ``AWS Management Console`` : advanced graphic user interface web browser
  * ``AWS Command Line Interface (AWS CLI)`` : accessing services by commands or specific scripts with the AWS ecosystem using linux, macOS or windows
  * ``Tools to Build on AWS (SDKs)`` : accessing services directly from your code (java, python, etc) through packages provided by AWS

### Section 4 - Change to AWS Cloud - AWS Cloud Adoption Framework (AWS CAF)

* Guidance and best practices to help organizations create a approach to cloud computing for the whole organization to accelerate successful cloud adoption
* Perspectives:

![rep](/images/perspectives.png)

* Each perspective consists of a set of resources covering different managed responsibilities owned by multifuncional teams
* Resources are used to identify which areas require attetion and when identifying gaps, prescriptive workflows are created that support a well journey successful for the cloud

## Module 2 - Cloud Savings and Billing
