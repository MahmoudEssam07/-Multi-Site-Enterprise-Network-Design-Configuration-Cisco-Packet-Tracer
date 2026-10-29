# Multi-Site Enterprise Network Design & Configuration

## 📌 Project Overview

This project demonstrates the design and configuration of a multi-site enterprise network using **Cisco Packet Tracer**.

The network connects multiple locations through routers and switches, providing inter-site communication, network segmentation, dynamic routing, automatic IP address assignment, and basic Layer 2 security.

## 🎯 Project Objectives

- Design a multi-site enterprise network topology.
- Implement VLANs for network segmentation.
- Configure OSPF for dynamic routing between sites.
- Configure DHCP for automatic IP address assignment.
- Implement DHCP Snooping to help protect against rogue DHCP servers.
- Configure PortFast on appropriate switch access ports.
- Integrate wireless access points for wireless connectivity.
- Configure DHCP and DNS server services.

## 🛠️ Technologies & Protocols

| Technology | Purpose |
|---|---|
| Cisco Packet Tracer | Network design and simulation |
| VLANs | Network segmentation |
| OSPF | Dynamic routing |
| DHCP | Automatic IP configuration |
| DHCP Snooping | Layer 2 security |
| PortFast | Faster transition of access ports to forwarding |
| Wireless Access Points | Wireless network connectivity |
| DNS | Name resolution |
| Serial Links | Inter-router connectivity |

## 🗺️ Network Topology

The topology consists of multiple sites connected through routers, with switches, wireless access points, PCs, printers, and centralized network services.

### Network Segmentation

- **VLAN 10:** Place 1
- **VLAN 20:** Place 2
- **VLAN 30:** Place 3
- **VLAN 40:** Place 4
- **VLAN 50:** Main Office

The main office includes DHCP and DNS servers, while the routers provide connectivity between the different network segments and locations.

<!-- Upload your topology image as topology.png to display it below. -->

![Multi-Site Enterprise Network Topology](topology.png)

## ⚙️ Implementation Details

### 1. VLAN Configuration
Created separate VLANs to logically segment the network and organize devices across different locations.

### 2. OSPF Dynamic Routing
Configured OSPF on the routers to exchange routing information and enable communication between remote networks.

### 3. DHCP Services
Configured DHCP services to automate IP address assignment to end devices and simplify network administration.

### 4. DHCP Snooping
Implemented DHCP Snooping on the appropriate switches to help prevent unauthorized DHCP servers from providing IP configuration to clients.

### 5. PortFast
Configured PortFast on suitable end-device access ports to reduce the time required for ports to enter the forwarding state.

### 6. Wireless Connectivity
Integrated wireless access points to provide network access to wireless clients. Wireless SSIDs and security settings were configured for the relevant locations.

### 7. DHCP and DNS Servers
Included DHCP and DNS servers in the main office to support essential network services.

## 🧪 Verification & Testing

The following commands can be used to verify the network configuration:

**Check OSPF neighbors**
```text
show ip ospf neighbor
```

**Inspect the routing table**
```text
show ip route
```

**Verify VLANs**
```text
show vlan brief
```

**Verify DHCP Snooping**
```text
show ip dhcp snooping
```

**Test connectivity**
```text
ping <destination-ip-address>
```

These checks help verify routing adjacencies, learned routes, VLAN assignments, DHCP Snooping status, and end-to-end connectivity.

## 📁 Project Files

- `Multi-Site-Enterprise-Network.pkt` — Cisco Packet Tracer project file.
- `topology.png` — Network topology diagram.
- `README.md` — Project documentation.

## 💻 Requirements

- Cisco Packet Tracer
- Basic knowledge of networking concepts, VLANs, IP addressing, and routing

## 📚 Learning Outcomes

Through this project, I practiced:

- Enterprise network design and segmentation.
- Dynamic routing using OSPF.
- DHCP configuration and IP address management.
- Layer 2 security concepts.
- Wireless network integration.
- Network troubleshooting and connectivity verification.

## 👨‍💻 Author

**Mahmoud Essam**

GitHub: [MahmoudEssam07](https://github.com/MahmoudEssam07)

---

⭐ If you find this project useful, feel free to explore the repository!
