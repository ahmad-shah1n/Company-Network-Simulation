# Company-Network-Simulation
This project simulates the internal network infrastructure of a company with two branches: one located in Cairo and the other in Alexandria. The simulation has been developed using Cisco Packet Tracer and represents a comprehensive setup of network devices, configurations, and security measures.

Overview
Each branch is equipped with its own set of servers and network devices, meticulously configured to replicate a real-world corporate environment. The network infrastructure supports various services including DHCP, DNS, Web, and IoT. Each floor within the branches has been segmented using VLANs to separate and secure different groups of devices, ensuring that IT and private networks operate independently.

Key Features
VLAN Segmentation: Devices on each floor are grouped using VLANs to enhance security and network management. This includes separating IT-related devices from other users, ensuring data privacy and reducing broadcast traffic.

IoT Integration: IoT devices are connected to the network via Access Points, which are in turn connected to a central server responsible for managing IoT functions like fire detection, smoke alarms, and lighting. These Access Points also provide Wi-Fi connectivity to mobile devices such as smartphones and laptops.

Router Configuration and Security: Routers in both branches are configured with username and password protection at each stage of the configuration process. The OSPF (Open Shortest Path First) protocol is used for routing between the branches, ensuring efficient and secure data transfer. Additionally, network security is reinforced using firewalls or Access Control Lists (ACLs).

Switch Configuration: Switches on each floor are individually configured with device names, usernames, and passwords to control access to the network configuration. This ensures that only authorized personnel can modify network settings.

Branch Interconnection: The two branches are interconnected, allowing seamless communication and data transfer between the Cairo and Alexandria locations.

Network Services
DHCP: Dynamic Host Configuration Protocol is used for dynamically assigning IP addresses to devices in the network.
DNS: Domain Name System services are provided to resolve domain names to IP addresses within the network.
Web Server: A web server is set up to host and manage the company’s internal and external web resources.
IoT Server: Manages IoT devices across both branches, ensuring proper functionality and monitoring.
Security Measures
User Authentication: Each device, including switches and routers, is secured with a unique username and password to prevent unauthorized access.
VLAN Security: VLANs are implemented to isolate different groups of devices, ensuring that sensitive data is protected.
Firewall and ACL: Firewalls and ACLs are used to control traffic entering and exiting the network, providing an additional layer of security.
Conclusion
This simulation represents a robust and secure network infrastructure for a company with multiple branches. By leveraging VLANs, IoT integration, and advanced routing protocols, the network ensures efficient and secure communication across all devices and locations.
