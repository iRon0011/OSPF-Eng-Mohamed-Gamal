# OSPF & RIP Redistribution Lab (GNS3)

This project is a complete GNS3 topology for practicing **OSPF** (multi-area), **RIP**, and **Redistribution**, including advanced OSPF concepts such as **Totally Stub Area** and **NSSA**, with an **ISP router** that provides Internet access simulation.

---

## 📖 Features
- OSPF multi-area configuration (Backbone + multiple areas).
- Redistribution between **RIP** and **OSPF**.
- OSPF **Totally Stub Area** implementation.
- OSPF **NSSA (Not-So-Stubby Area)** configuration.
- ISP Router simulating Internet connectivity (0.0.0.0/0).
- Loopback interfaces used to simulate multiple networks.
- Full end-to-end connectivity test with `ping` between routers.

---

## 🖼️ Topology
The topology includes multiple routers:
- **Internal Routers** running OSPF and RIP.  
- **ABR/ASBR** for redistribution.  
- **Stub and NSSA area routers.**  
- **ISP Router** with default route advertised.

*(Add topology screenshot here if available, e.g. `topology.png`)*

---

## ⚙️ Requirements
- **GNS3 v2.2+**
- **Cisco IOS image (c7200 recommended)** → *not included in this repo*  
- PC/Laptop with at least 8 GB RAM recommended

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/ospf-rip-redistribution-lab.git
