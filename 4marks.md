# 4-marks

Certainly, let's delve into each of these questions in detail:

1. **Briefly discuss the issues related to distributed system design:**

   - **Communication:** Ensuring efficient and reliable communication between distributed components is a challenge. Issues include latency, bandwidth, and message passing.

   - **Consistency:** Maintaining consistency across distributed data is complex. Ensuring that all nodes have the same view of data at the same time is challenging.

   - **Concurrency Control:** Managing concurrent access to shared resources to avoid conflicts and data inconsistencies is a significant concern.

   - **Fault Tolerance:** Designing for fault tolerance involves handling node failures, network partitions, and ensuring system resilience.

   - **Scalability:** Ensuring that the system can efficiently handle a growing number of users or resources without significant degradation in performance.

   - **Security:** Securing communication and data in a distributed environment is critical to prevent unauthorized access and data breaches.

2. **What is the need for code migration? Explain the code migration issues in detail:**

   - **Code Migration Need:** Code migration involves moving a program or its parts from one location to another. It is necessary for load balancing, resource utilization, and adapting to changing conditions in a distributed system.

   - **Issues:**
     - **Data Migration:** Moving data along with code introduces complexities in ensuring data consistency and synchronization.
     - **State Migration:** Transferring the state of a running process is challenging due to differences in system architectures and dependencies.
     - **Communication Overhead:** Communication between the migrating entity and the target system can result in delays and increased network usage.
     - **Security Concerns:** Ensuring security during migration, especially in open networks, is crucial to prevent unauthorized access.

3. **What is distributed commit and recovery in distributed systems?**

   - **Distributed Commit:** Distributed commit refers to the process of ensuring that all nodes in a distributed transaction agree to commit the changes. It involves a coordinated protocol to reach consensus among participating nodes.

   - **Recovery:** Recovery in distributed systems deals with restoring the system to a consistent state after a failure. This includes recovering from node crashes, network failures, or other faults.

4. **Enumerate various issues in clock synchronization:**

   - **Clock Drift:** Clocks on different machines may drift apart due to differences in hardware, temperature, or oscillator precision.

   - **Clock Skew:** Clock skew occurs when the clocks on different machines do not advance at the same rate.

   - **Network Delays:** Variability in network delays can impact the accuracy of clock synchronization.

   - **Fault Tolerance:** Handling clock synchronization in the presence of faulty nodes or network partitions is challenging.

5. **List the differences between RMI and RPC:**

   - **Remote Procedure Call (RPC):**
     - Language-agnostic communication protocol.
     - Typically uses a platform-neutral interface definition language (IDL).
     - Examples include XML-RPC and JSON-RPC.

   - **Remote Method Invocation (RMI):**
     - Java-specific protocol for invoking methods on objects in remote JVMs.
     - Utilizes Java-specific serialization.
     - Involves passing Java objects as parameters and return values.

6. **What is Replication? Write about motivations for replication:**

   - **Replication:** Replication involves creating and maintaining copies of data or services in multiple locations to improve availability, fault tolerance, and performance.

   - **Motivations for Replication:**
     - **Fault Tolerance:** Replication provides redundancy, ensuring that if one replica fails, another can take over.
     - **Load Balancing:** Distributing the load among multiple replicas improves system performance and responsiveness.
     - **Data Locality:** Replicating data closer to users reduces access latency.
     - **Improved Availability:** Multiple replicas increase the chances of finding a working copy of data or service.

7. **What is CORBA’s Common Data Representation (CDR)? Explain:**

   - **CORBA's Common Data Representation (CDR):** CDR is a standard for encoding and decoding data in CORBA, allowing communication between objects written in different programming languages.

   - **Explanation:**
     - CDR provides a standardized way to represent complex data structures in a language-independent manner.
     - It facilitates interoperability by ensuring that data can be exchanged seamlessly between different CORBA-compliant systems.
     - CDR includes rules for encoding basic data types, structures, arrays, and pointers.

8. **What is DFS? Also, write the features of DFS:**

   - **DFS (Distributed File System):** A DFS is a distributed implementation of the traditional file system that allows files to be shared and accessed over a network.

   - **Features of DFS:**
     - **Distributed Storage:** Files are stored across multiple servers, allowing for increased storage capacity.
     - **Scalability:** Can scale to accommodate growing storage needs.
     - **Fault Tolerance:** Provides redundancy and fault tolerance by replicating data across multiple servers.
     - **Access Transparency:** Users can access files without needing to know their physical location.
     - **Concurrency Control:** Manages concurrent access to files to avoid conflicts.

9. **Explain how simple client-server communication is done:**
   - In simple client-server communication:
     - The **client** initiates communication by sending a request to the server.
     - The **server** listens for incoming requests.
     - Upon receiving a request, the server processes it and sends a response back to the client.
     - Communication is typically based on a protocol (e.g., HTTP for web communication), and sockets may be used for establishing a connection.

