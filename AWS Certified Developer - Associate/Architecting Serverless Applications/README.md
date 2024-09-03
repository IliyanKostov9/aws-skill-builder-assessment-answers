#### A team of developers has an application that currently runs off Docker. You recently read about serverless technologies, which aim to remove infrastructure management burden. When you bring this up with your team, they retort that the application "just can't do serverless." The team states that they don't want to have to rewrite the application and don't think that their long-running tasks are suitable for serverless. Which service provides the least infrastructure management burden on the developers but still meets the team's requirements?

- AWS Lambda
- Amazon Elastic Kubernetes Service (Amazon EKS)
> - AWS Fargate
- Amazon EC2


#### Match each AWS data store on the left to its corresponding use case on the right. Move the left column toward the right to match the items.

DynamoDB = Store player game state for 300 million users while maintaining millisecond access
QLDB = Track the history of credits and debits in banking transactions in an organization
ElastiCache for Redis = A sorted leaderboard of top values requiring sub-millisecond read and write latencies
RDS = A relational data store to back a CMS that reduces operational overhead
S3 = Ideal for data lakes, due to its high scalability and flexibility


#### Which of these migrations patterns helps an organization incrementally and systematically decomposes monolithic applications by creating APIs and building event-driven components that gradually replace components of the legacy application?

- Leapfrog
> - Strangler
- Organic
- Saga


#### Which of these are best practices for serverless applications? (Select THREE.)

> - Don’t reinvent the wheel.
- Assume the limits of all of the services involved will scale to your needs.
- Send events to services outside AWS as soon as possible.
> - Prefer idempotent, stateless functions.
- Port your code for easy serverless integration
> - Stay current


