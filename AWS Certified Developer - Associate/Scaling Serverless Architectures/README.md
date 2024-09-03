#### Your AWS Lambda function is not processing Amazon Kinesis Data Streams records in a timely manner, and the IteratorAge metric is increasing on your Lambda dashboard. What is the best strategy for addressing this?

- Set up a dead-letter queue to manage processing failures.
> - Reshard to increase the number of shards in your stream.
- Batch incoming messages together to increase performance.
- Increase the retention period for records in your stream.
- Review the CloudWatch metrics dashboard and use AWS X-Ray to identify the bottleneck.


#### What are some scaling best practices? (Select TWO.)

- Keep the application and database combined.
> - Take advantage of the AWS Global Infrastructure.
- Identify and create the need for heavy lifting.
> - Monitor for percentile
- Refactor at the beginning to avoid the need to refactor later


#### What are some considerations for scaling AWS Lambda functions? (Select THREE.)

> - Burst behavior
- Infrastructure maintenance
> - Memory configuration
> - Concurrency limits
- Code reusability
- Configuring auto scaling


#### Which statements reflect recommended approaches for scaling databases? (Select TWO.)

- Amazon DynamoDB on-demand mode is a good fit if you have a very consistent, predictable workload.
> - Amazon DynamoDB on-demand mode is a good fit if you need to track the cost of individual transactions.
> - Provisioned capacity might be the better choice if you have a very consistent, predictable workload.
- Amazon DynamoDB Accelerator (DAX) is a useful solution for offloading transactions that can withstand a higher latency.
- The best option for connecting to traditional relational databases is to use concurrency limits to limit the number of concurrent database connections that AWS Lambda can invoke.


#### A company is designing an AWS Step Functions workflow, made up of a series of AWS Lambda functions and an Amazon DynamoDB table. The application seems to have a very consistent, predictable workload, and the cost is high. You have been hired to analyze the application architecture and to give cost-saving recommendations. Which options might lower the cost of the architecture? (Select THREE.)

> - Use wait states and callbacks in Step Functions.
- Use DynamoDB auto scaling with on-demand capacity.
> - Use AWS Lambda Power Tuning.
> - Use provisioned capacity for DynamoDB.
- Use a relational database instead to lower costs.
- Use Amazon EC2 rightsizing for DynamoDB.
