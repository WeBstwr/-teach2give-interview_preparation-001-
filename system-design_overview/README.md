# __Introduction to System Design__  
## Understanding System Design  
System design is a step-by-step process of defining a particular software’s architecture, components, modules, etc. It is a base concept in software engineering and vital in building scalable and reliable software.  
This system design primer helps you understand the essence of system design and various concepts from basics to advanced.  
## What is the Need for the System Design?  
System design is used to prepare the architecture of the software or application.  
Suppose you are a software developer and clients come to you that they need to build a software application. Firs, ask them about their requirements, functional and non-functional (scalability, high availability, consistency, etc.)  
After knowing the requirements, you need to prepare the architecture for the application according to requirements. Decide whether you want to use SQL or NoSQL databases based on the data you need to store. Then decide how to make the application scalable in case the traffic increases.  
## Exploring Essential Design Methods in System Design  
Developers are required to choose a particular method based on the project’s requirements.  
### 1.	Architectural Design  
This is the base of system design. It describes the infrastructure, model, view, components and interaction.  
### 2.	ERD Diagram  
ERD means entity-relationship diagram. It is mainly used in designing the application’s database structure.  
You can define multiple database schemas, add entities and add multiple attributes for each entity in the ERD diagram.
### 3.	UML Diagram  
UML stands for unified modeling language. It is used to prepare modeling software systems.  
### 4.	Class Diagrams  
Class diagrams are used to represent the classes, attributes, methods, and relationships between classes.  
Basically, it provides an overview of the system’s data and functionality.
### 5.	Sequence Diagrams  
They represent the interaction between the various components of the system. They model the behavior of the system.  
## Diving Deeper into System Design Concepts  
### 1.	Performance vs Scalability  
__Performance:__ If the loading time of your website is longer, traffic can decrease. Various mechanisms like caching can be used to increase the application’s performance and serve resources faster.  
__Scalability:__ Ability to scale the application. 
You can scale your application by distribution the load across multiple server’s capacity.  
### 2.	Latency vs Throughput  
They affect the efficiency of the system.  
__Latency:__ This is a network delay that occurs dues to Geographical distance, transport protocol, or network infrastructure.  
It is measured in Milliseconds.  
__Throughput:__ Number of operations the system can handle in a particular time or the number of data passed via network request in a given time.  
It is measured in megabytes (MB) per second and it checks the capability of the systems.  
### 3.	Consistency Patterns and Available Patterns  
__Consistency:__ It ensures that all nodes in the system read the same data at a particular time.  
__Availability:__ It ensures that each request receives a response either with fresh or old data.  
__Consistency Patterns__ <ul>
<li> Strong Consistency</li>  
<li> Eventual Consistency</li>  
<li> Weak Consistency</li>  </ul>   
 
__Availability Patterns__<ul>  
<li>Load Balancing</li>  
<li>Retry and Timeout strategies</li> </ul>  

## Advanced Concepts in System Design  
### 1.	CDN  
CDN stands for content delivery network. It is a distributed server network located at different geo-locations used to deliver content like images, various data, etc., from the server.  
It delivers the resource faster, decreases latency (network delay) and improves the application’s performance.  
### 2.	DNS  
Stands for domain name system.  
 It allows users to access the website and its resources using the domain name. It maps the unique domain name with a unique IP address.  
### 3.	Caching
It is a mechanism to serve resources faster. It is also called high-speed storage. Works between the web application and the source of the data.  
__NB:__ Cookies are used to cache data in your browser.  
### 4.	Proxies  
It is also called the proxy server. It works between the client of the application and the internet.  
The proxy servers are used for the caching.  
## Components of System Design  
### 1.	Microservices and Service Discovery  
The microservices break down complex applications into small services, such that each service works independently and accomplishes specific tasks.  
The concepts below are related to the microservices.  
<ul>
<li><b>Service Identification:</b> Every microservice has a unique ID and name for its identification.</li>
<li><b>Dynamic Service Discovery:</b> Each microservice can dynamically find other services located in the same network. This means that scaling and load balancing become easy.</li></ul>  

### 2.	Database Systems: RDBMS and NoSQL
__RDBMS__  
Stands for relational database management system. The SQL databases are built on the top of the RDBMS. It makes it easier to access the data from the database and connect it with other data as they are stored in the table format.  
Characteristics of the RDBMS database  
<ul>
<li>It stores the data in the table format.</li>
<li>You can’t scale the RDBMS database horizontally, but you can scale it vertically.</li>
<li>SQL is a query language for the RDBMS databases.</li>
<li>Accessing data from the RDBMS database is slow.</li>
</ul>  

__NoSQL__  
It means a non-SQL database. It stores data in the key-value pair instead of in table format. Use it when you are required to store unstructured data in the database.  
Characteristics of the NoSQL database.  
<ul>
<li>It stores the data in the key-value pair format.</li>
<li>It is horizontally scalable, as you can add new key-value pairs for new attributes.</li>
<li>It is faster than RDBMS databases</li>
<li>Each record can contain different key-value pairs.</li>
<li>It supports frequent changes in the database.</li>
</ul>  

### 3.	Communication Protocols
Protocols simply means rules and communication protocols refer to rules that communicate or exchange the data between systems. They can be server or client.  
Various communication protocols include:  
<ul>
<li>HTTP/HTTPS</li>
<li>TCP/IP</li>
<li>UDP</li>
<li>WebSockets</li>
</ul>  

## Approaching System Design Interview Questions
### Step-by-step Guide  

### 1.	Requirement Clarification  
Make sure you know the requirements before you prepare a system design for any software.  
There can be two types of requirements:  
<ul>
<li>Function Requirements:  Requirements in the application with which the user interacts. Example, navigation, authentication, etc.</li>
<li>Non-function requirements: Requirements to improve the application’s capabilities. Example, scalability, consistency, etc.</li>   
</ul>  

### 2.	Estimation of resources  
Decide what kind of resources you should use to build the application.  
Decide how much data you require to store in the database.  
### 3.	System interface definition  
A good example is defining the API endpoints and what to expect from each API endpoint.  
### 4.	Defining Data model  
Select a database for the application.  
If it’s a social media application, you can easily use Graph databases to manage many-to-many relationships.  
### 5.	High-level design  
Build the high-level components by deciding how you will connect the components of the system with each other.  
### 6.	Detailed design
Improve the system design by analyzing the system to fulfill the non-functional requirements.  

### 7.	Identifying and resolving bottlenecks
Lastly, identify the bottlenecks in your system design and discuss the solutions to resolve them with the interviewer.  

Sample System Design Interview Questions  
<ol>
<li>How would you design a URL Shortening service similar to TinyURL?</li>
<li>How would you design a Web Crawler?</li>
<li>How would you design Facebook and Instagram?</li>
<li>How would you design the API rate limit?</li>
