# Final Notes 

## Chapter 01 Cloud Concepts
Infrastructure: the components that make up IT, for example physical components like harware. Can also include software and networks.

Development: the process of creating a software. Steps include determining needs, designing, testing, fixing bugs, etc.

Security: Process of keeping designed software (networks, data, etc.) safe from hackers.

Data: Both hardware and software fall under Data. Hardware like HDD and SSD's store data, software is what accesses the data. Forms of data include Word Documents, photos, etc.
Learning the basic components of a computer are necessary in order to understand Cloud computing. Some components are not required in cloud like motherboard or basic input/output information. Since cloud is a virtual computer, it is important to be knowledgable on CPU's, RAM, Storage and GPU's.

## Chapter 02 Cloud Econ and Billing
Compute: charged per hr

Storage: charged per GB

Data transfer: outbound data has a charge, inbound data does not.

PAY AS YOU GO!! pay only for what you use. 

TCO : Total Cost of Ownership is the financial estimate and cost expense for your business.

Server, Network and Storage costs are somethings to take into consideration. AWS provides a TCO calculator. 

## Chapter 03 Global Infrastructure
AWS Regions are regions where infrastructure is held. The closer you are to a region, the faster the service will be.

AZ is the building that makes up the AWS Region. Having multiple AZ's is beneficial, gives you more back up options just in case an instance fails and you have more resources to use.

Scalability and elastic: can adjust to changes in capacity requirements, much room for growth

Fault tolerant: ability to continue operating even with failed components

Compute: supports big data processing and research examples: EC2, EC2 Scaling, Elastic Container and Elastic Registry

Storage: scalable, secure, reliable examples: Amazon S3 (Simple Storage Server), Elastic Block Store, Elastic File System

Databases: use cases and provide speed, reliability, availibility examples: Amazon Relational Database Service (RDS), Amazon Aurora, Amazon Redshift

Networking: preformance, global coverage, manageability, availibility examples: Amazon Private Cloud (VPC), Elastic Load Banding, CloudFront, Tranist Gateway 

## Chapter 04 Cloud Security
IAM : Web service that helps you secure control access with those you chose. 

Principle of least privlidge: giving users limited amount of access

## Chapter 05 Networking and Content Delivery
Amazon Virtual Private Cloud lets you isolate a section of the AWS Cloud and use it to launch resources in a private network. You have the ability to chose your own IP Address range and have full control over your networks, subnets and route tables. You can launch EC2 instances in your VPC and access across multiple AZ's in the same Region 


## Chapter 09 Storage 
Types of Storage: Volatile (RAM) which loses memory once power is interrupted and NonVolatile (ROM) is saved regardless of interruptions eg. Hard drive or flash memory

Block storage vs object storage 

Block storage updates the block of storage that was configured, object storage updates the whole file. 

EBS is block storage and allows you to create individual storage volumes and then attach them to instances 

S3 is object level storage, data is stored in buckets. Bucket names must b unique worldwide

EFS: storage for Ec2 instances

Commonly used storage 
S3 standard storage: high availability & durability for frequently accessed data

S3 standard infrequent access: long term storage for data not frequently accessed 

S3 Glacier: secure data archiving, data retrieval takes from min-hours

## Chapter 10 Databases 

Relational Database: collection of data with predefined relationship 

Primary key: a unique identifier 



