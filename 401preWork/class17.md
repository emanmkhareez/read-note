 AWS: S3 and Lambda ===

You can use Lambda to process event notifications from Amazon Simple Storage Service. Amazon S3 can send an event to a Lambda function when an object is created or deleted. You configure notification settings on a bucket, and grant Amazon S3 permission to invoke a function on the function’s resource-based permissions policy.

Amazon S3 invokes your function asynchronously with an event that contains details about the object. The following example shows an event that Amazon S3 sent when a deployment package was uploaded to Amazon S3.

{
  "Records": [
    {
      "eventVersion": "2.1",
      "eventSource": "aws:s3",
      "awsRegion": "us-east-2",
      "eventTime": "2019-09-03T19:37:27.192Z",
      "eventName": "ObjectCreated:Put",
      "userIdentity": {
        "principalId": "AWS:AIDAINPONIXQXHT3IKHL2"
      },
      "requestParameters": {
        "sourceIPAddress": "205.255.255.255"
      },
      "responseElements": {
        "x-amz-request-id": "D82B88E5F771F645",
        "x-amz-id-2": "vlR7PnpV2Ce81l0PRw6jlUpck7Jo5ZsQjryTjKlc5aLWGVHPZLj5NeC6qMa0emYBDXOo6QBU0Wo="
      },
      "s3": {
        "s3SchemaVersion": "1.0",
        "configurationId": "828aa6fc-f7b5-4305-8584-487c791949c1",
        "bucket": {
          "name": "lambda-artifacts-deafc19498e3f2df",
          "ownerIdentity": {
            "principalId": "A3I5XTEXAMAI3E"
          },
          "arn": "arn:aws:s3:::lambda-artifacts-deafc19498e3f2df"
        },
        "object": {
          "key": "b21b84d653bb07b05b1e6b33684dc11b",
          "size": 1305107,
          "eTag": "b21b84d653bb07b05b1e6b33684dc11b",
          "sequencer": "0C0F6F405D6ED209E1"
        }
      }
    }
  ]
}
Describe “The Cloud”
The cloud refers to servers accessed over the internet that store resources and software for computing and data storage.

What is a container (as it relates to computers and servers)?
A container is like a bundle containing an application and everything it needs to run.

What is auto-scaling?
A cloud computing feature that allows cloud services to automatically scale based on traffic and utilization.

What is bandwidth?
Bandwidth is how much data can be transferred by an entity such as a network or hardware.

How do cloud providers compute service costs? They charge based on the amount of usage of their services.

Document the following Vocabulary Terms
Server Instances A single instance of a server when it is run on a machine or virtual machine

Containers A self contained environment that contains an application and all of its dependencies.

Cloud Services Services provided by a cloud service provider such as computing resources and data storage.

Cloud Architecture All of the cloud services used in a project such as databases and computing resources.

AWS Amazon Web Services - a major cloud service provider

EC2/Beanstalk vs Heroku EC2/Beanstalk is AWS’s infrastructure solution for deploying software. Heroku is built off of these services and is more user friendly in my opinion.

