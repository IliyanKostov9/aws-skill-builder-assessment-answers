#### Which of the following are true of DynamoDB tables? (Select THREE.)

- All items must adhere to a fixed schema definition.
> - All items must have a partition key. The unique primary key includes a partition key and optional sort key.
- Item size is unlimited
> - Read and write capacity are managed independently.
> - Tables can scale to any data volume.


#### Which of the following workload characteristics might be a good fit for DynamoDB? (Select THREE)

> - The data is "hot" — serving real-time, transactional, operational, interactive uses.
- The data is historical, infrequently accessed for complex ad-hoc analytical queries that can be requested as a job and delivered minutes or hours later as a report.
- The data is a collection of very large binary objects which are written only once but often read by direct reference.
> - The data must be stored in a highly available, durable, and highly scalable manner
> - The session states for your application need to be stored off of your instances


#### One basic factor for success with DynamoDB is: (Select ONE.)

- Selecting optimal node size and availability zones for your tables
- Default to creation of strongly consistent tables to avoid corruption.
- Choosing a high cardinality sort key and localizing the index.
- Remembering to regularly adjust the shard algorithm for each item type.
> - Choosing a high cardinality partition key for even item and request distribution.


#### Which statements about consistency are true? 

- DynamoDB Accelerator (DAX) passes strongly consistent reads through but does not cache them.
- Strongly consistent reads can be made via a VPC Endpoint.
- Local and Global Secondary Indexes both support eventually consistent reads.
- You can make two eventually consistent reads (each up to 4KB) for one RCU.
- All successful writes are redundantly stored and durable - there is no eventual or strong consistency choice to be made for writes.
> - All of the above
- None of the above


#### Local secondary indexes can only be defined at the time of base table creation – they cannot be deleted without deleting the base table. True or false?

> - True
- False

#### Time-To-Live (TTL) can be used to have DynamoDB delete expired items from a table without being charged for WCU consumption. When you set an attribute for use by TTL, what is the value you should set for that attribute to result in expiry?

- The number of seconds since last update for the item to remain in the table.
> - The epoch timestamp (with unit seconds) after which the NN RTINS
- The number of days since last update for the item to remain in the table.
- A string pattern which needs to match the TTL expression for expiry.
- A Boolean specifying true or false for expiration.


#### Which of the following statements about DynamoDB streams is false?
- DynamoDB Streams is compatible by default with the Kinesis Client Library.
> - DynamoDB Streams can be used to audit read activity for a table.
- DynamoDB Streams is essentially a change log of updates to the table.
- Entries in a DynamoDB Streams are strictly ordered for a given primary key.
- DynamoDB Stream events can be used as a trigger for processing via Lambda.


#### Optimistic concurrency control in DynamoDB provides a form of locking. Which is the correct description of the mechanism?

> - Read, transform, conditionally write, retry as required.
- Strongly consistent write with lock option set true.
- Enable streams, check the stream to confirm no other updates are in progress, Deleteltem, Putltem.
- Putltem/Updateltem, then strongly consistent Getlten to confirm that your change has not been overwritten.
- Conditional Write, retry, transform, read, retry.


#### Which of the following is a commonly recommended serverless pattern for aging out DynamoDB data to a cold storage tier?
- DynamoDB conditional read from EC2 and subsequent transactional write to EBS.
- EMR job reads from DynamoDB and writes to local HSFS volumes.
- Monthly Scan of the entire table from an EC2 instance, with Deleteltem to remove old items, and subsequent storage to objects in S3.
- Roll the DynamoDB tables daily - older tables have their tier specified as Glacier.
> - Enable DynamoDB streams and use TTL to expire older items. A Lambda function is triggered on the change and writes the deleted item data into S3 via Kinesis Firehose.


#### Which of the following are parameters to DynamoDB Auto Scaling? (Select all that apply)

> - Minimum capacity.
- Average capacity.
> - Maximum capacity.
> - Target utilization.
- Node pre-warm time.
- All of the above
- None of the above
