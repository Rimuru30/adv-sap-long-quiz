## Long Quiz in Advanced Systems Integration & Architecture
1. Service-oriented architecture (SOA) is an approach to creating software applications that takes advantage of reusable components or services, it is also a software design pattern which makes two or more system or applications to talk each other 

2. List and discuss the characteristics of SOA 

Standardized Service Contracts - it is a software design principle applied within the service oriented design paradigm to ensure that contracts within a service inventory and the standardized service contracts also serve their contracts like express their purpose, their capabilities to ensure that the contract will do or must be done

Loose Coupling - it is a software design principle that give implementation while still guaranteeing baseline compatibility fir ysers who have grown or rely on the service features

Abstraction - Abstraction allows enterprise to define technology in the context of a business process and also abstraction breaks the dependencies and introduces agility.

Reusability - in its own word reusability, it can look for existing service before creating new ones or look for reuse before creating new services

Autonomy - Consumers need the defined service contract engagement so the users can then consume or in simple words it is a freedom and control to make its own decisions without the need for approval or involvement

Statelessness - it is a service minimization of resource consumption or simply the information shortened but still complete


Discoverability - it is a metadata for discovery which also communicate purpose and capabilities to human, The system must communicate on the consumer and offer as much as detail as possible.

Composability - It breaks the big problem to small problem, It helps us to solve problem into manageable parts

Interoperability - Services sets standards that allow subscribers to use the servicee and architecture ensure that services dont get reduced and interoperability referers to the sharing of data, The more software programs are, the easier for them to exchange data

3.Define Microservices

Microservices is also like SOA but Microservices is used to build individual applications in a way that makes them more scalable and resilient, in simple words it is like multiple pieces of lego or blocks that if you put together it build different structures, microservices are small, independent components that if you combine it will build larger applications

4. List and discuss the benefits of using Microservices 

Independently deployable- it is the most important characteristics of microservices, it is independently deployable becuase the services are smaller they communicate with each other via networks and as architecture choice offer many option for solving the problems you may face.

Right tool for job - It is one of the benefits of using microservice, microservices is the right tool for the job by making easier to deploy more data because it can be small pieces but complete data and each service can use its own language and framework for you to communicate easily with your application of choice

Precise Scaling - with microservices, individual services can be individually deployed and from its word precise scaling it gives accuracy of expression or the exactness of service, it can not only handle a large number of tasks at the same time but it can handle them efficiently and exactly

5.List and discuss the similarities and differences of SOA and Mircoservices

Similarities
Reuse - The SOA will look for existing service before creating new ones or look for reuse before creating new services. The Microservice prefer to reuse code by copy and accept data duplication.

Synchronous calls - The SOA service are available throughout enterprise via synchronous protocols while Microservices use synchronous calls will create real time dependencies or when one service sends a request to another service and wait for the response before proceeding futther

Data duplication - They both collections that focus on performing specific function, they are also the same in terms of maintaining complex data synchronization patterns

Differences between SOA and Microservices

Communication - The SOA communication is handled by ESB according to the handout and it can become a single point of failure for the whole enterprise because it only provides the medium by which services "talk" to each other and if a single service slows down the entrie system can be affecte, While the Microservice developed independently with its own communication protocol and relies on simpler messaging system like APIs which enable quicker communication

Interoperability - in SOA Services sets standards that allow subscribers to use the servicee and architecture ensure that services dont get reduced and interoperability referers to the sharing of data, The more software programs are, the easier for them to exchange data
while in Microservices are capable of two or more information system or components that allow exchanging and use of information across systems

Service granularity - The Microservice has highly specialized services but it is designed to do one thing while the SOA service can only range from small but specialized service to enterprise with wide services

Speed - SOA is simplify development and troubleshooting and because of that this also tends to make SOA operate more slowly than microservice and also because microservice allow developers to work on small independent pieces of an application so it can quickly deloyed and tested without affection the rest of the application.

6. Define Web Services - It is a software system that can communicate and share data with other software systems or function over a network.

7. List and discuss the benefits of using Web Services 
- Exposing the existing function on the network, it allows the user to use functionality if a code that is already exist over the network. This also allows other application to use the functionality of your program

- Interoperability is the ability of an application and systerm to securely and automatically exchange data. Without interoperability, Systems cannot interpret or utilize data to meet the coommon goals

- Standardized Protocol is a Web Service use standardized protocol refers to set rules and guidelines that define how different softwares system and function can communicate with each other over a network web services has standardized protocol because it focus on protocol and not on implementations

- Low Cost Communication- Web services use SOAP, it is a lightweight protocol used to create web API's and use for exchanging structured information so it is a low cost internet implementing web services

8. List and discuss the characteristics of Web Services 

- XML Based or the extensible markup language, it is a markup language that used to encode documents in format that is both human-readable and machine readable

- Loosely coupled it is the degree of interdependence between different components of a system and web service can change overtime without arrangement the client to interact with the service

- Coarse-Grained web service is a Java expose services through individual method,the coarse grained web services are designed to have broader fucntionality in comparison to fine-grained services

- Ability to be Synchronous or Asynchronous - Example in synchronous, The client will wait until the server returns the response message in this situation. The client application is able to determine the condition of the web service's execution while utilizing the synchronous service. While it can also be Asynchronous by allowing the client to invoke a service execute their function 

- Supports Remote Procedure Calls (RPCs) - RPCs allow a program to invoke procedure and functions on remote objects, RPCs style are synchronous it means the client has to wait for the response after the request

- Supports Document Exchange - Web services supports document exchange by using XML in generic way to represent data, This enables applications to share and collaborate on data and improving data integration

9. List and discuss the distinct roles in Web Services Architecture

- Provider creates web service and makes it available to application or in client application who wants to use it

- Requestor is a service request can be conducted through the web browser or client application

- Broker is application that provides access to UDDI to enables the client application to web service

- Publish informs the service registry or the broker about the things that on going in the web service by using service registries publish interface  

- Find is the process of service requester inquring the service registry about the location of the service provided by the service provider

- Bind is a group of service providers and requestors including service accessing path, calling parameter, transport protocol and security requirements

10. List and discuss the web services components

- SOAP in web services is the SIMPLE OBJECT ACCESS PROTOCOL which uses XML as a payload or request body. All request and responses are carried by the XML and it is a platform and language independent.

- WSDL in web services is the WEB SERVICES DESCRIPTION LANGUAGE it is very useful in web service because it defines where the web service resides to be picked up for request it is also navigates for inviduals and other businesses to access service

- UDDI in web services is the UNIVERSAL DESCRIPTION DISCOVERY and INTEFGREATION it is a service provider who provides the web service, It also uses WSDL to describe interface to web services
