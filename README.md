# dept-lan-design

A basic LAN design project created using Cisco Packet Tracer.  
This project demonstrates the connection of two departments — Accounts and Delivery — using subnetting and routers.

![Network Topology](topology.jpg)

---

## 🛠️ Project Overview

- 🔌 Designed a local area network (LAN) connecting:
  - 📁 Accounts Department
  - 🚚 Delivery Department
- Each department includes at least 2 PCs
- Connected using:
  - Routers
  - Switches
  - Proper cabling
- All devices are configured with:
  - Static IP addresses
  - Subnet masks
  - Default gateways
- Network connectivity was verified using ping tests between departments.

---

## 📡 Network Details

| Department  | Subnet             | Gateway IP        | Example PC IPs          |
|-------------|--------------------|-------------------|--------------------------|
| Accounts    | 192.168.40.0/25    | 192.168.40.1      | 192.168.40.10, .11       |
| Delivery    | 192.168.40.128/25  | 192.168.40.129    | 192.168.40.130, .131     |

---

## 🧰 Tools & Technologies

- Cisco Packet Tracer
- Subnetting (/25)
- Static IP configuration
- Basic Routing

---

## ✅ Results

- ✔️ Successful communication between all PCs across both departments
- ✔️ Clean, organized topology using appropriate addressing and design
- ✔️ Verified connectivity via ping with 0% loss after stabilization

---

## 📁 Files Included

- dept-lan-design.pkt – Cisco Packet Tracer project file
- topology.png – Network topology screenshot
