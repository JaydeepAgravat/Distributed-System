# 3-marks

1. **What is a distributed system? How does a distributed system project a single system image?**

   - **Distributed System:** A distributed system is a collection of independent computers that communicate and coordinate their actions to achieve a common goal. These systems can be located in the same physical space or be spread across different locations. The primary goal of a distributed system is to provide users with access to resources, data, and services, as if they were all part of a single, unified system.

   - **Single System Image:** Projecting a single system image in a distributed system means presenting the users and applications with the illusion of a single, cohesive computing environment, even though the underlying resources are distributed. This involves mechanisms such as transparency, where users are unaware of the physical location of resources or the distribution of processes.

2. **List out the various characteristics of a distributed system:**

   - **Concurrency:** Multiple components can execute concurrently.
   - **Transparency:** Users and applications perceive the system as a single entity.
   - **Scalability:** The system can easily accommodate a growing number of users or resources.
   - **Fault Tolerance:** The system continues to function in the presence of faults or failures.
   - **Interoperability:** Different types of hardware and software can work together.
   - **Resource Sharing:** Components share resources such as data, processing power, and storage.
   - **Heterogeneity:** The system may consist of diverse hardware and software platforms.

3. **Compare: Network Operating System and Distributed Operating System:**

   - **Network Operating System (NOS):**
     - Manages and supports network resources (printers, file systems) for client machines.
     - Focuses on facilitating communication and resource sharing among connected devices.

   - **Distributed Operating System (DOS):**
     - Extends the capabilities of a single machine to a distributed environment.
     - Manages resources across multiple machines as a unified whole.

4. **What is flat naming and structured naming?**

   - **Flat Naming:** In a flat naming system, each entity (like a file or a resource) has a unique name within the entire system. There is no hierarchy or structure to the names.

   - **Structured Naming:** Structured naming involves organizing names hierarchically, creating a structure that reflects the organization of the system. This structure can simplify naming and improve organization.

5. **Define IPC. What are the characteristics of IPC?**

   - **IPC (Inter-Process Communication):** IPC refers to the mechanisms and techniques used by processes to communicate with each other, either within the same computer or across a network.

   - **Characteristics of IPC:**
     - **Synchronization:** Processes can synchronize their actions.
     - **Communication:** Processes can exchange data and information.
     - **Cooperation:** Processes can collaborate to achieve a common goal.
     - **Data Sharing:** Processes can share data efficiently and securely.

6. **What is cryptography? What is the use of cryptography?**

   - **Cryptography:** Cryptography is the practice and study of techniques for securing communication and data against adversaries. It involves techniques such as encryption, decryption, and key management.

   - **Use of Cryptography:**
     - **Confidentiality:** Protecting information from unauthorized access.
     - **Integrity:** Ensuring that data remains unaltered during transmission or storage.
     - **Authentication:** Verifying the identity of communicating parties.
     - **Non-repudiation:** Ensuring that a party cannot deny the authenticity of their communication.

7. **What is multicasting? List the characteristics of multicasting:**

   - **Multicasting:** Multicasting is the process of transmitting data to a selected group of recipients in a network rather than broadcasting it to all nodes.

   - **Characteristics of Multicasting:**
     - **Selective Delivery:** Data is delivered to a specific group of recipients.
     - **Efficiency:** Optimizes bandwidth usage by avoiding unnecessary duplication of data.
     - **Scalability:** Well-suited for applications with large and dynamic groups of recipients.

8. **Difference between Authorization and Authentication:**

   - **Authentication:** Authentication is the process of verifying the identity of a user, system, or entity. It ensures that the entity trying to access a resource is who it claims to be. Common methods include passwords, biometrics, and cryptographic keys.

   - **Authorization:** Authorization comes after authentication and involves granting or denying access rights and permissions to a user or system. It specifies what actions or resources an authenticated entity is allowed to access. Access control lists and permissions are used for authorization.

9. **What is a distributed system? List out the advantages of a Distributed System:**

   - **Distributed System:** A distributed system is a collection of independent computers that communicate and coordinate their actions to achieve a common goal. It allows for the distribution of tasks across multiple interconnected machines.

   - **Advantages of Distributed Systems:**
     - **Resource Sharing:** Efficient sharing of resources like files, printers, and processing power.
     - **Reliability:** Improved reliability through redundancy and fault tolerance.
     - **Scalability:** Easily scalable to accommodate growing user or resource demands.
     - **Performance:** Enhanced performance through parallel processing and load balancing.
     - **Flexibility:** Allows for the integration of diverse hardware and software.
     - **Cost Efficiency:** Can be more cost-effective than centralized systems.

10. **Define Remote Procedure Call (RPC), Virtualization, Replication:**

    - **Remote Procedure Call (RPC):** RPC is a protocol that one program can use to request a service from a program located on another computer in a network. It allows programs to execute procedures or routines on a remote server as if they were local.

    - **Virtualization:** Virtualization is the process of creating a virtual (rather than actual) version of something, such as a virtual machine (VM), virtual storage, or virtual network resources. It enables multiple operating systems or applications to run on a single physical machine.

    - **Replication:** Replication involves creating and maintaining copies of databases, files, or entire systems to ensure data consistency, availability, and fault tolerance. Replication can be used to improve performance and reliability.

