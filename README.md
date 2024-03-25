# Singapore-Airlines-Interviews

# 1.How would you familiarize yourself with your work in a situation where all your colleagues and your boss are preoccupied?

I have that experience when I worked at IBM. The first week when I joined IBM, all my colleagues and my boss were preoccupied and they were busy working on one release, I would approach familiarizing myself with my work by leveraging my past experiences and technical skills. Firstly, I would thoroughly review any documentation or existing code related to the project to understand the current state and requirements. 

Additionally, I would utilize online resources, such as technical documentation, forums, and online courses, to fill any knowledge gaps that I may have. For example, in my previous role in Thomson Reuters, when joined the team, I knew that our project is deployed on AWS and I didn't have any cloud experience at that time, so I started to read the documents on AWS website to make me have a overview pages of all the services that AWS provided. At last, I were in charge of all the infrastrue design and deployment on AWS and make our project release successful.

Furthermore, I would seek out any available resources within the company, such as knowledge documents/confluence pages or tools, to expedite the learning process. By taking these steps, I aim to quickly get up to speed with the project requirements and contribute effectively towards achieving our team's goals.

# 2.Do you have experience with documentation? if so, how do you approach it?

Yes, I have experience with documentation throughout my career as a Software developer Engineer and Devops engineer. In my previous role at Thomson Reuters, I was responsible for maintaining technical documentations for AWS infrastruct part. The document is clear about how we design the AWS infrasture, how we do the deployement and some troubshooting tips. This not only enhanced team productivity as developers spent less time troubleshooting due to clearer instructions, but also make the new joiners farmiliar with our project quickly.

Furthermore, I were use Git to track document changes, ensuring that all updates were properly documented and easily retrievable. By implementing this process, it make the team members to access the most up-to-date information efficiently.

I also maintained documents in confluence pages about the technical implement details for the big new features and security reports. This confluence pages make team clear about logic for the new features and make my boss clear about our production's security status.

# 3.Explain the concept of microservices architecture
 If you’re building a large, complex application, you should consider using the microservice architecture.
 The high-level definition of microservice architecture (microservices) is an architectural style that functionally decomposes an application into a set of services.
 Microservices architecture is an approach to software development where applications are composed of small, independent services that communicate with each other through well-defined APIs. As a Java Developer with     experience in building scalable and reliable systems, I have experienced to rewite our service to be micro-services architecture style. The project that I worked at Thomson Reuters is packaged as single execution file, that is monolithic style of architecture, With the business logic complexity grow, it make the code base larger. That brings lots of problems
 1. As the code base grows, it’s too complex and too large for any developer to fully understand.
 2. Path from commit to deployment is long -- Because the code base is so complex and the impact of a change isn’t well understood, developers and the Continuous Integration (CI) server must run the entire test suite.
 3. Scaling is difficult -- That’s because different application modules have conflicting resource requirements.
 4. Lack of reliability ---One reason it’s unreliable is that testing the application thoroughly is difficult, due to its large size. As a result, there are frequent production outages. The application lacks fault isolation, because all modules are running within the same process. Every so often, a bug in one module—for example, a memory leak—crashes all instances of the application, one by one.
 5. The monolithic architecture makes it difficult to adopt new frameworks and languages. It would be extremely expensive and risky to rewrite the entire monolithic application
 So we decide to rewirte our project to be micro-services architecture style.
 Benefits and drawbacks of the microservice architecture
 The microservice architecture has the following benefits:

    It enables the continuous delivery and deployment of large, complex applications.

    Services are small and easily maintained.

    Services are independently deployable.

    Services are independently scalable.

    It allows easy experimenting and adoption of new technologies.

    It has better fault isolation.

Drawbacks of the microservice architecture
Certainly, no technology is a silver bullet, and the microservice architecture has a number of significant drawbacks and issues.
Here are the major drawbacks and issues of the microservice architecture:

    Finding the right set of services is challenging.
    One challenge with using the microservice architecture is that there isn’t a concrete, well-defined algorithm for decomposing a system into services. As with much of software development, it’s something of an art. To make matters worse, if you decompose a system incorrectly, you’ll build a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic architecture and the microservice architecture.

    Distributed systems are complex, which makes development, testing, and deployment difficult.
    Services must use an interprocess communication mechanism. This is more complex than a simple method call. Moreover, a service must be designed to handle partial failure and deal with the remote service either being unavailable or exhibiting high latency.
    Each service has its own database, which makes it a challenge to implement transactions and queries that span services.

    Deploying features that span multiple services requires careful coordination.

    Deciding when to adopt the microservice architecture is difficult.

# 4.How do you prioritize your tasks and tickets?  
 I consistently prioritized tasks based on their impact on project timelines, customer satisfaction, and revenue generation. We use a tracking system that Jira tickets will be created for each task, We will have a sprint planning meeting to estimation the time spend on the tasks and then collaborate with the product management team to understand the business priorities and set tasks priority with agreement with my manager.
 Additionally, we use a Kanban board to visually represent the status of each ticket, making it easier to identify bottlenecks and adjust priorities as needed. This visual representation not only helped me stay organized but also enabled the team to work collaboratively towards achieving our project goals. Overall, my approach to prioritizing tasks by effective communication with stakeholders and product management team.

# 5.Why are you keen to work in aviation?
I am keen to work in aviation because of my passion for technology and innovation in the industry. As demonstrated in my resume, I have a solid background in programming, especially in developing software solutions that optimize operations and improve efficiency. I believe that bringing my technical skills and problem-solving abilities to the aviation sector can contribute to streamlining processes and enhancing the overall passenger experience.

Furthermore, aviation is an industry that operates on a global scale, presenting diverse challenges that require constant adaptation and learning. This aligns with my career goal of working in a dynamic environment where I can continuously grow and expand my expertise. I am excited about the opportunity to be part of the aviation industry, where I can leverage my programming skills to make a tangible impact and be involved in shaping the future of air travel.

And I also had very good user experience with sigapore airline, no only during the process that I booked ticket from the website but also the services during the travelling.
 

