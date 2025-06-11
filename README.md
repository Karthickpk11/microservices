# microservices

The rise of microservices has been a remarkable advancement in application development and deployment. With microservices, an application is developed, or refactored, into separate services that “speak” to one another in a well-defined way –via APIs, for instance. Each microservice is self-contained, each maintains its own data store (which has significant implications), and each can be updated independently of others.

Moving to a microservices-based approach makes app development faster and easier to manage, requiring fewer people to implement more new features. Changes can be made and deployed faster and easier. An application designed as a collection of microservices is easier to run on multiple servers with load balancing, making it easy to handle demand spikes and steady increases in demand over time, while reducing downtime caused by hardware or software problems.

Microservices are a critical part of a number of significant advancements that are changing the nature of how we work. Agile software development techniques, moving applications to the cloud, DevOps culture, continuous integration and continuous deployment (CI/CD), and the use of containers are all being used alongside microservices to revolutionize application development and delivery.

**Using an API Gateway** – An API Gateway is the single point of entry for entire microservices-based application, presenting the API for each microservice.

**Inter-process Communication in a Microservices Architecture** - Once you break a monolithic application into separate pieces – microservices – the pieces need to speak to each other. And it turns out that you have many options for inter-process communication, including representational state transfer (REST).

**Service Discovery in a Microservices Architecture** – When services are running in a dynamic environment, finding them when you need them is not a trivial issue.

**Event-Driven Data Management for Microservices** – Instead of sharing a unified application-wide data store (or two) across a monolithic application, each microservice maintains its own unique data representation and storage. This gives you great flexibility, but can also cause complexity.

**Choosing a Microservices Deployment Strategy** – In a DevOps world, how you do things is just as important as what you set out to do in the first place.

**Refactoring a Monolith into Microservices** – In a perfect world, we would always get the time and money to convert core software into the latest and greatest technologies, tools, and approaches, with no real deadlines. But you may well find yourself converting a monolith into microservices, one… small… piece… at… a… time.

Do you want build the Enterprise Software Systems?
The following is a list of common characteristics that need to be available in a good enterprise software system:  
    • Scalability  
    • Availability  
    • Latency   
    • Robustness  
    • Security  
    • Modularity  
    • Reusability  
    • Replaceability  
    • Observability  
    • Adaptability  

**Scalability**: In the past, the growth of an enterprise took a considerable amount of time, and the enterprise teams had enough lead time to plan on scaling the applications. But in today’s world, enterprises can launch their products and services to larger audiences through the Internet, and the growth of the customer base can be instantaneous. Sometimes, you would receive ten times more traffic than what you initially estimated, and your enterprise system should be capable of scaling to these demands instantly. Utilize technologies provided by infrastructure providers to automatically scale the components based on certain metrics such as CPU usage, latency, or number of users. There are two types of scalability: _**Horizontal scalability**_ and _**Vertical scalability**_
