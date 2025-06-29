# network-system-project

This repository contains the materials and configuration files for the Computer Networks project conducted as an alternative to midterm exams.
Project is done in **Cisco Packet Tracer**.

---

## Project Overview

The project focuses on designing and implementing a multi-site network with advanced features including IPv4/IPv6 addressing, routing protocols, VLANs, NAT, DHCP, ACLs, and server setups.

---

## Project Requirements

| Feature                              | Description                                                                                              | Points      |
|------------------------------------|----------------------------------------------------------------------------------------------------------|-------------|
| IPv4 Addressing                    | Design IPv4 subnetting using the smallest possible subnet sizes.                                         | 5           |
| BGP Routing                       | Implement EBGP routing between Router 8 and Router 9. Redistribution from IGP to EBGP required.          | 10 (5 w/o)  |
| VLANs                             | Create and configure at least 4 VLANs across the network.                                               | 5           |
| EtherChannel                     | Configure EtherChannel links for increased bandwidth and redundancy.                                     | 5           |
| Route Redistribution             | Implement routing redistribution including BGP integration.                                              | 5 (10 with BGP) |
| NAT                              | Configure Network Address Translation appropriately.                                                    | 10          |
| DHCP                             | Set up DHCP services with IP address pools.                                                             | 10          |
| Additional Fiber Links in ISP     | Add extra fiber links in the ISP network for redundancy/performance.                                    | 2           |
| ACLs for WWW and SMTP             | Define Access Control Lists to regulate web and mail traffic.                                           | 5           |
| Mail Server                      | Deploy a mail server accessible within the network.                                                     | 3           |
| IPv6 Addressing                  | Assign IPv6 addresses from the 2000::/3 range, with /64 prefixes for LANs and links.                     | 5           |
| IPv6 Routing with OSPFv3          | Configure OSPFv3 for IPv6 routing in a shared domain between ISP and Customer D.                        | Included    |
| WWW Server                      | Host a website accessible via IPv6.                                                                     | Included    |

---

## Network Diagram Requirements

Your diagrams must clearly show:

- IP addressing schemes (IPv4 and IPv6)  
- Device IP assignments  
- NAT address pools  
- VLAN IDs  
- DHCP pools  

---

## Additional Guidelines

- Use a public Class A IPv4 network for the ISP.  
- Assign a public Class C IPv4 network for Customer A.  
- For customers without public networks assigned, use private IPv4 addressing (RFC1918).  
- WWW servers for all customers must be reachable from any PC in the network.  
- Allocate VLANs appropriately for Customer B.  
- Feel free to add extra switches, links, or servers as necessary.

---
