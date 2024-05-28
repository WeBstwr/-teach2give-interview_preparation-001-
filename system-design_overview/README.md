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