10. **What is Interceptor? Explain briefly:**
    - An **Interceptor** is a software component that intercepts and modifies the behavior of a system. In the context of distributed systems, interceptors are often used to add functionalities such as logging, security checks, or performance monitoring to communication between components.

11. **Briefly explain the iterative name resolution technique:**
    - **Iterative Name Resolution** is a DNS (Domain Name System) resolution method where a DNS client queries multiple DNS servers in a step-by-step fashion until it obtains the desired information or an authoritative server is reached. Each server queried provides a referral to the next server until the resolution is complete.

12. **Write a short note on Process Resilience:**
    - **Process Resilience** refers to a system's ability to maintain its functionality and recover from failures in individual processes. Resilient processes can handle faults, restart if necessary, and continue providing their services to the overall system.

13. **Explain Firewall in detail:**
    - A **Firewall** is a network security device or software that monitors and controls incoming and outgoing network traffic based on predetermined security rules. It acts as a barrier between a trusted internal network and untrusted external networks, filtering and blocking or allowing traffic based on specified criteria. Firewalls are crucial for protecting networks from unauthorized access, cyber attacks, and other security threats.

14. **What is RMI (Remote Method Invocation)? Explain briefly:**
    - **RMI (Remote Method Invocation)** is a Java-based framework that allows methods of remote objects to be invoked from other Java Virtual Machines (JVMs), possibly on different physical machines. RMI enables communication between distributed Java applications, providing a mechanism for remote procedure calls.

15. **What is CORBA? Explain briefly:**
    - **CORBA (Common Object Request Broker Architecture)** is a middleware that enables communication between objects in a distributed computing environment. It provides a platform-neutral, language-agnostic architecture for creating and using distributed objects. CORBA uses an Object Request Broker (ORB) to facilitate communication between distributed objects, allowing them to invoke methods and exchange data seamlessly across different languages and platforms.

16. **Explain advantages and disadvantages of distributed systems:**

   **Advantages:**
   - **Resource Sharing:** Efficient utilization of resources across the network.
   - **Reliability:** Improved reliability through redundancy and fault tolerance.
   - **Scalability:** Ability to scale horizontally to accommodate growing demands.
   - **Performance:** Enhanced performance through parallel processing and load balancing.
   - **Flexibility:** Integration of diverse hardware and software platforms.

   **Disadvantages:**
   - **Complexity:** Designing, implementing, and managing distributed systems can be complex.
   - **Security:** Security challenges arise with the need to protect communication and data across the network.
   - **Consistency:** Ensuring consistency in distributed data can be challenging.
   - **Cost:** Distributed systems may incur higher costs in terms of development and maintenance.
   - **Maintenance:** Ongoing maintenance and updates can be more complex than in centralized systems.

17. **Discuss flat and structured naming with an example:**

   - **Flat Naming:** In a flat naming system, each entity (file, resource) has a unique name within the entire system. Example: Each file in a directory must have a unique name.

   - **Structured Naming:** In a structured naming system, names are organized hierarchically. Example: A file path in a directory structure, like "/home/user/documents/file.txt."

18. **Give some examples of true identifiers:**

   - Examples of true identifiers include:
     - Social Security Numbers (SSN).
     - Vehicle Identification Numbers (VIN).
     - International Mobile Equipment Identity (IMEI) numbers for mobile devices.
     - Employee ID numbers.

19. **Write a short note on digital signature:**

   - A **digital signature** is a cryptographic technique used to verify the authenticity and integrity of a digital message or document. It involves using a private key to generate a unique digital signature, which can be verified by anyone who has access to the corresponding public key. Digital signatures are used for ensuring the origin, identity, and non-repudiation of digital messages or documents.

20. **Discuss persistent and non-persistent HTTP connection:**

   - **Persistent HTTP Connection:** In a persistent connection, the client and server keep the connection open after the initial request and response, allowing multiple requests and responses to be sent over the same connection. This reduces the overhead of opening and closing connections for each request.

   - **Non-persistent HTTP Connection:** In a non-persistent connection, a new connection is established for each request, and it is closed as soon as the response is delivered. This approach incurs the overhead of connection establishment for each request, especially for multiple small requests.

21. **Explain causal consistency:**

   - **Causal Consistency:** Causal consistency is a consistency model in distributed systems that ensures a causal relationship between related events is preserved. In other words, if one operation causally affects another, the system guarantees that the order of these operations is maintained. However, operations that are not causally related may be seen in different orders by different nodes.

22. **Discuss different alternatives of client-server organization:**

   - **Two-Tier Architecture:** Involves a client directly communicating with a server. Suitable for small-scale applications.

   - **Three-Tier Architecture:** Introduces an intermediate application server between the client and the data server. Enhances scalability and modularity.

   - **N-Tier Architecture:** Involves multiple layers, each serving a specific purpose. Can include presentation, application, business, and data tiers. Offers flexibility and scalability for large and complex systems.

   - **Peer-to-Peer (P2P):** All nodes in the network have equivalent capabilities and responsibilities. Suitable for decentralized and distributed applications. Examples include file-sharing networks.