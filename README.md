# cloud_computing_interview_questions
Important cloud computing interview questions

1. What is a Cloud Technology?

A cloud is a combination of services, networks, hardware, storage, and interfaces that helps in delivering computing as a service. It broadly has three users. These are the end-user, business management user, and cloud service, provider. The end-user is the one who uses the services provided by the cloud. The responsibility of the data and the services provided by the cloud is taken by the business management user in the cloud. The one who takes care of or is responsible for the maintenance of the IT assets of the cloud is the cloud service provider. The cloud acts as a common center for its users to fulfill their computing needs.

2. What are some of the key features of Cloud Computing?

The following are some of the key features of cloud computing:

1. Agility: Helps in quick and inexpensive re-provisioning of resources.
2. Location Independence: This means that the resources can be accessed from everywhere.
3. Multi-Tenancy: The resources are shared amongst a large group of users.
4. Reliability: Resources and computation can be dependable for accessibility.
5. Scalability: Dynamic provisioning of data helps in scaling. 

3. What do you mean by cloud delivery models?

Cloud delivery models are models that represent the computing environments. These are as follows:

1. Infrastructure as a Service (IaaS): Infrastructure as a Service (IaaS) is the delivery of services, including an operating system, storage, networking, and various utility software elements, on a request basis. 
2. Platform as a Service (PaaS): Platform as a Service (PaaS) is a mechanism for combining Infrastructure as a Service with an abstracted set of middleware services, software development, and deployment tools. These allow the organization to have a consistent way to create and deploy applications on a cloud or on-premises environment.
3. Software as a Service (SaaS): Software as a Service (SaaS) is a business application created and hosted by a provider in a multi-tenant model. 
4. Function as a Service (FaaS): Function as a Service (FaaS) gives a platform for customers to build, manage and run app functionalities without the difficulty of maintaining infrastructure. One can thus achieve a "serverless" architecture.

![image](https://user-images.githubusercontent.com/81725794/183340143-f9ac883a-28af-4b06-bb62-83754041d6ae.png)

4. What are the different versions of the cloud?

There are two primary deployment models of the cloud: Public and Private. 

1. Public  Cloud: The set of hardware, networking, storage, services, applications, and interfaces owned and operated by a third party for use by other companies or individuals is the public cloud. These commercial providers create a highly scalable data center that hides the details of the underlying infrastructure from the consumer. Public clouds are viable because they offer many options for computing, storage, and a rich set of other services.
2. Private Cloud: The set of hardware, networking, storage, services, applications, and interfaces owned and operated by an organization for the use of its employees, partners, or customers is the private cloud. This can be created and managed by a third party for the exclusive use of one enterprise. The private cloud is a highly controlled environment not open for public consumption. Thus, it sits behind a firewall.
3. Hybrid Cloud: Most companies use a combination of private computing resources and public services, called the hybrid cloud environment. 
4. Multi-Cloud: Some companies, in addition, also use a variety of public cloud services to support the different developer and business units – called a multi-cloud environment.

6. What are the main constituents that are part of the cloud ecosystem?

The parts of the cloud ecosystem that determine how you view the cloud architecture are:

Cloud consumers
Direct customers
Cloud service providers

6. Who are the Cloud Consumers in a cloud ecosystem?

The individuals and groups within your business unit that use different types of cloud services to get a task accomplished. A cloud consumer could be a developer using compute services from a public cloud.

7. Who are the Direct customers in a cloud ecosystem?

Users who often take advantage of services that your business has created within a cloud environment. The end-users of your service have no idea that you’re using a public or private cloud. As long as the users are concerned, they’re interacting directly with the services and value.

8. Who are the Cloud service providers in a cloud ecosystem?

Cloud service providers are the commercial vendors or companies that create their own capabilities. The commercial vendors sell their services to cloud consumers. In contrast to this, a company might decide to become an internal cloud service provider to its own partners, employees, and customers, either as an internal service or as a profit center. Cloud service providers also create applications or services for such environments.

9. Describe the Cloud Computing Architecture.

The cloud computing architecture is all the components of a cloud model that fit together from an architectural perspective. The figure below depicts how the various cloud services are related to support the needs of businesses. On the left side, the cloud service consumer represents the types of uses of cloud services. No matter what the requirements of the particular constituent are, it is important to bring the right type of services together that can support both internal and external users. Management of the consumers should be able to make services readily available to support the changing business needs. The applications, middleware, infrastructure, and services that are built based on on-premises computing models are within this category. In addition to this, the model depicts the role of a cloud auditor. This organization provides an oversight either by an internal or external group which makes sure that the consumer group meets its obligations.

![image](https://user-images.githubusercontent.com/81725794/183340255-744ca15e-2d89-4b8c-adaa-47e4ac3dffcc.png)

10. What are the Cloud Storage Levels?


Cloud storage device mechanisms provide common levels of data storage, such as:

Files – These are collections of data that are grouped into files that are located in folders.
Blocks – A block is the smallest unit of data that is individually accessible. It is the lowest level of storage and the closest to the hardware.
Datasets – Data sets organized into a table-based, delimited, or record format.
Objects – Data and the associated metadata with it are organized as web-based resources.
Each of the above data storage levels is associated with a certain type of technical interface. This interface corresponds to a particular type of cloud storage device and the cloud storage service used to expose its API.

![Uploading image.png…]()

11. What are serverless components in cloud computing?

Serverless components in cloud computing allow the building of applications to take place without the complexity of managing the infrastructure. One can write code without having provision to a server.

Serverless machines take care of virtual machines and container management. Multithreading, hardware allocating are also taken care of by the serverless components. 

12. What are the advantages and disadvantages of serverless computing?

Serverless computing has the following advantages and disadvantages:
Advantages:

It is cost-effective.
The operations on serverless computing are simplified.
Serverless computing helps boost productivity.
It offers scaling options.
It involves zero server management.
Disadvantages:

Serverless code can cause response latency.
It is not ideal for high-computing operations because of resource limitations.
For serverless computing, the responsibility of security comes under the service company and not the consumer, which might be more vulnerable.
Debugging serverless code is a bit more challenging.

13. What are cloud-enabling technologies?

There are several areas of technology that contribute to modern-day cloud-based platforms. These are known as cloud-enabling technologies. Some of the cloud-enabling technologies are:

Broadband Networks and Internet Architecture
Data Center Technology
(Modern) Virtualization Technology
Web Technology
Multitenant Technology
Service Technology

14. What are Microservices?

Microservices is a process of developing applications that consist of code that is independent of each other and of the underlying developing platform. Each microservice runs a unique process and communicates through well-defined and standardized APIs, once created. These services are defined in the form of a catalog so that developers can easily locate the right service and also understand the governance rules for usage.

15. Why are microservices important for a true cloud environment?

The reason why microservices are so important for a true cloud environment is because of these four key benefits:

Each microservice is built to serve a specific and limited purpose, and hence application development is simplified. Small development teams can then focus on writing code for some of the narrowly defined and easily understood functions.
Code changes will be smaller and less complex than with a complex integrated application, making it easier and faster to make changes, whether to fix a problem or to upgrade service with new requirements.
Scalability — Scalability makes it easier to deploy an additional instance of a service or change that service as needs evolve.
Microservices are fully tested and validated. When new applications leverage existing microservices, developers can assume the integrity of the new application without the need for continual testing.

16. What is the cloud usage monitor?
