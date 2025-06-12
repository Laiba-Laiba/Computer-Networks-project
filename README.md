Computer Networks Project – Cisco Packet Tracer Simulation

This project is a detailed network simulation built using Cisco Packet Tracer (Instructor Version) as part of my Computer Networks coursework. The goal was to configure a complex network topology involving multiple blocks with different routing protocols, subnetting, and security rules. The design and implementation reflect real-world networking practices.

Each student was assigned a unique set of IP addresses and host requirements from an official IP address sheet. I calculated subnet addresses using VLSM (Variable Length Subnet Masking) to optimize IP usage, ensuring all networks and router-to-router links had the correct number of hosts.

The topology includes:

EIGRP, OSPF (Area 1 & 2), and RIP for dynamic routing between networks.

Route redistribution on routers that connect different routing domains.

A centralized DHCP server in Block D to assign IPs dynamically to all hosts across routing protocols.

NAT configured on Router21 and Router10 using a provided public IP address for each.

Security policies were enforced using Access Control Lists (ACLs). Specific hosts in Network A, Network E, and Network B were restricted from accessing the Web Server. Additionally, all hosts in Network D were denied Web Server access.

A Mail Server was configured in Block D, allowing email communication between hosts in Network H and Network I. Only Network G devices were granted access to the FTP Server, with permission to upload files — implemented through protocol-based filtering and port control.

The project follows strict academic integrity guidelines with no copying or reuse. All configurations, routing, subnetting, ACLs, and services were implemented independently.

This simulation demonstrates strong knowledge of networking fundamentals including IP addressing, dynamic routing, NAT, DHCP, ACLs, and service configuration in a simulated enterprise environment.

