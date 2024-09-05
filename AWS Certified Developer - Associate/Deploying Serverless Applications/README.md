#### A team of developers created a serverless, distributed application on AWS. For custom business logic and application code, they're using AWS Lambda. They're using Amazon API Gateway in front of their Lambda endpoints and using Amazon S3 as the storage system for their data. The team wants to deploy a new version of their application but needs the ability to roll back automatically if a resource isn't properly built out. How can the team best meet this requirement? Select the correct answer and choose SUBMIT.

- Use an AWS CloudFormation template and syntax to define the latest version of the application.
- Create a new version of the AWS Lambda application and point an alias to the new version using the Lambda API.
> - Use the AWS Serverless Application Model (AWS SAM) to define the latest version of the application.
- Use the AWS CLI to create a script to deploy the new version of the resources.


#### A development team has just finished migrating a stable application to AWS Lambda. They're now looking to release a patch version of their application in a safe and gradual manner. The team is planning on sending 10 percent of traffic to the patch version for 30 minutes before directing all of the traffic to the new function. Which of the following strategies could the team use to test out their new feature? (Select TWO.)

> - Use the AWS Serverless Application Model (AWS SAM) to configure a Canary10Percent30Minutes deployment preference.
- Use Amazon API Gateway to deploy a new stage named version2 to the API.
> - Activate traffic shifting for an alias using the Lambda API.
- Create a second Amazon API Gateway resource and integrate the $LATEST version of the Lambda function.
- Use AWS CloudFormation to configure a Linear10Percent30Minutes deployment preference.


#### When you create a Lambda function, there is only one version called what?

> - $LATEST
- Alias
- Main function
- Template


#### Which of these deployment strategies has immediate deployment speed?

- Canary
- Linear
- Blue/Green
> - All-at-once
