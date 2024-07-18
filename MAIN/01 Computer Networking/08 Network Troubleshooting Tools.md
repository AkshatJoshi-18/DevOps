# Network Troubleshooting Tools

<br>

- In DevOps networking, network troubleshooting tools are essential for detecting and resolving issues on a network. Here are some of the most important ones:

## Ping:

- Ping tests network connectivity between two devices.

<br>

- Ping sends a request packet to the destination device, and if it receives a reply, it confirms that the two devices are connected.

<br>

- To use Ping, open a terminal window and type ping [IP address or hostname] for example, ping google.com 

<br>

![image](/resources_img/Networking/Network%20Troubleshooting%20Tools/ping.png)

<br>


## Traceroute:


- Traceroute is used to identify the path taken by packets to a destination host.

<br>

- Traceroute displays the IP addresses of all the hops in a route and provides information about response times. This information helps identify and troubleshoot network latency and routing problems in DevOps networking.

<br>

- To use Traceroute, run the traceroute [IP address or hostname] command in the command prompt. For example, traceroute google.com

<br>

![image](/resources_img/Networking/Network%20Troubleshooting%20Tools/trace_router.png)

<br>

## Netstat:

- Netstat shows network statistics for active connections.

<br>

- It displays the status of TCP and UDP ports and the IP addresses and ports of established connections.

<br>

- Netstat can be used to identify unauthorized connections and network usage.

<br>

- To use Netstat in DevOps networking, execute the netstat -a command in your terminal.

<br>

![image](/resources_img/Networking/Network%20Troubleshooting%20Tools/netstat.png)

<br>

## Nslookup:

- Nslookup is a command-line tool for querying DNS servers.

<br>

- In DevOps networking, this tool troubleshoots DNS problems by checking the IP address of a domain name and verifying the DNS records.

<br>

- It displays the IP address associated with the hostname and the hostname associated with the IP address.

<br>

- To use Nslookup, open a command prompt or terminal window and type nslookup [hostname or IP address] for example, nslookup google.com

<br>


## Nmap:

- Nmap is a network scanner to identify hosts and services on a network.

<br>

- It can detect open ports, operating systems, and other network characteristics.

<br>

- Nmap is for network mapping and security auditing.

<br>

- To use Nmap, open a terminal window and type, for example, to scan port 80 on a single host 192.168.1.1, execute the following command: nmap -p 80 192.168.1.1.

<br>

![image](/resources_img/Networking/Network%20Troubleshooting%20Tools/Nmap.png)

<br>


#### These are just some of the DevOps networking troubleshooting tools. Using these tools, network administrators can diagnose and resolve network problems, ranging from connectivity issues to security vulnerabilities.