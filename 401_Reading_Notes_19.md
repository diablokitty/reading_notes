# Reading Notes for Day 19 of 401:

## AWS SQS vs SNS

### What is the difference betweeen SQS and SNS?

SNS is a subscribe and publish service, and SQS is a queing service, so messages published to SNS are pushed immediately while SQS messages wait for the subscriber to retrieve them. 

### What are some use cases for both SNS and SQS?

From the reading:

### Choose SNS if:

- You would like to be able to publish and consume batches of messages.
- You would like to allow same message to be processed in multiple ways.
- Multiple subscribers are needed.

### Choose SQS if:

- You need a simple queue with no particular additional requirements.
- Decoupling two applications and allowing parallel asynchronous processing.
- Only one subscriber is needed.


## AWS SNS and SQS


### Describe how to use SQS and SNS in a “fanout” pattern.
When a message is published, it is pushed to all subscribers regardless of type. Types could include clients of types SQS, lambda and email.

### Explain how “push notifications” work, using SNS.
A push notification is a notification that gets sent out by the service instead of waiting for the client to check for it. Once it is pushed, it's gone, so if the client is not currently connected, they will never see the message. 


## SQS and SNS Basics

### How might a large scale, distributed application make use of a Queue system like SQS?

A subscribed service might use SQS to send out links to access the data subscribers are expecting to access, but with an expiry date so that it's only available for a certain period of time. 

### Bookmark and Review

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)

### Things I want to know more about:

I'm not entirely clear about the relationship between SNS and SQS and will need to read to understand how the two interact, for example, if you want a message to be pushed and also persistent, does the SNS push to and SQS for each client?

[back to Table of Contents](./README.md)