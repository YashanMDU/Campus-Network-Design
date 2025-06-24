#  GoldenWings University Network Design & Configuration

A comprehensive network infrastructure project for **GoldenWings University**, designed and implemented using **Cisco Packet Tracer**. This project simulates a real-world, enterprise-grade network environment across a multi-building university campus, with secure routing, VLAN segmentation, and scalability in mind.

<img width="1142" alt="Diagram" src="https://github.com/user-attachments/assets/0126c7a7-327e-4656-ab06-fbb51de76d0a" />

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

## Cloud_Server_Ping
 <img width="1435" alt="Cloud_Server_Ping" src="https://github.com/user-attachments/assets/0ee28754-fcf6-4118-940a-b1b3f238e61a" />
 
## End_Devices_Ping
<img width="1428" alt="End_Devices_Ping" src="https://github.com/user-attachments/assets/90c600d7-1ee7-4629-80d5-b099d55b791d" />

## CDP_Neighbors
<img width="1439" alt="CDP_Neighbors" src="https://github.com/user-attachments/assets/0e214b97-9639-4c9f-8130-6a8636df8baf" />

## FTP_Server_Access
<img width="1076" alt="FTP_Server_Access" src="https://github.com/user-attachments/assets/5b80250b-bb65-4577-a3f8-268fd42f88ef" />

## Web_Server_Access
<img width="1419" alt="Web_Server_Access" src="https://github.com/user-attachments/assets/fb73553f-6f84-4b37-938b-c44c4a19dae4" />

## Port_Security
<img width="929" alt="Port_Security" src="https://github.com/user-attachments/assets/709a82b9-848b-407d-b7dc-1bb2b925e184" />


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


