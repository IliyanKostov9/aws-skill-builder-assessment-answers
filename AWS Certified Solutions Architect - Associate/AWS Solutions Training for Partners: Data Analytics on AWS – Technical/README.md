#### Which AWS tool is the most useful for converting schema from a legacy data warehouse, like Netezza, to migrate data to Amazon Redshift?

- AWS Data Migration Service (AWS DMS)
- Amazon Redshift UPLOAD command to load Netezza data
> - AWS Schema Conversion Tool
- No tool necessary – write the data from Netezza to Amazon S3 and load it into Amazon Redshift using the COPY command


#### Which option shows the top four most common challenges faced by data analytics customers according to the Business Application Research Center's Business Intelligence Survey? 

    Inadequate analytical know-how
    Fast evolving technologies
    Inadequate technical know-how
    Data security

    Inadequate analytical know-how
    Data privacy issues
    Inadequate technical know-how
    Financial inadequacies 

    Too much data 
    Data privacy issues
    Unwillingness of employees to learn
    Data security

>    Inadequate analytical know-how
    Data privacy issues
    Inadequate technical know-how
    Data security


#### Which option lists the four stages of the data analytics pipeline in the correct order?

    Collect
    Process and analyze
    Store
    Visualize

>   Collect
    Store
    Process and analyze
    Visualize

    Collect
    Store
    Visualize
    Process and analyze

    Store
    Collect
    Process and analyze
    Visualize


#### Which option identifies two services that allow customers to build a secure data lake in days instead of months?

- AWS CloudFormation and AWS Glue
- AWS CloudFormation and a de-identified data lake (DIDL)
- Amazon Redshift and AWS Glue
> - AWS Lake Formation and a de-identified data lake (DIDL)


#### Which option accurately describes Amazon Redshift lake house architecture? 

- With Amazon Redshift lake house architecture, customers can only query data in Amazon Redshift and an Amazon data lake
> - With Amazon Redshift lake house (Spectrum) architecture, customers can efficiently query data in Amazon RDS, Amazon Redshift, and an Amazon data lake. They can also write the data back to the data lake using open source formats like Parquet or ORC.
- Amazon Redshift lake house is a new name for Amazon Redshift queries.
- With Amazon Redshift lake house architecture, customers can only query data in Amazon RDS.


#### What are the recommended instance types for Amazon Redshift? (Select TWO.)

> - Dense Compute – DC2
- Compute Optimized – C4
- Dense Storage – DS2
- Graphical Compute – GPU2
> - Amazon Redshift Analytics – RA3


#### Which principles are included in the 10 general design principles outlined in the AWS Well-Architected Analytics Lens whitepaper? (Select TWO.)

> - Describe data with metadata, so you can find the data later and avoid "dark data."
- Once you process the original data, you should delete it to save disk space and money.
- Avoid sharing original source data with anyone
> - Preserve the original data source, so you can process the original data for different purposes in the future.
- Avoid using metadata, so AWS Glue can discover all data easily.


#### What are the first two recommended calls to action for an APN Partner to complete in the weeks following the completion of this course? (Select TWO.)

- Call all of their customers and share the entire AWS Data Analytics portfolio.
- Complete the AWS Data Analytics Specialty Certification exam as quickly as possible before reaching out to customers.
- Focus 100% of their time on building a prepackaged solution to sell directly to their customers.
> - Work with their AWS PDR and PDM to plan and schedule a Data Analytics Immersion Day for their customers.
> - Call their customers and offer them the data lake assessment service.


#### A Partner's customer needs an inexpensive way to move 70 terabytes of data within 2 weeks from their on-premises data center to the AWS Cloud. They do not currently have high speed internet. Which AWS data migration option is the right solution for this customer?

- Amazon S3 Transfer Acceleration
- AWS Storage Gateway
> - AWS Snowball
- AWS Direct Connect


#### Which option accurately describes the difference between Federated Query and Amazon Redshift standard query?

- With Federated Query, customers can a query for data only in Amazon RDS and Amazon Redshift.
> - With Federated Query, customers can seamlessly query for data in Amazon RDS,  Amazon Redshift, and Amazon Data Lake from Amazon Redshift 
- With Federated Query, customers can a query for data in Amazon RDS and Amazon Data Lake from Amazon Redshift.
- With Amazon Redshift standard query, customers can efficiently query data in a data lake and Amazon Redshift tables.


