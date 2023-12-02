## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
 - A design pattern used in business software development, where it focuses in using software components called services. Services are a unit of software designed to perform a specific task, SOA makes these services independent and reusable, which means these services can be used for other business processes, platforms, and systems. Furthermore, the independent services can be combined to create a larger and more complex applications. Service example: authentication functionality
 - Aside from creation and organizing of independent services, SOA is also a middleware for different systems or applications which means it is efficient as it handles necessary functionalities to let these services connect and communicate with each other across multiple platfroms and different languages. 
2. List and discuss the characteristics of SOA.
    + Standardization
      - standardizes how business processes are automated and used in a way that maintains security and governance.
    + Reusability
      - SOA services are held in a repository and linked upon request, making the services a resource accessible to everyone. Reusing services saves organizations time and reduces development costs.
    + Ease of maintenance
      - Since these services are independent, it is easier to modify or add some changes without affecting other services. This lessens the operating costs as well as the cost of maintenance compared to codes that are very fragile.
    + Interoperability
      - allows different distributed web services to run on a variety of software platforms and hardware architectures.
    + Increased reliability
      - SOA create reliable applications because the small services are easier to debug than large code or a monolothic method of development.
    + Scalability
      - In my own understanding, scalability in SOA refers to the services having only one certain function where it makes upgrading this specific function a lot easier as well as add some changes related to that specific service.
3. Define Microservices.
- Microservices is an architecture used in developing an application that consists of collection of independent services. From monolothic approach of creating systems where everything is centralized to multi-tier application where the creation of business software are separated into layers to implementing Microservices where services are independent and have only one business function for the purpose of improving maintenance, reusability, complexity, and scalability of a business software.
- Mircroservices provides an architecture where teams with different functionalities to develop can work separately and independently of each other, this lowers the risk of damaging or impacting other teams through the devleopment process. This can also mean that different services can be developed using different programming languages and can be deployed to different platforms. These microservices grow along with the growth of an enterprise, since these microservices are highly distributed, if a microservice instance fails it could cascade outages to other microservices and finding the root cause would become difficult and fixing it immediately will be also hard.  
4. List and discuss the benefits of using Microservices.
    + Smart endpoints and dumb pipes
      - Microservices aim to be as decoupled and as cohesive as possible, so they own their own domain logic and receiving a request, applying logic and producing a response with using their own Restful APIs.
    + Decentralized Governance
      - Sharing useful and all tested code as libraries, encourages other developers to solve similar problems in similar ways.
    + Decentralized Data Management
      - Microservices let each services manage its own database. 
    + Scalable
       - Each service operates independently which means it is easier to scale individual services up or down as needed, without affecting the other microservices that make up the application. 
    + Resilience
       - a fault in one service does not disable the entire application.
    + Agility
       - A microservice architecture offers faster development and greater agility compared to a      monolith method.
5. List and discuss the similarities and differences of SOA and Microservices.
- In terms of principles and characteristics SOA and microservices are similar in being Scalable, Reliable and Resilient. Both have independent services within a system which are focused only on one function or business process,service or capabilities which makes the three characteristics possible with these architectures. Furthermore the services in both SOA and microservices can be deployed to different application and can run on different programming languages. The difference between the two is that Microservices are structures independent of each other in a way that these services can have and handle their own databases and APIs, the services in this architecture focuses on a single task only and a lot more smaller than SOA, while SOA is an architecture that has indpendent services but these services are shared and reused to perform multiple business tasks.Furthermore, these services in SOA communicates with each other and can be combined to create a more complex application. 

- Microservices addresses the shortcomings of the SOA, it is because while SOA  work well for building large enterprise applications, it needs more flexibility to scale smaller business-specific applications. This is where Microserrvices come in where it divides SOA service into smaller services or a more fine-grained approach to building applications.  
6. Define Web Services.
- Basically, web services are any software, application, or cloud technology that uses standardized web protocols either HTTP or HTTPS to communicate and exchange data through the internet. Web services usually uses XML, a markup language format that uses a set of rules in encoding data that is readable for both human and machine. Web services makes communication of applications with different programming languages possible.
7. List and discuss the benefits of using Web Services.
- Ease of Use
  + Interoperability 
    - Since web services is not tied to a particular programming language, hardware or system. The technology used in web services allows different applications to communicate with each other and allows the transport of information written in any format over the internet. 
  + Reusability
    - In my own understanding of web services, these are services that has interoperabiliry and flexibility as it can enable communication of different applications in an enterprise. This means that web services are reusable because it can be used for different applications without re-creating or duplicating the codes of services. 
8. List and discuss the characteristics of Web Services.
  - Web services are self-contained and do not need any additional sofware nor requires writing additional code to use. Only the support of XML and HTTP is required which is available in most technologies used for web development.
  - Web services are also composable, meaning these services are reusable and can be easily rearranged or assembled to cater a certain necessary service for a business. 
9. List and discuss the distinct roles in Web Services Architecture.
  - Service Provider
    + A service provider software hosts and creates web services. This also publishes the services and its description and make it available to client applications by sending to the directory or the Service Registry.
  - Service Registry
    + In other discussion in the internet and also from what i understand, Service Registry is like the directory which contains the services and its description, it also like the middleman between the client and the service provider. This application is responsible in looking for and invoking interaction with a service.  It is also the application that provides access to the UDDI. The UDDI enables the client application or the Service Requestor to locate the web service.
  - Service Requestor
   + This application creates the query to request a service to the Service Registry, find out what services are available and how to communicate with the service provider.
10. List and discuss the Web Services Components.
  - SOAP (Simple Object Access Protocol)
   + Is is a messaging protocol for communication between service provider to services registry(directory) and service requestor to services registry(directory), or to exchange structured information in the web services within a computer network. 
  - UDDI (Universal Description, Discovery and Integration)
   + An XML based standard for describing, finding, and publishing web services which is used in Service Registry for the client application to locate a web service. Also, It is a registry for businesses or enterprises providing web-based services to list themselves and find partners on the internet.
  - WSDL (Web Services Description Language)
   + This is a industry accepted language used to create service descriptions. Before a service description to be placed in the directory or service registry, it ha to be created in WSDL.