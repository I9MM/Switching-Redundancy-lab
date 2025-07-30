# 🖧 Redundant Campus Network – Cisco Packet Tracer Lab

This lab demonstrates a **redundant Layer 2 switching architecture** using Cisco **multilayer switches (3560)** and **access switches (2960)** to simulate a highly available enterprise campus network.

## 🧩 Topology Overview

- **Core Layer**: Two Cisco 3560 Multilayer Switches (Switch0 and Switch1) act as the core/distribution layer with inter-switch links for redundancy.
- **Access Layer**: Two Cisco 2960 switches (Switch1 and Switch2) connect to end devices and uplink redundantly to the core.
- **End Devices**:
  - PC4 & PC5 → connected to Access Switch1
  - PC6 & PC7 → connected to Access Switch2

## 🔧 Technologies Practiced

- VLAN segmentation
- Redundant links with **Spanning Tree Protocol (STP)**
- Basic inter-VLAN routing on multilayer switches
- Fast failover in case of link failure
- Layer 2 Access / Layer 3 Core design model

## 📂 Files

- `redundant-switching.pkt` – Cisco Packet Tracer simulation file
- `config-commands.txt` – CLI configurations used (optional)
- `topology-diagram.png` – Visual representation of the topology

## 💡 Learning Outcomes

- Understand how enterprise campus networks implement redundancy using multiple switches.
- Configure STP to ensure loop-free topologies.
- Design fault-tolerant topologies with scalable VLAN-based architectures.
- Get hands-on experience configuring Cisco switching infrastructure in simulated environments.

## 🛠️ Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

---
