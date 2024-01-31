+++
author = "Sachin Parihar"
title = "What is Serverless?"
date = "2019-03-05"
description = "Way to build and run applications and services without having infrastructure."
tags = ["emoji"]
image = "/images/artist.jpg"
+++

1. **Serverless Computing** is a way of building and running applications and services without having infrastructure. This means that you don't have to worry about maintaining servers to run your code, as an infrastructure managed by a cloud provider(aws, azure, gcp cloud).

2. Serverless doesn't mean that they don't have servers. There are still servers but they are abstracted away from app development. It means that you don't need to maintain, provision, or scale servers, you only need to focus development side. This can save time and money, and allow developers to focus on writing code.

3. Serverless computing uses event-triggered stateless containers to host your services. They can scale out and in to meet demand as needed.

## How does it work?

1. In a serverless architecture, you write and deploy your code as functions. These functions are executed in response to events, such as an HTTP request, a database write, or a message published to a message queue. When an event occurs, the cloud provider runs the functions and returns the result to the client.

## Benefits of serverless architecture

1. **Cost-effective:** You only pay for the resources that your functions use when they are executing.

2. **Scalability:** Your functions can automatically scale up or down based on demand, so you don't have to worry about capacity planning.

3. **Flexibility:** You can write code in any language as suits you best.

4. **Speed:** You can deploy and update your functions quickly.

5. **Simplicity:** You don't have to worry about infrastructure, so you can focus on writing code and building your applications.

## Drawbacks

1. **Complexity:** Serverless architectures can be more complex to design and build, especially if you are using multiple functions and triggers. This can make it more difficult to debug and troubleshoot issues.

2. **Higher cost:** While serverless architectures can be cost-effective at lower scales, they can become more expensive as the scale increases.

3. **Cold starts:** When a function is triggered for the first time, or after it has been idle for a while, there can be a delay before the function starts executing.

## Conclusion

1. Overall, Serverless computing is a powerful technology to build and deploy applications. If you are looking to build and deploy an application quickly, serverless computing would be worth considering.

Further more reading on Serverless Computing: Checkout This
