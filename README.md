# Network-Security-2

## Table of Contents

  
# Network Topology  
_The topology diagram represents the simulated network configuration, provides an overview of the network devices and their interconnections._

<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/1c4baa76-8059-4f30-8ace-d1d28089c521" alt = "Network Topology Diagram" width="1300" height="510">


# Network Connectivity Map
_The network connectivity map illustrates the connectivity and relationships between different devices in the network. The map shows the physical connections between the devices, including the interfaces, IP addresses, and subnet masks used for communication. It helps to understand the overall network layout and aids in troubleshooting and maintaining the network infrastructure._

<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/fbb5e9c8-6736-4614-927f-d92202411756" alt = "Network Connectivity diagram" width="800" height="500">

# DNS Server

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/69d9ede2-7656-4ef4-bef2-59725a1ec9b8)

```
www.external-server.com is mapped to 20.20.20.45 address
www.hq-server.com is mapped to 9.9.9.9 address
www.hq-ftp.com is mapped to 192.168.3.163 address (Client access only)
```

# VPN Configuration

_ISAKMP protocol is used to establish and manage the Security Association(SA) between Branch and HQ-Edge routers. 
The encryption algo, hash algo, authentication method, DH key exchange group, and lifetime parameters are exchanged to setup a VPN connection_ 

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/5007753a-bc5f-499b-b7eb-be8f3daff7a4)
![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/383e64ea-332b-4aa2-b35d-2a3ed57d47ab)
![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/3959439b-b5c5-41e3-9424-b71afe750874)

_After establihing an inital secure relationship, IPsec protocol suite is used to provide secure communication over the network._

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/3db20016-d08a-475e-81b7-02d4b04db8f9)

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/600215b7-4d2f-45ea-a876-8865d0bc7904)

# ASA Firewall

_Class maps and Policy maps enable fine-grained control over traffic handling and security policies within the ASA firewall. Class map is used to classify traffic based on criteria, and policy map is used to define actions to be taken on the classified traffic._

<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/b84cc303-abe7-48ab-80c3-12468a4cb92b" alt = "Network Topology Diagram" width="800" height="680">

# NAT Translations
_Network Address Translation (NAT) enhances security by acting as a form of firewall. As the internal IP addresses are hiden behind a single IP address, external entities cannot directly initiate connection to devices within the private network. This obscurity adds a layer of security by reducing visibility of internal network structure._

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/a28ee053-db68-4ced-a149-9b0a7fe7785d)

# VLAN Segmentation

_VLANs reduce the scope of potential security threats by segmenting a physical network into isolated broadcast domains._

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/4ce83625-fcf2-4978-80e8-567619d8c6f9)

<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/eb98ed70-d008-4b8c-b2ac-37595eb7917d" alt = "Network Connectivity diagram" width="300" height="400">


# Access Lists
![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/4d395b8f-f351-47a1-a227-0967fb6f4ebc)

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/01eb2150-d28c-4a31-9d48-09b3eaeec3e2)

# Network Route
<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/bcd56ea0-a953-453f-81ab-b276a589fa8c" alt = "Network Topology Diagram" width="700" height="400">

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/4bdd4e0c-a12e-4c74-9bbd-89176d7d3720)

![image](https://github.com/Muneer44/Network-Security-2/assets/117259069/d8a2a624-cd8c-440a-8084-67dd4ebe8710)

# Connectivity tests

### Branch PC to HQ-FTP Server:
<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/b40d96cb-9d86-4558-8064-459c970ae202" alt = "Network Topology Diagram" width="620" height="500">

### Branch PC to HQ-Internal Web Server:
<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/4f85fdeb-8499-44a6-a552-e380e12c6805" alt = "Network Topology Diagram" width="720" height="300">

### VLAN-1 to External Web Server:
<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/ef290594-10df-4175-8aa7-702cc2782255" alt = "Network Topology Diagram" width="720" height="300">

### Branch PC to HQ Client PC:
<img src="https://github.com/Muneer44/Network-Security-2/assets/117259069/c01b0a3b-ad22-46ca-85e3-65e94464cd03" alt = "Network Topology Diagram" width="620" height="500">


