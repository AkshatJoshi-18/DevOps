### Defination of OSI Model :
- The Open Systems Interconnection (OSI) model is a conceptual framework that describes how data moves through a network. OSI is a layered approach that defines seven layers, each with a specific function in the communication process.

- The OSI model is crucial in DevOps networking because it provides a common reference point for network architects, engineers, and administrators to design, implement, and troubleshoot networks.


### Layer 1: Physical Layer :

- The Physical layer is the first and bottom layer of the OSI model.
- It converts data into a stream of bits and transmits them over the physical network medium.
- It defines the physical characteristics of the network, such as the type of cable, connectors, and signaling methods used to transmit data.
- This layer establishes, maintains, and terminates physical connections between network devices.
- This layer in DevOps networking uses various communication channels, including copper wires, Wi-Fi, Bluetooth, and fiber optic cables.
- Topologies used at this layer include point-to-point, bus, star, mesh, and ring.
- This layer uses techniques such as encoding, modulation, and error detection and correction, to minimize the effects of interference and noise.
- Some protocols used in the layer include Ethernet, Wi-Fi, Bluetooth, USB, and HDMI.

![image](/resources_img/Networking/OSI_model/physical-layer-of-osi-model%20(3).png)


### Layer 2: Data Link layer :

- The Data Link layer is the second layer in the OSI model.
- It is responsible for providing error-free transfer of data frames between devices on the same network segment.
- It layer breaks down the data received from the Network layer into frames and adds a header and trailer to each frame, which contains control and addressing information.
- The Data Link layer transmits data over a local network and uses physical addresses (MAC addresses) to identify devices on the same network segment.
- This layer in DevOps networking provides services such as framing, error detection, and flow control to ensure the reliable transmission of data frames.
- Topologies used at this layer include point-to-point and broadcast.
- The protocols used in the layer include Ethernet, Token Ring, and FDDI.
- The medium used in this layer includes twisted pair copper wire, coaxial cable, and fiber optic cable.

![image](/resources_img/Networking/OSI_model/datalink_layer.png)


### Layer 3: Network Layer :

- The Network layer is the third layer in the OSI model.
- It is responsible for logically addressing and routing the data between different networks. Logical addressing is a method to identify a device or network node on a network.
- The function of this layer is to provide end-to-end communication between two hosts on different networks.
- This layer in DevOps networking receives data from the upper layers and adds a header that contains logical addressing information, such as IP addresses.
- The protocols used at this layer include Internet Protocol (IP), Internet Control Message Protocol (ICMP), and Internet Group Management Protocol (IGMP).
- The medium used at this layer includes routers and switches.
- The primary task of this layer is to provide routing services and enable data packets to travel across different networks using various routing algorithms.
- This layer helps manage congestion control by monitoring the network and managing the flow of data packets.

![image](/resources_img/Networking/OSI_model/network_layer.png)


### Layer 4: Transport Layer :

- The Transport layer is the fourth layer in the OSI Model.
- The function of this layer is to provide reliable end-to-end delivery of data between applications or hosts on different networks.
- This layer in DevOps networking takes the data segments received from the Session layer and breaks them down into smaller units, called packets, for transmission over the network.
- The layer is responsible for regulating the flow of data and controlling congestion, thereby preventing network overload.
- The medium used in this layer can be copper cables, fiber optic cables, or wireless communication.
- Some of the commonly used protocols in this layer are Transmission Control Protocol (TCP), User Datagram Protocol (UDP), and Stream Control Transmission Protocol (SCTP).

![image](/resources_img/Networking/OSI_model/transport_layer.png)


### Layer 5: Session Layer :

- The Session layer is the fifth layer of the OSI model.
- It establishes and manages sessions between applications on different devices.
- The Session layer in DevOps networking maintains the session state, keeping track of the conversation and data exchange.
- It allows for synchronized data exchange and recovery from communication failures.
- It may provide encryption, compression, and checkpoints to ensure the integrity of session data.
- It interacts with the Presentation and Transport layers.
- Protocols used in this layer are NetBIOS, RPC, and SQL.

![image](/resources_img/Networking/OSI_model/session_layer.png)


### Layer 6: Presentation Layer :

- The Presentation layer is the sixth layer of the OSI model, located between the Session and Application layers.
- Its primary function is to ensure that data exchanged between applications is presented in a standardized format, regardless of the underlying data format used by the applications.
- This layer performs data transformation, converting data from one format to another to ensure compatibility between applications.
- This layer in DevOps networking also performs encryption and decryption of data, thereby enabling secure data transmission over unsecured networks.
- Compression and decompression of data is another function of this layer, reducing the size of data to be transmitted and saving network bandwidth.
- Protocols used in this layer are JPEG, GIF, MPEG, ASCII, and EBCDIC.

![image](/resources_img/Networking/OSI_model/presentation_layer.png)


### Layer 7: Application Layer :

- The Application layer is the top layer in the OSI model.
- In this layer, user applications interact with the network.
- Its primary function is to provide a user interface and services that allow applications to exchange information with other devices on the network.
- This layer in DevOps networking supports a range of network applications, including email, web browsing, file transfer, and remote access.
- Applications at the top layer use standardized protocols such as HTTP, FTP, SMTP, and Telnet to communicate with each other.
- This layer handles application-specific functions like message formatting, file compression, and user authentication.
- It interacts with all the lower layers to transmit data across the network.

![image](/resources_img/Networking/OSI_model/application_layer1.png)

<br>

**Understanding the OSI model and its seven layers is essential for a professional working in DevOps networking. Here is an image for a better understanding:**

<br>

![image](/resources_img/Networking/OSI_model/OSI_understanding.png)