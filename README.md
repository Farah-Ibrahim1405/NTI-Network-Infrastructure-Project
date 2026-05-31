# Network Infrastructure Project

A network infrastructure simulation project developed using Cisco Packet Tracer.
The project demonstrates VLAN configuration, router and switch setup, static and dynamic routing, subnetting, and Access Control List (ACL) implementation across multiple interconnected networks.

---

# Project Requirements

The network was designed using the subnet:

* `192.168.7.0/24`

The project includes:

* Router configuration with:

  * Hostname setup
  * Encrypted privileged passwords
  * Console configuration
  * SSH configuration
  * Login banner configuration

* Switch configuration with:

  * Native VLAN (VLAN 200)
  * SVI Configuration (VLAN 100)
  * Default gateway setup

* IP address assignment for:

  * Router interfaces
  * Switch interfaces
  * PCs

* Interface descriptions for all router interfaces

* Network verification using Cisco IOS commands

* ACL implementation:

  * Net1 cannot communicate with Net4
  * Net2 cannot communicate with Net3

* Routing implementation using:

  * Static Routing
  * OSPF Routing Protocol

---

# Features

* Multi-LAN Network Design
* VLAN Segmentation
* Router-to-Router Communication
* Static Routing
* OSPF Dynamic Routing
* Access Control Lists (ACL)
* IP Addressing & Subnetting
* Router & Switch Configuration
* Connectivity Verification & Troubleshooting

---

# Verification & Testing

Connectivity and routing behavior were tested between all networks to verify:

* Proper routing
* VLAN functionality
* ACL restrictions
* Interface status
* End-to-end connectivity

The following Cisco IOS commands were used during verification:

```bash
show ip interface brief
show ip route
show interfaces
ping
traceroute
```

---

# Technologies Used

* Cisco Packet Tracer
* VLAN Configuration
* Static Routing
* OSPF Routing Protocol
* Access Control Lists (ACL)
* IP Addressing & Subnetting
* Router & Switch Configuration

---

# Network Topology

The topology consists of:

* 2 Routers
* 4 Switches
* Multiple PCs distributed across different LANs

Routers are connected using serial interfaces, while switches connect local devices inside each subnet.

---

# Project Structure

```
network-infrastructure-project/
│
├── final project.pkt
├── network infra.mp4
└── README.md
```

---


# Educational Purpose

This project was developed for educational purposes to demonstrate:

* Network infrastructure design
* VLAN implementation
* Router and switch configuration
* Static and dynamic routing
* ACL-based traffic filtering
* Network verification and troubleshooting
