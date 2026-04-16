# 🌐 Static Routing Network Project (Cisco Packet Tracer)

## 📌 Overview
This project demonstrates the implementation of **Static Routing** using Cisco Packet Tracer. The network is designed with multiple routers and LANs to enable communication between different subnets.

## 🏗️ Network Topology
- 3 Routers (R0, R1, R2)
- 3 Switches
- 6 PCs (2 per network)

Each router is connected to:
- A local LAN via GigabitEthernet
- Other routers via Serial interfaces

## 🔧 IP Configuration

### Serial Links:
- R0 ↔ R1 → 10.0.0.1 / 10.0.0.2
- R1 ↔ R2 → 11.0.0.1 / 11.0.0.2

### LAN Networks:
- R0 → 192.168.1.0/24
- R1 → 192.168.2.0/24
- R2 → 192.168.3.0/24

### PCs:
- Network 1 → 192.168.1.2, 192.168.1.3
- Network 2 → 192.168.2.2, 192.168.2.3
- Network 3 → 192.168.3.2, 192.168.3.3

## ⚙️ Configuration
- Assigned IP addresses to all router interfaces and PCs
- Configured static routes on each router
- Enabled inter-network communication

## ✅ Testing
- Performed successful **ping test** from PC0 (R0 network) to PC5 (R2 network)
- Verified end-to-end connectivity

## 📸 Screenshots
Screenshots of the topology, routing configuration, and ping test are available in the `screenshots` folder.

## 🎯 Learning Outcomes
- Understanding of static routing
- Router-to-router communication
- IP addressing and subnetting
- Network troubleshooting using ping

## 🛠️ Tool Used
- Cisco Packet Tracer
