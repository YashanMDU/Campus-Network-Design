#  GoldenWings University Network Design & Configuration

A comprehensive network infrastructure project for **GoldenWings University**, designed and implemented using **Cisco Packet Tracer**. This project simulates a real-world, enterprise-grade network environment across a multi-building university campus, with secure routing, VLAN segmentation, and scalability in mind.

---

##  Project Overview

This repository features a complete dual-campus network design tailored for GoldenWings University. It applies industry-standard practices and tools to model a secure, reliable, and efficient educational network environment.

---

## Network Architecture

### 📍 Main Campus
- **Building A**: Administrative , HR , Finance and Business Faculty 
  - VLANs for HR, Management, Finance  and Business Faculty
  - Router-based DHCP for dynamic IPs
- **Building B**: Faculty of Engineering & Computing, Art & Design
- **Building C**: Student Labs + IT Department  
  - Hosts university web servers and internal services

### 📍 GoldenWing's Branch Campus
- **Faculty of Health & Sciences**  
  - Isolated networks for staff and students using VLANs

---

## Technical Implementation

### Core Features
- **VLAN Segmentation**: Isolates departments and enhances security
- **Dynamic Routing (EIGRP)**: Enables scalable internal routing
- **Static Routing**: Configures external server access (Web server , FTP and Email Server)
- **DHCP Services**: Dynamic IP addressing from routers (For vlan 10 t0 100)
- **Switch Security**: Prevents unauthorized access at port level (Port Security Implemented)
- **Scalable Topology**: Designed for modular expansion

###  Network Components
- VLAN-enabled Core and Access Switches
- Layer 3 Routing Between Departments
- Packet Tracer-based Connectivity Testing
- External Cloud-based Email Server Integration

---

##  Requirements Fulfilled

- ✅ Multi-building campus network  
- ✅ IP segmentation by department  
- ✅ VLAN creation & inter-VLAN routing  
- ✅ RIPv2 routing protocol configuration  
- ✅ DHCP server setup  
- ✅ Layer 2 and Layer 3 security practices  
- ✅ External network connectivity  

---

##  Tools & Technologies

- **Cisco Packet Tracer** – Network simulation
- **Routing Protocols** – RIPv2, Static Routes
- **Network Services** – DHCP, DNS
- **Security Features** – Port Security, VLAN ACLs

---

## Repository Contents

- Packet Tracer project file 
- Network design documentation
- IP and Subnet Plan 
- Connectivity testing results  

---

##  Learning Outcomes

Through this project, the following skills and knowledge areas are demonstrated:

- Enterprise-level campus network design  
- VLAN and IP subnetting implementation  
- Routing protocol deployment and testing  
- Network service configuration  
- Infrastructure security best practices  
- Hands-on experience with Cisco devices and tools  

---


