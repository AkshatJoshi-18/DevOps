## TCP / IP :

- TCP/IP is a set of communication protocols that allow computers to communicate over the internet.

## What is TCP/IP, and How is it Different from OSI :

- TCP/IP is the most widely used networking protocol suite in DevOps networking. It provides a reliable, connection-oriented communication model for transmitting data between devices.

- ### Here are some salient points about TCP/IP:
  - Here are some salient points about TCP/IP:
    - TCP, which provides reliable and ordered delivery of data, and
    - IP that provides routing and addressing capabilities.
  
  - TCP/IP is responsible for breaking data into packets, routing those packets to their destination, and reassembling them into their original form.
  
  - It is a four-layered model, and the four layers are:
    - **Network Interface Layer:**
       This layer transmits data over a physical network, including hardware addressing, error detection, and media access control.

    - **Internet Layer:**
      The responsibility of this layer is to address and route data packets among devices situated on distinct networks.

    - **Transport Layer:**
        Provides end-to-end data transport services, including error detection, flow control, and congestion control.

    - **Application Layer:**
        This layer deals with the protocols and processes that applications use to communicate with each other over the internet.

     ![image](/resources_img/Networking/tcp\IP/TcpIp_with_protocols.png)


  - **Difference between TCP/IP and OSI Model:**
    - In DevOps networking, while both TCP/IP and OSI are used to facilitate communication between computer systems, there are differences between the two models.

    - **Number of Layers:**
       TCP/IP has four layers, while OSI has seven layers.

    - **Functionality:**
      The layers in TCP/IP are more focused on specific tasks, while the layers in OSI are more generalized

    - **Implementation:**
      TCP/IP is a practical implementation of networking protocols, while OSI is more of a theoretical framework.

    - **Widely Used:**
      TCP/IP is a suite of protocols used for communication over the internet, while OSI is a conceptual model that describes the communication between different systems in a network.

    ![image](/resources_img/Networking/tcp\IP/Layer_Protocol_tcpip%20Model.png)


## TCP versus UDP :

- TCP and UDP are two widely used transport layer protocols in DevOps networking. While both are responsible for delivering data between applications, they differ significantly in how they operate. Here are some of the main differences between TCP and UDP:

- **Connection-Oriented vs. Connectionless**
    
    - TCP is a connection-oriented protocol. It establishes a reliable and secure connection between two endpoints before exchanging data. It ensures that data is transmitted without errors and in the correct order.

    - In contrast, UDP is a connectionless protocol. It does not establish a dedicated connection before sending data. Rather than ensuring the delivery of data packets to the recipient, UDP transmits them without any guarantees about their successful delivery.

- **Reliability vs. Speed**
  - TCP ensures reliable data delivery through mechanisms like error detection, flow control, and retransmission, but this can slow down transmission.

  - UDP prioritizes speed over reliability, lacking mechanisms for error detection or retransmission, resulting in lost or out-of-order packets, but enabling faster data transmission than TCP.
 
- **Suitability for Connection and Data Size :**
  - TCP is suited for long-lived connections with a small amount of data sent in single bursts.
  
  - UDP, for short-lived connections with a huge amount of data sent in a single burst.

- **Acknowledgment and Retransmission :**
  - The receiver acknowledges TCP segments and requests their retransmission if not received.
  
  - UDP does not guarantee packet delivery or retransmission.

- **Flow and Congestion Control :**

  - In DevOps networking, TCP uses flow and congestion control mechanisms to prevent network congestion and ensure reliable data transmission, while UDP does not.

- **Usage Scenarios :**
  - TCP, for applications that require reliable and ordered delivery of packets, such as email, file transfer, and web browsing.
  
  - UDP, for applications that can tolerate packet loss, such as video streaming and online gaming.


## Ports and Protocols :

- In DevOps networking, ports and protocols identify different applications and services on a network.

- ### Ports :
    
    - A port is a communication endpoint for identifying specific applications and services running on a device by network protocols.
    
    - **In DevOps networking, this is what you need to know about ports:**
      
      - Ports can be blocked or opened using firewall rules to control network traffic and improve security.

      - Port scanning is a technique to identify open ports on a device or network.
      
      - **The numbering of ports ranges from 0 to 65535. There is a division of ports into three ranges:**
        
        - Well-known ports (0-1023)
        
        - Registered ports (1024-49151)
        
        - Dynamic or private ports (49152-65535)

      - Well-known ports are typically associated with services or applications, while, for temporary purposes, we use dynamic or private ports.

      ![image](/resources_img/Networking/tcp\IP/ports_IpAdress.png)

      - Well-known ports and protocols used in DevOps networking include:

        ![image](/resources_img/Networking/tcp\IP/ports_protocols.png)

- ### Protocols :
  - A protocol is a set of rules governing the communication between devices on a network.

  - **Some commonly used protocols in DevOps networking include:**

    ![image](/resources_img/Networking/tcp\IP/protocol_description.png)


- In summary, ports and protocols are crucial components of DevOps networking that facilitate communication between devices.