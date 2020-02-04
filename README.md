#The Definition of Software Architecture
In simple words, software architecture is the process of converting software characteristics such as flexibility, scalability, feasibility, reusability, and security into a structured solution that meets the technical and the business expectations.'''link:https://codeburst.io/software-architecture-the-difference-between-architecture-and-design-7936abdd5830'''
#MicroServices
MicroServices is one of many other software architecture patterns such as Layered Pattern, Event-Driven Pattern, Serverless Pattern and many more. Some of them will be discussed later. The Microservices pattern received its reputation after being adopted by Amazon and Netflix and showing its great impact. Now, let’s dig deeper into the architecture patterns.
Microservices that expose an HTTP endpoint, it is recommended
 that you use another framework, such as Flask
Flask is very flexible and doesn’t force you to adopt a specific layout style for your projects. It’s light-weight because it doesn’t require users to use particular tools or libraries. For example, Flask doesn’t come with any database access libraries. You will use extensions to add the functionality that you want.
The microservices talk to each other using REST API. How do they know the address (host:port) of other services? In this example, each microservice runs on a separate port so we could identify them. In real-world projects, people use more advanced techniques such as service discovery (either server or client side; consul is a popular tool that people use for this purpose.)
*in flask-tutorial-04 we will do user authentication microservice in flask and deploy with docker to give you a home page found in the welcome micro service home page (flask-tutorial-02)
