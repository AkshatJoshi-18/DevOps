## IP Subnetting:

- Subnetting means dividing a relatively large network into smaller subnetworks, or subnets. It involves creating subnets with their unique network addresses and configuring them to work together as a single network.
  
<br>

 ![image](/resources_img/Networking/subnet%20and%20cidr/Subnetting.png)
<br>

- **Subnetting is essential in DevOps networking because it helps in the following ways :**

    - ***Allocating IP addresses efficiently :***
        Dividing a network into smaller subnets enables more efficient assignment of IP addresses, reducing the wastage of addresses.
    - ***Enhancing network security :***
        Subnetting can help improve network security by isolating sensitive resources and limiting access.
    - ***Improving network performance :***
        Dividing a network into smaller subnets enables more efficient traffic management. Thus, reducing network congestion and enhancing network performance.

<br>

- In IP addressing, the host portion refers to the part of the IP address used to identify a specific device within a network. The network portion of an IP address identifies the network to which the device is connected.
<br>

- **Subnet mask**:
    - The subnet mask is a numerical value that identifies network and host portions of an IP address. It consists of 32 bits and establishes the boundaries of the network and the devices that belong to it.
    - The representation of a subnet mask is similar to that of an IP address.
    - For example, a subnet mask of 255.255.255.0 indicates that the first three octets represent the network portion of the address, while the last octet represents the host portion.

<br>

- **Network ID:**
    - The network ID is part of an IP address that identifies the network to which the host belongs.
    - Applying the subnet mask to the IP address gives us the network address.
    - For example, for the IP address 192.168.1.10 and the subnet mask 255.255.255.0, the network ID is 192.168.1.0.
  
  <br>

- **Host ID:**
    - The host ID portion of an IP address specifies the particular device on a network.
    - To obtain it, take the IP address and apply a mask to remove the network ID.
    - E.g., the host ID is 0.0.0.10 for the IP address 192.168.1.10 and the subnet mask 255.255.255.0.

<br>

- **CIDR notation:**
    - CIDR (Classless Inter-Domain Routing) notation is a shorthand method of representing the subnet mask.
    - It consists of the IP address followed by a slash (/) and the number of bits in the subnet mask.
    - E.g., 192.168.1.0/24 represents a network with a subnet mask of 255.255.255.0.


## CIDR:

- In DevOps networking, CIDR is a method used to allocate and manage IP addresses more efficiently. Below is a brief explanation
- CIDR enables variable-length subnet masks to create subnets of different sizes within a network.
- CIDR, denoted by a slash followed by a number, determines the network portion of an IP address using the subnet mask. For example, a subnet mask of /24 would create a network with 256 addresses, while a subnet mask of /25 would result in a network with 128 IP addresses.
- CIDR helps to conserve IP addresses by allowing organizations to create smaller subnets, which can be allocated to devices only as needed, rather than assigning larger blocks of IP addresses that may go unused.
- CIDR also enables easier route summarization, thus reducing the size of routing tables and improving network performance.
- CIDR calculates the number of hosts and networks available in a subnet.
- The following table shows some common CIDR notations and their corresponding subnet masks:

<br>

![image](/resources_img/Networking/subnet%20and%20cidr/cidr.png)

<br>

***In DevOps networking, CIDR is used with IP subnetting to create efficient and scalable network architectures.***