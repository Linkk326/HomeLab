# 🏠 HomeLab Overview

Welcome to my HomeLab repository! This repo documents the architecture, projects, and practical skills I've built by designing and maintaining a functional network and virtualization environment. My setup allows me to explore areas like:

- Cybersecurity
- Networking
- Virtualization
- Systems administration
- Home automation and monitoring

---

## 🧱 Infrastructure Overview

### 🔌 ISP & Router
- **Internet Provider:** COX
- **Firewall/Router:** `pfSense` running as a VM
- **Hypervisor:** Proxmox VE
- **Host Machine:** HP EliteDesk Mini
  - **CPU:** Intel i7-8700
  - **RAM:** 8 GB
  - **Storage:** 500 GB M.2 SSD

> pfSense VM is the central routing and firewall solution, running on the bare metal Proxmox host.

---

### 🔀 Network Topology

- **LAN Backbone:** Cisco Meraki 8-Port PoE Switch
- **Access Points:** TP-Link Deco Mesh System (configured as APs)
- **Extra Connectivity:** Netgear 5-Port Unmanaged Switch

---

### 🖥️ Proxmox Cluster

**Two-node Proxmox cluster hosting critical VMs and services.**

#### Node 1 & Node 2:
- **Model:** HP Z2 Mini G3 (x2)
- **CPU:** Intel i7-8700
- **RAM:** 16 GB each
- **Cluster Features:** Local backups, resource pooling, redundancy (manual failover)

---

## 📡 Network Flow Diagram *(Visual Coming Soon)*


> A full network diagram with IP ranges, VLANs, and virtual topology will be included in the `/Diagrams` folder.

---

## 🔧 Coming Soon: VM & Service Details

Each major VM or service in the lab will be documented in its own folder with:
- Config steps
- Network configuration
- Security posture
- Screenshots and logs

Stay tuned!

---

## 🧠 Goals of this HomeLab

- Practice secure network segmentation and firewall rules
- Deploy enterprise-grade services in a virtual environment
- Document real-world sysadmin and networking tasks
- Build a portfolio for cybersecurity and infrastructure roles

---

## 📜 License

This repository is for personal and educational use. Diagrams, notes, and configurations are shared for reference purposes only.


