# CS230
CS 230 - Operating Platforms


### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
  - The client, The Gaming Room, wanted to expand their Android-based game, Draw It or Lose It, into a multi-platform, web-based environment. They required software capable of supporting multiple platforms while ensuring scalability, unique identifiers for game entities, and centralized data management.
    
### What did you do particularly well in developing this documentation?
  - The documentation effectively recommended a scalable and cost-efficient Linux-based platform and proposed practical design patterns, like Singleton and Iterator, to manage centralized game services and unique identifiers. Additionally, the security considerations and distributed system strategies were aligned with the client's needs for cross platform communication.
    
### What about the process of working through a design document did you find helpful when developing the code?
  - Working through the design document helped outline the system architecture and identify clear requirements, such as scalability and security, before implementation. It also provided a roadmap for integrating modular components like REST APIs and caching mechanisms, ensuring consistent communication and performance.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
- I would revise the discussion on distributed systems to include more specific techniques for handling session consistency, fault tolerance, and network outages. Enhancing this section with concrete examples, like using Redis for session management or Kubernetes for orchestration, would make the recommendations more actionable.

### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  - I interpreted the user's need for scalability and cross-platform compatibility by recommending REST APIs, microservices, and caching mechanisms. Considering user needs ensures the software aligns with business goals, enhances usability, and allows seamless future expansion. Just like testing verification verifies that we made the code correctly, we need software validation to validate that we made the correct code.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
-  I approached software design by first analyzing the client's requirements and then proposing modular architectures and design patterns to meet them. In the future, I would incorporate prototyping and iterative feedback cycles to validate designs and refine them based on client input.
