# AWS: API, Dynamo, and Lambda

## AWS API Gateway Overview
1. What is Amazon API Gateway?
- service that allows developers to define http endpoints of a REST or WebSocket API and connect the backend logic to them
- handles authentication, access control, monitoring, and tracing of requests

2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
- ties together serverless functions and API definitions
- lambda functions can be triggered by HTTP requests

3. How does API Gateway integrate with other AWS services?
- lambda - run lambda functions to generate HTTP API responses
- AWS SNS - publish SNS notifications when HTTP API is accessed
- Amazon Cognito - provide authentication/authorization for HTTP requests

## AWS API Gateway
1. What are the some benefits of using Amazon API Gateway?
- Efficient api development
- cost savings at scale
- easy monitoring
- RESTful API options

2. What two API types might you choose from?
- RESTful APIs
- WebSocket APIs

## AWS DynamoDB Guide
1. What is DynamoDB?
- hosted NoSQL database offered by AWS

2. Under what circumstances would you recommend DynamoDB over MongoDB?
- applications with large amounts of data and strict latency
- Serverless applications using AWS Lambda
- Data sets with simple, known access patterns

## Dynamoose
1. What is Dynamoose?
- modeling tool for Amazon's DynamoDB, similar to Mongoose

2. What are some key features of Dynamoose?
- Type Safety
- High Level API
- Easy to use Syntax


### Things I want to learn more about

### Links
[AWS API Gateway Overview](https://www.serverless.com/guides/amazon-api-gateway)

[Amazon API Gateway](https://aws.amazon.com/api-gateway/)

[What is DynamoDB?](https://www.dynamodbguide.com/what-is-dynamo-db/)

[Amazon DynamoDB](https://aws.amazon.com/dynamodb/)

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)
