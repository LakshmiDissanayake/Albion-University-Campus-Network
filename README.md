# Albion University Campus Network Design and Configuration

## 📌 Project Overview

This project focuses on designing and configuring a multi-campus university network for **Albion University** using Cisco Packet Tracer.

The university has two campuses located approximately 20 miles apart. The network is designed to provide reliable communication between departments, staff members, student laboratories, internal servers, and external services.

The main objective is to create a structured, secure, and scalable network infrastructure using VLANs, IP addressing, routing protocols, and essential network services.

## 🎯 Project Objectives

- Design a network topology connecting two university campuses.
- Configure separate IP networks for different departments and faculties.
- Implement VLANs to logically segment the network.
- Configure inter-VLAN communication.
- Enable dynamic IP address allocation using DHCP.
- Implement RIP Version 2 for internal dynamic routing.
- Configure static routing for the external mail server.
- Provide connectivity between campus networks.
- Enable access to internal university servers and external services.

## 🏫 Network Architecture

The network consists of two main campuses.

### 1. Main Campus

The main campus contains three buildings.

**Building A – Administrative and Business Departments**
- Administration
- Human Resources (HR)
- Finance
- Business Faculty

**Building B – Academic Departments**
- Engineering and Computing Faculty
- Art and Design Faculty

**Building C – Student Laboratories and IT Department**
- Student Laboratory
- IT Department
- University Web Server
- FTP Server

An external cloud-based mail server is also included in the network design.

### 2. Branch Campus

The smaller campus consists of:

- Health and Sciences Faculty
- Staff Network
- Student Laboratory

The branch campus is connected to the main campus through a WAN connection.

## 🖥️ Technologies and Components Used

- Cisco Packet Tracer
- Routers
- Layer 3 Switch
- Layer 2 Switches
- PCs and End Devices
- Servers
- VLAN Configuration
- Inter-VLAN Routing
- RIP Version 2
- DHCP
- Static Routing
- WAN Connectivity
- IP Addressing and Subnetting

## 🌐 VLAN and IP Addressing Plan

The following VLAN structure is represented in the network topology.

| VLAN ID | Department / Network | IP Network |
|---|---|---|
| VLAN 10 | Administration | 192.168.1.0/24 |
| VLAN 20 | HR | 192.168.2.0/24 |
| VLAN 30 | Finance | 192.168.3.0/24 |
| VLAN 40 | Business | 192.168.4.0/24 |
| VLAN 50 | Engineering and Computing | 192.168.5.0/24 |
| VLAN 60 | Art and Design | 192.168.6.0/24 |
| VLAN 70 | Student Laboratory | 192.168.7.0/24 |
| VLAN 80 | Servers | 192.168.8.0/24 |
| VLAN 90 | Branch Staff | 192.168.9.0/24 |
| VLAN 100 | Branch Student Laboratory | 192.168.10.0/24 |

*Note: Confirm the VLAN assignments and IP networks against your final Packet Tracer configuration before submission.*

## ⚙️ Network Configuration

The project includes the following network configuration tasks:

1. VLAN creation and assignment.
2. Switch port configuration.
3. Trunk link configuration between switches and network devices.
4. Inter-VLAN routing.
5. RIP Version 2 configuration for internal routing.
6. DHCP configuration for Building A devices.
7. Static routing for external mail server connectivity.
8. WAN configuration between the main and branch campuses.
9. End-device IP configuration.
10. Network connectivity testing.

## 🖼️ Network Topology

The network topology illustrates the complete university network infrastructure, including the main campus, branch campus, departmental VLANs, servers, routers, and WAN connections.

The topology is designed to support communication between different university departments while maintaining logical network separation.

## 🧪 Testing and Verification

The following tests can be used to verify the network implementation:

- Verify IP address allocation using `ipconfig`.
- Test connectivity using `ping`.
- Verify VLAN assignments using `show vlan brief`.
- Verify trunk connections using `show interfaces trunk`.
- Check routing information using `show ip route`.
- Verify RIP configuration.
- Test communication between the main and branch campuses.
- Test access to internal servers and external services.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Designing enterprise-level network topologies.
- Understanding VLANs and network segmentation.
- Configuring routers and switches.
- Implementing dynamic routing.
- Understanding DHCP and static routing.
- Connecting geographically separated networks.
- Troubleshooting network connectivity issues.

## 👩‍💻 Project Information

**Project Name:** Albion University Campus Network Design and Configuration

**Tool:** Cisco Packet Tracer

**Project Type:** Computer Networking / Network Administration

📂 Project Files

[⬇️ Download Albion University Network (.pkt)](./Packet-Tracer-Project/Albion_University_Network.pkt)

[📸 View Screenshots Folder](./Screenshots)



⭐ This project demonstrates practical networking knowledge through the design and configuration of a multi-campus university network using Cisco Packet Tracer.
