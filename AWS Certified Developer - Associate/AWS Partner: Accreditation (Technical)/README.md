#### A solutions architect is designing a highly-scalable system to store back up files. When the files are needed, they must be available for immediate download. The solutions architect has a requirement to maintain the records for 1 year, and then the records must be deleted. Which solution is appropriate for this scenario?

- Store the files on Amazon Elastic Block Store (Amazon EBS) and create a lifecycle policy to remove the files after 1 year
- Store the files on Amazon Elastic File System (Amazon EFS) and create a lifecycle policy to remove the files after 1 year
- Store the files on an Amazon EC2 instance
> - Store the files on Amazon S3 and create a lifecycle policy to remove the files after 1 year


#### A network administrator needs to design a network topology that maintains redundancy and fault tolerance. What is the minimum number of Availability Zones required in this scenario?

- 3
- 4
> - 2
- 5


#### A solutions architect is designing an application on the Amazon EC2 Auto Scaling service to keep a steady and predictable performance at the lowest cost. Which autoscaling features can the solutions architect can use? (Select TWO.)

> - Automatic scaling
- Fleet management
- Turning off servers when the traffic is lowered ❌
- Manually adding and removing servers
- Turning off servers to save electricity


#### A media streaming company is consistently receiving feedback regarding the poor recommendations that are being offered. Which AWS service should the company use to improve their recommendation engine?

> - Amazon Neptune
- Amazon ElastiCache
- Amazon DynamoDB
- Amazon Timestream


#### An application developer wants to build an e-commerce website that is expected to have high traffic. Which purpose-built database service can provide performance and scale for the website?

- Amazon DocumentDB (with MongoDB compatibility)
> - Amazon DynamoDB
- Amazon ElastiCache
- Amazon Timestream


#### A solutions architect is building a highly available photo sharing application. The application serves the photos from Amazon S3 and stores the data in Amazon DynamoDB. The application is hosted on a single Amazon EC2 instance. What should the solutions architect do to improve application availability in this architecture?

> - Create another EC2 instance in a different Availability Zone
- Create a lifecycle policy to store the data in Amazon S3 Glacier
- Create another S3 bucket in a different Region
- Replicate data from DynamoDB to Amazon RDS for redundancy


#### A solutions architect is redesigning a monolithic application architecture to make the application more cloud-native to improve performance. Which migration strategy is the solution architect using?

- Retain
> - Refactor
- Relocate
- Repurchase


#### Which load balancer should be used for load balancing HTTP and HTTPS traffic?

> - Application Load Balancer
- Round Robin
- Gateway Load Balancer
- Network Load Balancer


#### Which component in the Shared Responsibility Model is the customer responsible for?

- Availability Zones
- Compute
- Regions
> - Operating systems, network, and firewall configuration


#### Which AWS Lambda concept is a resource that can be invoked to run code in Lambda?

> - Function
- Event
- Deployment package
- Trigger


#### A developer must install an HTTP server to run their application. Which compute service is appropriate for the developer in this scenario?

> - Amazon EC2
- Amazon RDS
- Amazon DynamoDB
- AWS Lambda


#### Which compute options are available on AWS? (Select THREE.)

> - Serverless
- Amazon Elastic Block Store (Amazon EBS)
> - Container services
- Amazon Relational Database Service (Amazon RDS)
- Amazon Simple Storage Service (Amazon S3)
> - Virtual machines (Amazon EC2 instances)


#### A developer wants to automatically initiate actions based on sustained state changes of their resource metrics. Which Amazon CloudWatch concept should the developer choose?

- Custom metrics
- CloudWatch dashboards
- CloudWatch logs
> - CloudWatch alarms


#### Which of the following are default metric categories for an Amazon EC2 instance? (Select TWO.)

- Disk space consumption
- Number of objects store in a bucket
> - Network utilization
- Database connections
> - CPU utilization


#### A solutions architect for a digital media and entertainment company is building an architecture for their company’s hybrid cloud deployment. They need standardized access using file system protocols, such as a Network File System (NFS) or Server Message Block (SMB). Which storage type is appropriate in this scenario?

- Amazon Relational Database Service (Amazon RDS)
- Block storage
> - File storage
- Object storage


#### A database administrator is using a database hosted in Amazon RDS. Which task is the responsibility of the database administrator?

- Operating system installation
- High availability
- Database backups
> - Database tuning and query optimization


#### What are the benefits to having well-architected application workloads? (Select THREE.)

- Reduce your on-premises infrastructure footprint  ❌
- Increase time spent maintaining infrastructure  ❌
> - Decrease unplanned downtime of application workloads
- Improve communication with customers  ❌
> - Improve application performance efficiency
> - Reduce infrastructure spend


#### A solutions architect must quickly migrate and scale to satisfy a business capacity need. Which migration strategy should the solutions architect choose?

- Repurchase
- Refactor
- Retire
> - Rehost


#### Which container use cases are on AWS Fargate? (Select THREE.)

> - Batch processing
> - Microservice architecture applications
- Cluster capacity management
- Patching servers
> - Migrating on-premises applications to the cloud
- Managing Amazon Elastic Cloud (Amazon EC2) instances


#### When does an Amazon Elastic Compute Cloud (Amazon EC2) instance stop incurring charges?

- When the instance is running
> - When the status of an instance changes to shutting down or terminated
- When the instance is rebooted
- When an instance with an attached Amazon Elastic Block Store (Amazon EBS) volume enters the stopped state


#### Which option means a collection of attributes in Amazon DynamoDB?

- Table
- AWS Key Management Service (AWS KMS)
> - Item
- Attributes


#### Which pillar of the AWS Well-Architected Framework focuses on improving application performance efficiency?

- Operational excellence
- Reliability
- Cost optimization
> - Performance efficiency


#### Which AWS framework can help a customer achieve cloud readiness for a successful migration to AWS?

> - AWS Cloud Adoption Framework 
- AWS CAF Envision Workshop
- AWS Cloud Journey Framework
- AWS Cloud Economics Framework


#### Which storage option is preferred for an application that is transactional and I/O-intensive?

- Object Storage
- File Storage
> - Block Storage
- Amazon S3


#### What is a set-and-forget file system that automatically grows and shrinks as files are added and removed?

- Amazon RDS
> - Amazon Elastic File System (Amazon EFS)
- Amazon Elastic Block Store (Amazon EBS)
- Amazon S3
