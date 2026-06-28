<div align="center">

# 🚀 CCNA Static Routing Lab
### 5-Router Cisco Network Topology built using GNS3

![Cisco](https://img.shields.io/badge/Cisco-IOS-blue?style=for-the-badge&logo=cisco)
![CCNA](https://img.shields.io/badge/CCNA-Networking-red?style=for-the-badge)
![GNS3](https://img.shields.io/badge/GNS3-Lab-green?style=for-the-badge)
![IPv4](https://img.shields.io/badge/IPv4-Static_Routing-success?style=for-the-badge)

<img src="banner.png" width="100%">

### 📖 A Cisco CCNA lab demonstrating Static Routing between five routers with full end-to-end connectivity.

</div>

---

# 📌 Project Overview

This project demonstrates the implementation of **Static Routing** using **Cisco IOS routers** in **GNS3**.

The objective is to establish communication between all routers by manually configuring static routes and verifying complete connectivity using Cisco IOS commands.

---

# 🎯 Objectives

- Configure IPv4 Addressing
- Configure Static Routes
- Verify Routing Tables
- Test End-to-End Connectivity
- Practice Cisco IOS CLI
- Understand Next-Hop Routing
- Troubleshoot Routing Issues

---

# 🖥️ Network Topology

> Replace the image below with your own topology.

<p align="center">

<img src="topology.png" width="900">

</p>

---

# 🌐 IP Addressing Plan

| Link | Network | Router Interfaces |
|------|---------|------------------|
| R1 ↔ R2 | 20.0.0.0/8 | 20.0.0.1 / 20.0.0.2 |
| R1 ↔ R3 | 30.0.0.0/8 | 30.0.0.1 / 30.0.0.2 |
| R1 ↔ R5 | 40.0.0.0/8 | 40.0.0.1 / 40.0.0.2 |
| R3 ↔ R5 | 50.0.0.0/8 | 50.0.0.1 / 50.0.0.2 |
| R2 ↔ R4 | 60.0.0.0/8 | 60.0.0.1 / 60.0.0.2 |
| R4 ↔ R5 | 70.0.0.0/8 | 70.0.0.1 / 70.0.0.2 |

---

# 📂 Repository Structure

```
CCNA-Static-Routing-Lab
│
├── README.md
├── banner.png
├── topology.png
│
├── configs
│   ├── R1.txt
│   ├── R2.txt
│   ├── R3.txt
│   ├── R4.txt
│   └── R5.txt
│
├── gns3
│   └── Static-Routing-Lab.gns3
│
└── screenshots
    ├── ping-success.png
    ├── traceroute.png
    ├── show-ip-route.png
    └── interfaces.png
```

---

# ⚙️ Router Configuration

Each router contains:

- Interface Configuration
- IPv4 Addressing
- Static Routes
- Basic Device Configuration

Configuration files are available inside the **configs** folder.

---

# 🔍 Verification

The following commands were used to verify connectivity.

```bash
show ip route
```

```bash
show ip interface brief
```

```bash
ping
```

```bash
traceroute
```

---

# ✅ Expected Results

✔ All routers successfully reach one another

✔ Static routes installed correctly

✔ Routing tables verified

✔ Successful Ping

✔ Successful Traceroute

---

# 🛠 Skills Demonstrated

- Cisco IOS CLI
- IPv4 Addressing
- Static Routing
- Routing Tables
- Network Troubleshooting
- Cisco Router Configuration
- Connectivity Verification
- GNS3 Network Simulation

---

# 📚 Technologies Used

- Cisco IOS
- GNS3
- IPv4
- Static Routing
- Cisco CLI

---

# 🚀 Future Improvements

- OSPF Single Area
- Multi-Area OSPF
- VLANs
- Inter-VLAN Routing
- ACL Implementation
- NAT/PAT
- DHCP Configuration
- HSRP
- EIGRP
- BGP (Advanced)

---

# 📸 Screenshots

### Routing Table

<img src="screenshots/show-ip-route.png">

---

### Successful Ping

<img src="screenshots/ping-success.png">

---

### Traceroute

<img src="screenshots/traceroute.png">

---

# 🎓 Learning Outcomes

After completing this lab I gained hands-on experience with:

- Static Routing
- Route Selection
- Next-Hop Configuration
- Cisco IOS Commands
- Routing Verification
- Network Troubleshooting

---

# ⭐ If you found this project useful

Give this repository a ⭐

It motivates me to build more Cisco networking labs.

---

<div align="center">

## 👨‍💻 Author

**Pranay Chadda**

Aspiring Network Security Engineer | CCNA Student | Bug Bounty Hunter

</div>
