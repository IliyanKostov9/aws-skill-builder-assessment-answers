#### Which of the following are true about Amazon Simple Queue Service (Amazon SQS) and AWS Lambda? (Select TWO.) Select the correct answers and choose SUBMIT. For keyboard only accessibility, press TAB to navigate to the correct answer, and press SPACEBAR to select. Repeat the step until all correct responses are checked, then press ENTER to submit.

- A best practice is to set the visibility timeout to 3 times the timeout you configure for your Lambda function.
> - If a Lambda function returns errors when processing messages, Lambda decreases the number of processes polling the queue.
> - Lambda has a default of five parallel processes to get things off of a queue.
- If there is an increase in queue size, Lambda decreases the concurrency required to reduce cost.
- If the visibility timeout expires before the Lambda function processes the messages, messages will be deleted by the queue.


#### A company owns an ecommerce website that sells dog pajamas. Whenever an order is placed for a product, the company wants to send an email alert to the customer and at the same time process the order and update the inventory database. After a popular talk show host talked about the website, the company is having issues processing orders as they come in. The company often creates duplicate orders for their customers. Which of the following architectures would meet the company's requirements and create a better customer experience? Select the correct answer and choose SUBMIT. For keyboard only accessibility, press TAB to navigate to the correct answer, press SPACEBAR to select, and press ENTER to submit. 

- Use the claim check pattern. Add the order into an Amazon S3 bucket and create a presigned URL. Use an AWS Lambda function to send a message with that URL to a standard Amazon Simple Queue Service (Amazon SQS) queue. Use Lambda to poll the queue, filter the message, send an email to the customer, and update the database.
- Use the claim check pattern. Add the order into an Amazon S3 bucket and create a presigned URL. Use an AWS Lambda function to send a message with that URL to a First-In-First-Out (FIFO) Amazon Simple Queue Service (Amazon SQS) queue. Use Lambda to poll the queue, filter the message, send an email to the customer, and update the database.
- Use the Amazon Simple Notification Service (Amazon SNS) fan-out pattern. When the order is placed, send a message to the SNS topic, with customer email addresses and a standard Amazon Simple Queue Service (Amazon SQS) queue as the subscribers. Use AWS Lambda to poll the queue, filter the message, and update the database.
> - Use the Amazon Simple Notification Service (Amazon SNS) fan-out pattern. When the order is placed, send a message to the SNS topic, with customer email addresses and a First-In-First-Out (FIFO) Amazon Simple Queue Service (Amazon SQS) queue as the subscribers. Use AWS Lambda to poll the queue, filter the message, and update the database.


#### A team of developers noticed that one of their AWS Lambda functions keeps failing. One of the team members wonders why the service did not retry the request. Which of the following could explain why the function was not retried? Select the correct answer and choose SUBMIT. For keyboard only accessibility, press TAB to navigate to the correct answer, press SPACEBAR to select, and press ENTER to submit. 

- The team is using an asynchronous event source to invoke their function, which has no built-in retries for a failed or throttled request.
- The team is invoking their function to poll an Amazon Simple Queue Service (Amazon SQS) queue, which has no built-in retries for a failed or throttled request.
> - The team is using a synchronous event source to invoke their function, which has no built-in retries for a failed or throttled request.
- The team is using a streaming service, like Amazon Kinesis Data Streams, to invoke the function, which has no built-in retries for a failed or throttled request.


#### Which of these patterns for communicating status updates do you use to get status information on a long-running transaction? Select the correct answer and choose SUBMIT. For keyboard only accessibility, press TAB to navigate to the correct answer, press SPACEBAR to select, and press ENTER to submit. 

- WebSockets with AWS AppSync
> - Client polling pattern
- Saga pattern with AWS Step Functions
- Webhooks with Amazon Simple Notification Service (Amazon SNS)


#### Which of the following are attributes of using streaming services for serverless data processing? (Select TWO.) Select the correct answers and choose SUBMIT. For keyboard only accessibility, press TAB to navigate to the correct answer, and press SPACEBAR to select. Repeat the step until all correct responses are checked, then press ENTER to submit.

- With streaming services, data is deleted when it has been consumed.
> - The data on the stream remains in the stream for a designated period of time and then is gone, regardless of consumer behavior.
> - Each stream consumer needs to maintain a pointer to a particular position in the stream. After consuming the message, the consumer moves the pointer forward to the next record and processes it.
- With streaming services, you can configure retries up to a certain number of attempts, and dead-letter queues are built in to the service.
- With streaming services, the core entity is an individual message.
