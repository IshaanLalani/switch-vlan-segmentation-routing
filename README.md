# Cisco Packet Tracer: VLAN Segmentation & Inter-VLAN Routing

## 📋 Project Overview
This repository contains a core networking lab implementation focusing on Layer 2 VLAN segmentation and Layer 3 Inter-VLAN routing using Cisco switches and routers.

---

## 🏗️ Network Architecture & Design
* **Topology Type:** Single-Switch / Multi-Switch VLAN Environment
* **Core Devices:** 
  * **Switches:** Cisco Catalyst Access Switches configured with explicit VLAN databases
  * **Routers / Layer 3 Devices:** Configured for routing traffic between isolated broadcast domains using Inter-VLAN routing (Router-on-a-Stick or SVI)
* **VLAN Configuration:** Departmental or functional segregation of network traffic into designated VLAN IDs.

---

## ⚙️ Implemented Configurations
* **VLAN Creation & Assignment:** Created and named specific VLANs on access switches and assigned switch ports accordingly.
* **Trunking Protocols:** Configured trunk links to carry multiple VLAN traffic across switches.
* **Inter-VLAN Routing:** Enabled inter-subnet communication through router subinterfaces or switch virtual interfaces.

---

## 📂 Repository Structure
```text
├── Assignment Ishaan (1).docx  # Comprehensive lab assignment documentation
└── README.md                   # Project documentation