#### What are two potential financial benefits for APN Partners from hosting AWS Data Analytics Immersion Days? (Select TWO.)

- SPIFF money for opportunities registered
> - Partners can access AWS Market Development Funds (MDF) to offset their marketing expenses.
> - Partners get access to AWS credits to develop new solutions or try new AWS products for their customers.
- Lottery winnings
- Partners can profit from customer registrations for AWS Immersion Days.
- Partners are guaranteed many new customers right away.


#### Which options correctly describe the key tasks completed by compute nodes in an Amazon Redshift cluster? (Select TWO.)

> - Compute nodes are responsible for returning the intermediate query results back to the leader node after query completion.
- Compute nodes are only responsible for running queries and nothing else.
- Compute nodes do not run queries, but they are responsible for returning intermediate query results back to the leader node. 
> - Compute nodes are responsible for data manipulation and running of query tasks assigned to them by the leader node.
- Compute nodes interface directly to the client to receive query tasks assignments.


#### Which options correctly describe the key tasks completed by a leader node in an Amazon Redshift cluster? (Select TWO.)

- A leader node sends query requests to the client to be broken down into smaller requests to be pre-processed by the compute nodes.
- A leader node is only responsible for communicating to the client by way of JDBC or ODBC and nothing else.
- A leader node receives query requests from a client, pre-processes them, breaks the query into smaller tasks, and runs them in parallel. 
> - A leader node receives query requests from a client, pre-processes them, breaks the query into smaller tasks, and distributes the tasks to compute nodes for parallel completion.
> - A leader node collects intermediate results returned from the compute nodes, processes and assembles them, and then returns the aggregated query results to the client. 


#### Which actions help an APN Partner build a successful data analytics practice on AWS, as described in the course? (Select THREE.)

- Avoid AWS APN Partner training programs until Partner opportunities are secured
- Keep data analytics customer opportunities private until training is completed
- Avoid collaboration with APN service teams
> - Achieve AWS  Data Analytics Competency certification
> - Develop customer workshops
> - Engage the APN service team


#### Based on the Data Flywheel, which options are the next two steps after a customer has moved most of their on-premises data to Amazon S3? (Select TWO.)

> - Start innovating with machine learning to gain insights
- Move more data to the AWS Cloud
- Nothing. The data analytics journey to the cloud is complete
> - Start building data-driven applications


#### What are the top performance features of Amazon Redshift? (Select TWO.)

- Super fast in-memory transaction query that speeds up queries by 45%
> - Columnar storage that improves data compression and query performance
- Massively fast disk read/write
> - Massively parallel processing (MPP) for faster processing time


#### Traditional architectures and on-premises data warehousing pose many challenges for customers. Which options describe some of these challenges discussed in this course? (Select THREE).

> - Cannot scale easily and quickly
- Malware issues
> - Have expensive licensing and support costs
- Environmental issues
- Job security concerns
> - Require complex upgrades


#### Which  Amazon Kinesis service can ingest streaming data and write it to Amazon S3 or Amazon Redshift?

- Amazon Kinesis Video Streams
> - Amazon Kinesis Data Firehose
- Amazon Kinesis Data Streams
- Amazon Kinesis Data Analytics


#### Which service empowers developers and data scientists with the ability to build, train, and deploy machine learning models quickly?

- Amazon Macie
> - Amazon SageMaker
- Amazon Elastic Interface
- Amazon CodeGuru


#### Which option correctly lists the three steps APN Partners follow for a successful proof of concept (POC) outcome?

    Identify vague end goals
    Identify how success will be measured
    Lead developer sponsorship of the POC from the customer side

    Identify vague end goals, if any
    No specific markers for measuring success; leave this open for change
    C-level sponsorship of the POC from the customer side

    Identify the end goal
    Identify how success will be measured
    Lead developer sponsorship of the POC from the customer side

>   Identify the end goal
    Identify how success will be measured
    C-level sponsorship of the POC from the customer side
