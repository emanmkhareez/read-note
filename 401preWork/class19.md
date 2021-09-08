Review, Research, and Discussion

Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server?
By using Express server, you connect and send HTTP requests to specific endpoints and connect them with handler functions on the same server.
By using AWS, you can separate the routing process and the function handler, where you send the HTTP request using AWS API Gateway and integrate them with Lambda functions as they will be triggered when a specific route is reached.
List the AWS Database offerings and talk about the pros and cons of each?
Key-value: High-traffic web apps, e-commerce systems, gaming applications
In-memory caching, session management, gaming leaderboards, geospatial applications
Relational: Traditional applications, ERP, CRM, e-commerce
Document Content management, catalogs, user profiles
Wide column High scale industrial apps for equipment maintenance, fleet management, and route optimization
Time series IoT applications, DevOps, industrial telemetry
What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.
How can the server be assured a message was properly received?
Logging and using timestamps and checking whether it was delivered based on the response sent from the endpoint.
Document the following Vocabulary Terms
Serverless API: A serverless API is based on a cloud service that allows for the creation of API endpoints with specific http request methods such as POST and GET. This allows a coder to create a website without needing a server to host their code.
Triggers: an AWS Lambda resource or resource in another service that you configure to invoke your function in response to lifecycle events, external requests or on a schedule, a function can have multiple triggers.
Dynamo vs Mongo: They are booth No-SQL database and both of them have a package that will help us in connecting to the DB and manipulating the data (Mangoose and Dynamoose).
Dynamoose vs Mongoose: Dynamoose is a modeling tool for Amazon’s DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familar.
Preparation Materials
SQS and SNS Basics
SNS is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS. SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll or pull messages from SQS.

SNS is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS. SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll or pull messages from SQS. Messages can't be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later. Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers. SNS supports several end points such as email, SMS, HTTP end point and SQS. If you want unknown number and type of subscribers to receive messages, you need SNS. You don't have to couple SNS and SQS always. You can have SNS send messages to email, SMS or HTTP end point apart from SQS. There are advantages to coupling SNS with SQS. You may not want an external service to make connections to your hosts (a firewall may block all incoming connections to your host from outside).