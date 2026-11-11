[github_readme.md](https://github.com/user-attachments/files/34672512/github_readme.md)
# 🏨 Premier Hotel Smart Network & IoT Infrastructure

A comprehensive enterprise-grade 5-floor hotel network simulation developed using Cisco Packet Tracer. The project integrates core network engineering principles, strict security protocols, and centralized IoT automation to deliver a secure and modern digital hospitality experience.

## 📖 Overview
Traditional hotel networks often maintain separate infrastructures for IT data, guest Wi-Fi, and room appliances. This project introduces a converged smart network where guest internet access, secure administrative data, and IoT room automation coexist on a single managed infrastructure. 

The system is designed to improve network efficiency, ensure strict data privacy for hotel accounts, and elevate the guest experience through automated smart room features.

## 🚀 Features

### 🔐 Network Security & Access Control
- VLAN Segmentation (Guest, Accounts, Server Room)
- Access Control Lists (ACL)
- Traffic Restriction (Blocking Guest VLAN from Accounts)
- WPA2 Secured Wireless Infrastructure

### 🌐 Core Routing & Switching
- 5-Router Core Topology
- OSPF (Open Shortest Path First) Dynamic Routing
- Inter-VLAN Routing (Router-on-a-Stick)
- Serial DCE/DTE WAN Link Simulation

### 🏠 Smart IoT Automation
- Centralized IoT Server Management
- Motion-Triggered Smart Lighting
- Temperature-Controlled Smart AC 
- RFID Smart Door Locks
- Custom Automation Conditions (If-Then Rules)

### 💻 Internal Server Infrastructure
- DNS & Web Server (Hotel Intranet)
- Internal Email Server (SMTP/POP3)
- DHCP Server for Automatic Guest IP Assignment
- Centralized Network Management

## 🏗️ System Architecture
The project follows a Hierarchical Network Design:

- **Core Layer:** 5 Interconnected Routers forming the backbone via Serial WAN connections with synchronized clock rates.
- **Distribution/Floor Layer:** Dedicated Layer 2 Switches for each floor/department with VLAN tagging and broadcasting control.
- **Access Layer:** End devices including Reception PCs, Accounts Workstations, Guest Smartphones, Wireless Access Points (WAP), and IoT Smart Devices.

## 🛠️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **Cisco Packet Tracer** | Network Simulation & Design |
| **OSPF (Process 10)** | Dynamic Routing Protocol |
| **VLSM (IPv4)** | IP Addressing & Subnetting |
| **VLAN & ACL** | Network Segmentation & Security |
| **IoT Gateway/Server** | Smart Device Automation |
| **HTTP / DNS / SMTP** | Internal Web & Mail Services |

## 📱 Simulated Zones Included
- Central Server Room
- Reception & Front Desk
- Accounts Department (Secure Zone)
- Guest Floor 1 (Smart Rooms)
- Guest Floor 2 (Smart Rooms)
- Guest Floor 3 (Smart Rooms)

## 🎯 Objectives
- Create a structured and scalable network topology.
- Improve data privacy using Access Control Lists (ACL).
- Provide automatic IP provisioning via DHCP.
- Enhance guest experience with IoT automation.
- Deliver a reliable internal communication system (Email/Intranet).

## ⚡ Advantages
- Enterprise-Grade Security
- Centralized IoT Control
- Automated and Scalable Routing
- Zero-Interference between Guest and Staff Networks

## 🔮 Future Enhancements
- IPv6 Dual-Stack Implementation
- Cloud Server Integration for Real-Time Booking/Billing
- WPA3-Enterprise Wireless Security
- Advanced Firewalls (ASA) Integration
- External ISP/NAT Configuration

## 📂 Project Structure
```text
project/
├── Premier_Hotel_Network.pkt      # Main Cisco Packet Tracer Simulation File
├── docs/
│   ├── Hotel_Network_Project_Proposal.pdf
│   └── Premier_Hotel_Network_Presentation.pptx
└── README.md
```

## 📑 Project Report
A detailed project report and topology documentation are available for further review, including IP addressing plans, DFD, OSPF tables, and IoT configuration scripts.

📥 **[View Full Project Report (PDF)](./Premier_Hotel_Report.pdf)**

## 📋 Project Management
To ensure efficient planning, topology design, and testing, our team coordinated the project workflow effectively.

**Workflow Structure**
- 📝 Topology Design
- 🚧 IP Addressing & Routing Configuration
- 🚧 Server & Services Setup
- 🚧 IoT Automation & Security (ACL)
- ✅ Testing (Ping/Email/IoT Triggers)
- ✅ Documentation & Presentation

## 👥 Team NetSync (Group 4)
| Name | Student ID | Role / Contribution |
| :--- | :--- | :--- |
| **Ifty Anwar** | **0222320005101192** | Scenario & Topology Design |
| **Sazib Hossain** | **0222320005101174** | VLSM, Routing & VLANs |
| **Santusti Biswas** | **0222320005101194** | Security (ACL), Wireless & IoT |
| **Mohammad Rayan** | **0222320005101186** | Testing & BAETE KP/CEP |

## 🎓 Academic Project
**Course:** Computer Networks  
**Department:** Computer Science & Engineering  
**Institution:** Premier University, Chattogram  

## 📚 References
- Cisco Networking Academy (NetAcad)
- OSPF & VLAN Configuration Guides
- Packet Tracer IoT Implementation Docs

## ⭐ Support
If you found this network simulation project useful, consider giving it a ⭐ Star on GitHub!

**Developed with by Team NetSync**
