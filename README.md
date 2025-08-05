# 🖧 Peer-to-Peer Network Lab – Cisco Packet Tracer

This project demonstrates a **peer-to-peer network topology** in Cisco Packet Tracer. The goal of this lab was to manually configure IP addresses, cable the network, and verify end-to-end connectivity using ICMP (ping).

---

## 🧰 Lab Overview

- Devices: 4x PCs, 1x Switch
- Cables: Copper Straight-Through
- IP Assignment: Static (manually set on each PC)
- Verification: Ping test using Command Prompt

---

## 🖼️ Screenshots

### 1. Initial Device Layout
> PCs and switch placed in the logical workspace

![Device layout](ss1.png)

---

### 2. Connecting the First Device
> PC0 connected to FastEthernet0/1 on Switch0

![First cable connection](ss2.png)

---

### 3. Completed Network Topology
> All four PCs connected to the switch

![Full topology cabled](SS3.png)

---

### 4. Static IP Configuration
> Manual IP address assignment on PC0

![IP configuration](ss4.png)

---

### 5. Ping Test Between Devices
> PC2 pings PC0 successfully

![Ping results](ss5.png)

---

## 📄 IP Address Table

| Device | IP Address     | Subnet Mask     | Default Gateway |
|--------|----------------|------------------|------------------|
| PC0    | 192.168.1.2    | 255.255.255.0    | 192.168.1.1      |
| PC1    | 192.168.1.3    | 255.255.255.0    | 192.168.1.1      |
| PC2    | 192.168.1.4    | 255.255.255.0    | 192.168.1.1      |
| PC3    | 192.168.1.5    | 255.255.255.0    | 192.168.1.1      |

---

## 💡 Skills Practiced

- Static IP addressing
- Cable selection and port mapping
- Command-line ping verification
- Network topology planning and configuration

---

## 📂 Files Included

| File | Description |
|------|-------------|
| [`Building Client Server Network.pkt`](./Building%20Client%20Server%20Network.pkt) | Cisco Packet Tracer file |
| [`ss1.png`](./ss1.png) → [`ss5.png`](./ss5.png) | Screenshots of topology, config, testing |
| [`README.md`](./README.md) | Documentation (this file) |


---

## 👨‍💻 Author

**Anthony Alston**  
UT Dallas – Junior, Information Technology Systems  
🔐 Cybersecurity & Networking Enthusiast  
📫 tosha.alston@gmail.com  
🌐 [GitHub Profile](https://github.com/AnthonyAAlston)
