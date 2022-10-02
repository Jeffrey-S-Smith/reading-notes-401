Readings: AWS: API, Dynamo and Lambda
=====================================

Reading
-------

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

1. What is Amazon API Gateway?
    is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
    API Gateway allows you to implement a fully managed authentication and authorization layer by using Amazon Cognito and Lambda custom authorizers without running your own auth systems. By using API Gateway you also get access to the developer portals that are generated automatically from your API schemas.

3. How does API Gateway integrate with other AWS services?
    You can integrate many AWS services with API Gateway, but the setup and mapping vary depending on the particular service API. To integrate another service with API Gateway, build an HTTPS request from API Gateway to the service API so that all request parameters are correctly mapped.

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

1. What are the some benefits of using Amazon API Gateway?
  
  * Efficient API development. Run multiple versions of the same API simultaneously with API Gateway, allowing you to quickly iterate, test, and release new versions. ...
  * Performance at any scale. ...
  * Cost savings at scale.

2. What two API types might you choose from?
    Internal APIs, which only internal teams may access. Composite APIs, which combine multiple APIs.

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

1. What is DynamoDB?
    Experience the Ease, Security & Reliability of Building a DynamoDB Database With AWS. Deploy Multiple Database Editions With Cost-Efficient & Resizable Hardware Capacity. Highly Scalable.

2. Under what circumstances would you recommend DynamoDB over MongoDB?
    DynamoDB will allow a maximum of just 400 KB, while MongoDB has a limit of 16 MB. If you need to store big objects with DynamoDB, AWS recommends using another service, such as S3. Bear in mind that while this solution can work, it does so at the cost of reduced performance.

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

1. Explain to a non-technical friend how DynamoDB works.
    Upon entry, data is first distributed into different partitions by hashing on the partition key. Each partition can store up to 10GB of data and handle by default 1,000 write capacity units (WCU) and 3,000 read capacity units (RCU).

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

1. What is Dynamoose?
   Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar. 

2. What are some key features of Dynamoose?
   * Type safety.
   *  High level API.
   * Easy to use syntax.
   *  DynamoDB Single Table Design Support.
   * Ability to transform data before saving or retrieving items.
   * Strict data modeling (validation, required attributes, and more)
   * Support for DynamoDB Transactions.
   * Powerful Conditional/Filtering Support. 

## Things I want to know more about