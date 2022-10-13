# AWS Events

## AWS SQS vs SNS
1. What is the difference betweeen SQS and SNS?
- SNS is a distributed publish-subscribe service
- SQS is a distributed queueing service

2. What are some use cases for both SNS and SQS?
- SNS is a good way to send push notifications to Apple, Google, Fire OS, and Windows, good for sending out a notification to a large number of subscribers
- SQS is good when you need to persist the messages and have users get them at a later time, only one subscriber is necessary

## AWS SNS and SQS
1. Describe how to use SQS and SNS in a “fanout” pattern.

2. Explain how “push notifications” work, using SNS.

## SQS and SNS Basics
1. How might a large scale, distributed application make use of a Queue system like SQS?

## Things I want to learn more about

### Links
[AWS — Difference between SQS and SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

[SNS vs SQS Comparison](https://www.youtube.com/watch?v=mXk0MNjlO7A)

[Decouple and Scale Applications Using Amazon SQS and Amazon SNS](https://www.youtube.com/watch?v=UesxWuZMZqI)

[AWS.SNS](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[AWS.SQS](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)