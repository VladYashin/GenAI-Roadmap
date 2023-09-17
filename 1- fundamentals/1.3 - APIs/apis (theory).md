# APIs

## Table of Contents
1. [Definition](#definition)
2. [Why do we use API?](#why-do-we-use-api)
3. [How do APIs work?](#how-do-apis-work)
   - [SOAP APIs](#soap-apis)
   - [RPC APIs](#rpc-apis)
   - [Websocket APIs](#websocket-apis)
   - [REST APIs](#rest-apis)
4. [Why REST APIs are so popular?](#why-rest-apis-are-so-popular)
5. [What are the benefits of REST APIs?](#what-are-the-benefits-of-rest-apis)
6. [Learn more](#learn-more)


## Definition
An Application Programming Interface (API) is a set of rules and protocols that allows different software entities to communicate with each other.

## Why do we use API?
To retrieve data, integrate with other systems, automate tasks, and expand functionality without needing to understand or modify the underlying system.

## How do APIs work?

API architecture is usually explained in terms of client and server. The application sending the request is called the client, and the application sending the response is called the server. Let's assume we have a mobile earthquake prediction application. 

In this example, the earthquake's database/prediction system is the server, and the mobile app is the client.

![Alt Text](/images/apis_working_principles.png)


There are four different ways that APIs can work depending on when and why they were created:

- **SOAP APIs** 
These APIs use Simple Object Access Protocol. Client and server exchange messages using XML. This is a less flexible API that was more popular in the past.

- **RPC APIs**
These APIs are called Remote Procedure Calls. The client completes a function (or procedure) on the server, and the server sends the output back to the client.

- **Websocket APIs**
Websocket API is another modern web API development that uses JSON objects to pass data. A WebSocket API supports two-way communication between client apps and the server. The server can send callback messages to connected clients, making it more efficient than REST API.

- **REST APIs**
These are the most popular and flexible APIs found on the web today. The client sends requests to the server as data. The server uses this client input to start internal functions and returns output data back to the client. Let’s look at REST APIs in more detail below.

In this roadmap we'll focus primarily on using REST APIs. 

## Why REST APIs are so popular?
The main feature of REST APIs is statelessness. Statelessness means that servers do not save client data between requests. Client requests to the server are similar to URLs you type in your browser e.g. Chrome, Firefox, etc. 

The response from the server is plain data, without the typical graphical rendering of a web page. The main format for repsonses is [JSON](https://www.json.org/json-en.html).

## What are the benefits of REST APIs? 

1. **Streamlined Integration**
   APIs serve as a means to seamlessly integrate new applications with existing software systems. This significantly accelerates development processes as it eliminates the need to build every functionality from scratch, allowing developers to harness the power of pre-existing code.

2. **Catalyst for Innovation**
   The introduction of a new application can transform entire industries. To remain competitive, businesses must respond swiftly and facilitate the rapid deployment of innovative services. APIs play a crucial role in this by enabling modifications at the API level, sparing the need for a complete rewrite of the underlying codebase.

3. **Facilitating Expansion**
   APIs offer a unique opportunity for businesses to meet the diverse needs of their clients across various platforms. For instance, a maps API allows seamless integration of map information on websites, Android, iOS, and more. Any business can provide similar access to their internal databases by leveraging both free and paid APIs.

4. **Simplified Maintenance**
   APIs act as intermediaries between two systems, requiring each system to make internal adjustments to ensure the API remains unaffected. This approach ensures that future code changes made by one party do not disrupt the other, simplifying the maintenance process.


## Learn more
    - [API Basics on MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction)
    - [Postman Learning Center](https://learning.postman.com/)
    - [RapidAPI Blog](https://rapidapi.com/blog/)