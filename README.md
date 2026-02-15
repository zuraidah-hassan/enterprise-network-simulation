# Enterprise Network Simulation

This repository contains my hands-on networking labs using Cisco Packet Tracer.

---

## Lab 01 – Basic LAN

### Topology Diagram
![Lab 01 Topology](screenshots/lab01-topology.png)

### Ping Verification
![Lab 01 Ping Result](screenshots/lab01-ping.png)


### Topology
3 PCs connected to one Layer 2 switch (2960).

### IP Addressing
- HR-PC: 192.168.1.10 /24
- Admin-PC: 192.168.1.20 /24
- Finance-PC: 192.168.1.30 /24

### Verification
Successful ping between all PCs (0% packet loss).

### Skills Demonstrated
- Manual IP configuration
- Basic Layer 2 switching
- Network connectivity testing using ping

---

## Lab 02 – Inter-Network Routing (Router)

### Topology

![Lab 02 Topology](screenshots/lab02-topology.png)

### Router Interfaces

![Lab 02 Router Interfaces](screenshots/lab02-router-interfaces.png)

### Cross Network Ping

![Lab 02 Cross Network Ping](screenshots/lab02-cross-network-ping.png)

### Description

Two different networks were connected using a router.

Network A: 192.168.1.0/24
Gateway: 192.168.1.1

Network B: 192.168.2.0/24
Gateway: 192.168.2.1

Devices from both networks successfully communicated through routing.
