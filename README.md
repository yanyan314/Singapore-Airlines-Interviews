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

# 6.How to integrate modules in Spring?
To integrate modules in Spring, I rely on my experience with building scalable and modular applications using Spring Framework. One approach I've utilized is dependency injection, a core concept in Spring, to manage the dependencies between different modules. By configuring components in the Spring container and injecting dependencies through annotations or XML configuration, I ensure loose coupling and flexibility within the application.

For instance, in my previous project, we had a service layer that was tightly coupled with the data access layer. Upon refactoring, I introduced Spring's @Autowired annotation to inject the repository dependencies into the service layer, reducing the coupling and making it easier to swap out implementations without affecting other modules. 

Furthermore, I make use of Spring's modular architecture by dividing the application into smaller, manageable parts known as modules. Each module encapsulates specific functionalities and can be developed and tested independently. By leveraging Spring's support for modularization through components like Spring Boot and Spring MVC, I ensure that each module remains cohesive while still being loosely coupled with other parts of the system, improving maintainability and scalability.

# 7.How does the body in a GET request get handled differently from the body in a POST request?
In a GET request, the body of the request is typically empty because GET requests are used to retrieve data from a server rather than sending data to a server. GET requests are meant to be idempotent, meaning they should not have any side effects on the server. On the other hand, in a POST request, the body of the request is used to send data to the server, such as form submissions or JSON data. POST requests are not idempotent and can have side effects, like creating a new resource on the server's database.

By understanding the differences in how GET and POST requests handle the body of the request, software engineers can design more efficient and secure APIs that align with the intended functionality of each HTTP method.

# 8.How much was your expected salary?
Based on my experience in software engineering and the skills showcased in my resume, I am seeking a competitive salary that reflects the value I can bring to the role of a Software Engineer. Throughout my career, I have consistently delivered high-quality work that has directly contributed to the success of projects. 

# 9.Describe agile scrum aspects. 
Agile Scrum is a framework used in software development that emphasizes collaboration, flexibility, and continuous improvement. One important aspect of Agile Scrum is the concept of sprints, which are time-boxed iterations where development work is completed. During my previous role as a Java Developer, my team adopted agile and used 2 weeks sprints. By breaking down the project into manageable chunks, we were able to deliver incremental value to the product and receive feedback from stakeholders more frequently. At the beginning of the sprint, we have a sprint-planning meeting, in that meeting, we will priority the tasks and put tasks in that sprint.

Another key aspect of Agile Scrum is the daily stand-up meetings, also known as daily scrums. These brief meetings provided my team with the opportunity to discuss progress, challenges, and coordinate efforts to ensure alignment towards our sprint goals. I found these daily interactions to be highly beneficial in fostering communication and transparency within the team.

Furthermore, Agile Scrum promotes the use of retrospective meetings at the end of each sprint to reflect on what went well, what could be improved, and action items for the next sprint. In one particular project, after conducting a retrospective, we identified a bottleneck in our deployment process that was causing delays. By addressing this issue and streamlining our deployment pipeline, we were able to reduce our release cycle time , resulting in quicker delivery of features to our customers.

# 10.How familiar are you with ci and cd?
When I worked at Thomson Reutures, I acted as global Devops function leader. I am responsible for design and implement the CI/CD pipeline to deploy our product to AWS. We have several projects, some implmented CI/CD pipeline by using jenkins, some are using gitlab, also have projects that use codepiple in AWS. so I am quite familiar with CI/CD. Continuous Integration is all about validating software as soon as it's checked in to source control, more or less guaranteeing that software works and continues to work after new code has been written. Continuous Delivery succeeds Continuous Integration and makes software just a click away from deployment. Continuous Deployment then succeeds Continuous Delivery and automates the entire process of deploying software to your customers (or your own servers).

If Continuous Integration, Delivery, and Deployment could be summarized with one word, it would be Automation. All three practices are about automating the process of testing and deploying, minimizing (or completely eliminating) the need for human intervention

In summary, my experience with CI/CD has shown me the importance of automation in the development lifecycle, enabling faster and more reliable releases while maintaining the quality of the product. I am confident in my ability to leverage CI/CD practices effectively to optimize the development and deployment of applications.

# 11.What are the key differences between front-end and back-end development?
Front-end development primarily focuses on the user interface and user experience of a website or application. This involves working with technologies like HTML, CSS, and JavaScript to create visually appealing and interactive elements that users interact with directly.

On the other hand, back-end development deals with the server-side logic, databases, and ensuring the smooth functioning of the application behind the scenes. It involves languages like Python, Java, and databases like MySQL or MongoDB. In acted as back-end engineer both at IBM and Tomsons Reuters.

Understanding the differences between front-end and back-end development is crucial for delivering a seamless user experience. While front-end focuses on the presentation layer, back-end ensures that the application runs smoothly and efficiently. Both aspects are integral to the success of a website or application, and a balance between the two is essential for a successful development process.

# 12.questions
If I am lucky to join the company, what's the biggest changllenge for the position? and what skills I can prepared in advance for the job?

# 13.AI
powerful applications enabled by LLMs is sophisticated question-answering (Q&A) chatbots. These are applications that can answer questions about specific source information. These applications use a technique known as Retrieval Augmented Generation, or RAG.
RAG is a technique for augmenting LLM knowledge with additional data.
LLMs can reason about wide-ranging topics, but their knowledge is limited to the public data up to a specific point in time that they were trained on. If you want to build AI applications that can reason about private data or data introduced after a model’s cutoff date, you need to augment the knowledge of the model with the specific information it needs. The process of bringing the appropriate information and inserting it into the model prompt is known as Retrieval Augmented Generation (RAG).

LangChain is a framework for developing applications powered by language models. Before your chosen LLM can act on your data, you first need to process the data and load it. We use llamindex to Load the data
Transform the data and Index and store the data in  With your data loaded, you now have a list of Document objects (or a list of Nodes). It's time to build an Index over these objects so you can start querying them. Vector Store Index embeds your documents. embedding, is a numerical representation of the semantics, or meaning of your text. Once the ranking is complete, VectorStoreIndex returns the most-similar embeddings as their corresponding chunks of text. The number of embeddings it returns is known as k, so the parameter controlling how many embeddings to return is known as top_k. This whole type of search is often referred to as "top-k semantic retrieval" for this reason.


 

