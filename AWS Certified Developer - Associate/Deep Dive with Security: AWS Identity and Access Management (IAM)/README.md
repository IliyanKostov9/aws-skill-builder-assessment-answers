#### A solutions architect is designing a shared service for hosting containers from several customers on Amazon Elastic Container Service (Amazon ECS). These containers will use several AWS services. A container from one customer should not be able to access data from another customer. Which of the below solutions should the architect use to meet these requirements?

> - AWS IAM roles for Amazon ECS tasks
- AWS IAM roles for Amazon EC2 instances
- AWS IAM instance profile for Amazon EC2 instances
- AWS IAM security group roles


#### A solutions architect is deploying an application on Amazon EC2, which must call AWS APIs. What method should they use to securely pass credentials to the application?

- Pass API credentials to the instance using instance user data.
- Store API credentials as an object in an Amazon S3 bucket.
- Embed the API credentials into the application.
> - Assign an IAM role to the EC2 instance.


#### Which of the following is NOT a feature of AWS Security Token Service?

- AWS STS enables users to request temporary limited-privilege credentials.
- AWS STS enables users to assume a role.
> - AWS STS enables users to request Git credentials.
- AWS STS generates federated credentials for IAM users.


#### A security engineer wants to enable federated access from a corporate IdP to an AWS account using AWS IAM and AWS STS. Which API call is required?

> - AssumeRoleWithSAML
- GetFederationToken
- AssumeRoleWithWebIdentity
- GetCallerIdentity


#### A solutions architect has written an AWS Lambda function that writes customer data to an Amazon DynamoDB table. Which of the following must be in place to ensure that the Lambda function can interact with the DynamoDB table?

> - An IAM role is attached to the Lambda function with the required DynamoDB privileges.
- An IAM user is attached to the Lambda function that has the required DynamoDB privileges.
- Access keys are embedded in the AWS Lambda function.
- The IAM user password is embedded in the AWS Lambda function.


#### A company is building a new application and is hosting their development, test, and production applications on Amazon EC2 instances. Administrators for each of the environments will need access to their environment but not to the other environments. What best practice would you suggest to give the administrators the access they need?

> - Add tags to the instances and IAM policies to mark each environment. 
- Add user data to the underlying instances to mark each environment.
- Add metadata to the underlying instances to mark each environment.
- Add each environment to a separate Auto Scaling group.


#### An architect is developing a mobile application and wants to issue temporary security credentials to users of the application. Which is the best service to achieve this?

> - AWS STS
- Amazon Cognito
- AWS SSO
- AWS IAM


#### Which of the following gives you granular control over when your JSON policy statements match or don’t match an incoming request?

> - Global condition keys
- Service policies
- Session tags
- NotAction tags


#### A security engineer is approached by a solutions architect after an EC2 instance was shut down unexpectedly, compromising the workload. Which AWS service is used to investigate who shut down the workload?

> - AWS CloudTrail
- Amazon CloudWatch
- AWS Config
- AWS Systems Manager


#### A security engineer is responding to an Amazon DynamoDB table that has been deleted. They are trying to understand what level of access users have and where users may have too much access. What IAM tool will help them troubleshoot policies?

> - AWS IAM Policy Simulator
- AWS IAM Access Analyzer
- AWS IAM Policy Analyzer
- AWS IAM documentation
