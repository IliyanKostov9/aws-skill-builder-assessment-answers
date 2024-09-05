#### Which groups does Amazon S3 grant permissions to its members to consider a bucket or an object public? (Select TWO.)

- All-Identity
> - AuthenticatedUsers
> - AllUsers
- AllPrincipals
- Everyone


#### Which image represents a bucket policy?
Policy one shows an IAM policy that has the Action, Effect, and resource elements. Policy 2 shows the Action, Effect, Resource, and principal element.

- Policy 1
> - Policy 2
- Neither of these is a bucket policy.


#### What does the condition element represent?

> - Specifies conditions for when a policy is in effect. The Condition element is optional.
- Specifies conditions for when a policy is in effect. The Condition element is required.
- Specifies the resource that the policy is applied to.
- Specifies whether you allow or deny the condition.


#### What does the Amazon S3 Object Ownership feature allow?

- The account that uploads an object to a bucket owns the object.
> - The account that owns the bucket owns the uploaded objects.
- Objects are owned by all users of a bucket.
- Objects do not have ownership in Amazon S3.


#### What is an appropriate use case for presigned URLs? (Select TWO.)

> - Embed a presigned URL on your website to download objects.
> - Use it in a command line client (such as curl) to download objects. 
- Use it as a permanent link on a static website.
- Send it in an email containing personally identifiable information.
- Use it with permanent user credentials.


#### When accessing an encrypted presigned URL, what special step do you need to follow?

> - Nothing. Presigned URLs work the same with encrypted or unecrypted objects.
- Attach the AWS KMS key.
- Configure the bucket to unencrypt the URL before returning the object to the requestor.
- If it's unencrypted,  encrypt it for security and then send it to the requestor.


#### Which server-side encryption methods does Amazon S3 support? (Select THREE.)

> - SSE-S3
> - SSE-KMS
> - SSE-C
- SSE-clientside
- SSE-sigv4
- SSE-TLS


#### Which AWS services do gateway endpoints support? (Select TWO.)

> - Amazon S3
> - Amazon DynamoDB
- AWS Lambda
- Amazon Elastic Compute Cloud (Amazon EC2)
- AWS Fargate


#### Which endpoint service uses only endpoint policies to secure the endpoint?

> - Gateway endpoints
- Interface endpoints
- Access endpoints
- Direct Connect endpoints
- Security group endpoints


#### When using an endpoint policy to control access to an Amazon S3 bucket, what should the S3 bucket policy specify?

> - The bucket policy should only accept connections from the appropriate access point.
- The bucket policy should be identical to the endpoint policy.
- The bucket policy should specify only the administrator who manages the bucket permissions.
- No bucket policy should be on the bucket.


