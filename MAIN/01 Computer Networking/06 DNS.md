# Domain Name System (DNS) 

- DNS is a hierarchical and decentralized naming system for computers, services, or other resources connected to the internet or a private network.
<br>
- It is like a phonebook, converting human-readable domain names like `google.com` into IP addresses like 172.217.6.14, which computers use to identify each other.
<br>

### a. DNS Overview

- DNS is responsible for translating domain names into IP addresses, which computers can understand and use to communicate with each other.
<br>
- Here are some crucial points to know about DNS
<br>
- DNS is a distributed database that contains information about domain names and their associated IP addresses.
<br>
- When a user types a domain name into their web browser, the browser requests a DNS resolver to find the corresponding IP address.
<br>
- The DNS resolver then checks its cache for the IP address. If it does not have the IP address, it sends a request to a root server.
<br>
- The root server responds with the address of a top-level domain (TLD) server, which the DNS resolver then queries for the IP address of the domain name you entered.
<br>
- In DevOps networking, DNS operates at the application layer of the OSI model and uses the client-server model.
<br>
- In summary, DNS is a critical component in DevOps networking. DNS can also be a target for cyber attacks, and DevOps networking teams must implement appropriate security measures to protect against DNS-based attacks.
<br>

### b. Domains, Zones, and Delegation

- Domains, Zones, and Delegation are significant concepts in DevOps networking, particularly in the Domain Name System (DNS). Below we have a detailed overview of each of these concepts:
<br>

- **Domains:**
    <br>
    
    - Domains are a hierarchical way of organizing resources in a network.
    <br>
    - A domain name, such as `example.com`, represents a website or online service and can be subdivided into subdomains like `blog.example.com` or `store.example.com` to categorize or specify the services provided by the domain.
    <br>
    - DNS maps domains to IP addresses.
    <br>

        ![image](/resources_img/Networking/DNS/domain_map_to_ip.png)
    <br>

- **Zones:**
    <br>
    
    - Zones are a contiguous portion of the DNS namespace managed by a single entity, such as an organization or a DNS server.
    <br>
    - In DevOps networking, a domain name identifies each zone that stores information about the domain, including its authoritative name servers, mail servers, and other details.
    <br>
    - A zone can contain multiple domain names.
    <br>
        
        ![image](/resources_img/Networking/DNS/Zones.png)
    <br>

- **Delegation:**
<br>
    
    - Delegation means transferring the responsibility for managing a subdomain to another DNS server.
<br>
    - It is done when a domain owner wants to manage a subdomain on a separate server or delegate responsibility to a third-party provider.
<br>
        ![image](/resources_img/Networking/DNS/deligation.png)
    <br>

- In summary, domains, zones, and delegation are vital concepts in DNS and play a key role in organizing and managing resources on a network. Understanding these concepts is essential for effective DevOps networking.

<br>

### c. DNS Record Types
<br>

- DNS uses record types to store information about domain names and their associated IP addresses. The most common record types are:
<br>

![image](/resources_img/Networking/DNS/DNS_record%20_types.png)

- Consult the DNS server documentation and configuration guides to ensure specific applications use the correct record types,
<br>

 ***In summary, DNS is a critical part of the internet infrastructure, providing a way to translate human-readable domain names into machine-readable IP addresses. Understanding DNS is essential for DevOps networking professionals as it plays a vital role in network communication and application delivery.***