11. **Define identifiers, names, and addresses:**

    - **Identifiers:** Identifiers are symbols or names used to uniquely identify a program element, such as variables, functions, or objects, within a program. They are essential for referencing and manipulating these elements in the code.

    - **Names:** Names are labels or identifiers given to entities, including files, variables, functions, etc. Names are used to reference and access these entities.

    - **Addresses:** Addresses are numerical or symbolic values assigned to identify a location in memory or a location in a network. In the context of networking, addresses are used to locate devices on a network, such as IP addresses.

12. **What is multicasting? List the characteristics of multicasting:**

    - **Multicasting:** Multicasting is the process of transmitting data to a selected group of recipients in a network rather than broadcasting it to all nodes.

    - **Characteristics of Multicasting:**
      - **Selective Delivery:** Data is delivered to a specific group of recipients.
      - **Efficiency:** Optimizes bandwidth usage by avoiding unnecessary duplication of data.
      - **Scalability:** Well-suited for applications with large and dynamic groups of recipients.

13. **What is a digital signature? Explain briefly:**

    - **Digital Signature:** A digital signature is a cryptographic technique used to verify the authenticity and integrity of a digital message or document. It involves using a private key to generate a unique digital signature, which can be verified by anyone who has access to the corresponding public key.

14. **What is Denial of Service? Explain briefly:**

    - **Denial of Service (DoS):** Denial of Service is a cyber-attack where the attacker aims to make a computer or network resource unavailable to its intended users by overwhelming it with a flood of illegitimate requests or traffic. The goal is to disrupt the normal functioning of the targeted system.

15. **Discuss Non-persistent HTTP connection briefly:**

    - **Non-persistent HTTP Connection:** In a non-persistent or short-lived HTTP connection, a new connection is established for each request and is closed as soon as the response is delivered. This approach contrasts with persistent connections, where the connection remains open for multiple requests.

    - **Characteristics:**
      - **Efficiency:** Quick setup and teardown of connections, suitable for small amounts of data.
      - **Resource Savings:** Minimizes the use of resources on both the client and server.
      - **Overhead:** Incurs overhead in terms of connection establishment for each request, especially for multiple small requests.

16. **Explain how simple client-server communication is done:**

   - In simple client-server communication, the client and server are two separate entities that communicate over a network. Here's a basic overview:
   
      - **Client:** Initiates the communication by sending a request to the server. The request typically includes information about the action it wants the server to perform.
      
      - **Server:** Listens for incoming requests. Upon receiving a request, it processes the request and sends a response back to the client.
      
      - **Communication:** This interaction is typically based on a client-server protocol (e.g., HTTP for web communication). The client and server may use sockets to establish a connection for data exchange.

   - For example, in a web scenario, a client (web browser) sends an HTTP request to a server (web server) asking for a specific resource, and the server responds with the requested data.

17. **Briefly explain scalability in a distributed system:**

   - **Scalability:** Scalability in a distributed system refers to its ability to handle an increasing amount of work or growth efficiently. It can be achieved through two main types:

     - **Vertical Scalability:** Involves adding more resources (CPU, RAM) to a single machine to handle increased load.
     - **Horizontal Scalability:** Involves adding more machines to a distributed system to distribute the load.

   - A scalable system should be able to maintain or improve its performance as the number of users or the volume of data increases.

18. **Discuss cryptography in brief:**

   - **Cryptography:** Cryptography is the practice and study of techniques for securing communication and data. It involves using mathematical algorithms to transform information into a format that is unreadable without the appropriate decryption key.

   - **Objectives of Cryptography:**
     - **Confidentiality:** Ensuring that information is kept secret from unauthorized users.
     - **Integrity:** Verifying that data has not been altered during transmission or storage.
     - **Authentication:** Confirming the identity of the parties involved in communication.
     - **Non-repudiation:** Ensuring that a sender cannot deny the authenticity of their message.

19. **Explain the term availability and reliability:**

   - **Availability:** Availability is a measure of the time a system is operational and accessible for use. It is usually expressed as a percentage and represents the reliability of a system to be available when needed.

   - **Reliability:** Reliability is the ability of a system to consistently perform a specified function without failure over time. It is a measure of the system's dependability and consistency in delivering its intended functionality.

20. **Define happened before relation:**

   - **Happened Before Relation:** In the context of distributed systems, the "happened before" relation is a partial order that defines the causal relationship between events. If event A happened before event B, there is a causal connection, meaning A influenced B directly or indirectly.

   - This relation is crucial for understanding the order of events in a distributed environment and is often used in the context of Lamport timestamps and vector clocks.

21. **Define names, identifiers, and addresses:**

   - **Names:** Labels or identifiers given to entities (files, variables, etc.) to reference and access them.

   - **Identifiers:** Symbols used to uniquely identify program elements (variables, functions) within a program.

   - **Addresses:** Numerical or symbolic values assigned to identify a location in memory or on a network. In networking, addresses are used to locate devices, e.g., IP addresses.