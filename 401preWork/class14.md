Event Driven Architecture
 (Links to an external site.)Review, Research, and Discussion
What’s the difference between a FIFO and a standard queue?

Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.
How can the server be assured a message was properly received?


The messages sent by the client, usually a Web browser, are called requests ... Each individual request is sent to a server.
What classic design pattern is best represented by event driven programming?

The Observer pattern.
How do you test an event driven system?

By checking the message queue.
 (Links to an external site.)Document the following Vocabulary Terms
FIFO Queue: is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives.
Pub/Sub: Pub/Sub allows services to communicate asynchronously, with latencies on the order of 100 milliseconds, is used for streaming analytics and data integration pipelines to ingest and distribute data. It is equally effective as messaging-oriented middleware for service integration or as a queue to parallelize tasks.
 (Links to an external site.)Preview
Which 3 things had you heard about previously and now have better clarity on?
Nothing.
Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Observer pattern
Pub/Sub
What are you most excited about trying to implement or see how it works?
Pub/Sub
 (Links to an external site.)Preparation Materials
QS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll or pull messages from SQS. Messages can't be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later. Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers. SNS supports several end points such as email, SMS, HTTP end point and SQS. If you want unknown number and type of subscribers to receive messages, you need SNS.