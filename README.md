# 🌐 Multi-Area OSPF Network Design & Implementation

### Cisco Packet Tracer | CCNA Networking Project

---

## 📌 Project Overview

This project focuses on designing and implementing a Multi-Area OSPF (Open Shortest Path First) network using Cisco Packet Tracer.

The network consists of multiple interconnected routers distributed across four OSPF areas, with Area 0 serving as the backbone area.

The main objective is to understand and implement dynamic routing, inter-area communication, and efficient IP addressing in a multi-area network environment.

## 🏗️ Network Architecture

The network is divided into four OSPF areas:

| OSPF Area | Description |
|---|---|
| Area 0 | Backbone Area |
| Area 17 | Regional Network |
| Area 25 | Regional Network |
| Area 30 | Regional Network |

The backbone area provides connectivity between the different OSPF areas through Area Border Routers (ABRs).

## 🛠️ Technologies & Concepts

- Cisco Packet Tracer
- OSPF Multi-Area Routing
- OSPF Backbone Area (Area 0)
- Area Border Routers (ABRs)
- IPv4 Addressing
- VLSM & Subnetting
- Wildcard Masks
- Dynamic Routing
- Inter-Area Communication
- Network Troubleshooting

## 🔧 Routing Implementation

OSPF is used as the dynamic routing protocol to exchange routing information between routers.

The implementation covers:

- Configuring OSPF on multiple routers.
- Assigning interfaces to different OSPF areas.
- Establishing OSPF neighbor relationships.
- Advertising connected networks.
- Enabling communication between different areas.

## 🧪 Network Verification

The following Cisco IOS commands are used to verify the network configuration and operation:

```cisco
show ip ospf neighbor
show ip route
show ip route ospf
show ip ospf interface brief
show ip protocols
```

Connectivity is also tested using ICMP (Ping) between end devices in different OSPF areas.

## 🎯 Project Objectives

- Understand OSPF Multi-Area architecture.
- Implement a backbone-based routing design.
- Practice IPv4 addressing and VLSM.
- Understand inter-area routing.
- Develop practical Cisco IOS configuration skills.
- Test and troubleshoot network connectivity.

## 💻 Simulation Environment

**Software:** Cisco Packet Tracer

**Routing Protocol:** OSPF

**IP Version:** IPv4

## 👨‍💻 Author

**Yousef Mahmoud**

Computer Science & Artificial Intelligence Student

Interested in Networking, Network Engineering, and Cybersecurity.

---

⭐ If you find this project useful, feel free to explore it!
