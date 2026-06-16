*Volunteer IT Infrastructure Specialist** | Keiser University, Tallahassee, FL | June 2026 – September 2026

---

## 📋 Project Overview

The **Seahawk Cyber-Sprint** is a hands-on IT infrastructure initiative at Keiser University where I served as a volunteer IT Infrastructure Specialist. The project involved building and maintaining a fully operational technology lab from scratch — from component-level hardware assembly and projector repair to complete network configuration and deployment.

This repository documents the work performed, technologies used, and lessons learned throughout the deployment.

---

## 🛠️ What Was Done

### Hardware Assembly & Deployment
- Assembled **20+ Dell desktop computers** from component level: BIOS/UEFI configuration, RAM installation, CPU cooler mounting, storage drive setup, and PSU integration
- Inspected and diagnosed motherboard-level issues (Dell OptiPlex and Tower series) — SATA ports, RAM slots, CMOS battery, chipset components
- Deployed **Windows 10/11** and **Linux Mint** operating systems via bootable USB across all machines
- Performed hardware diagnostics using ESD-safe procedures, compressed air cleaning, and component bench testing

### Projector Repair & Maintenance — NEC V260 DLP
- Performed **full component-level disassembly** of NEC NP-V260 DLP projectors (manufactured June 2011, Lamp Type: NP13LP)
- Removed and inspected the **lamp assembly (NP13LP)**, lamp door/cover, and housing
- Removed and inspected the **main DLP board** (Texas Instruments DLP chipset) and **I/O board** (Audio In, Computer In, VGA Monitor Out, PC Control, S-Video)
- Documented internal wiring, optical path (lens assembly, cooling fans), and connector layout for reassembly
- Identified fault conditions and performed maintenance on projector internals
- Reassembled units and verified functionality

### Network Infrastructure
- Configured and deployed **Cisco 2500 Series** routers/switches and **Cisco Catalyst 1900 Series** switches
- Set up **DHCP** and **DNS** services for the lab network
- Configured **VLANs** for network segmentation
- Performed physical cabling and cable management on rack-mounted equipment
- Executed port-by-port status verification and documented all results with physical labels
- Performed comprehensive network testing: connectivity verification, ping/tracert analysis

### Documentation
- Created technical documentation, troubleshooting guides, and system specifications
- Labeled all network equipment with operational status ("W ON", "ALL PORTS OK", "Ports 4 8 12 off")
- Produced hardware inventory and configuration records for ongoing support

---

## 🧰 Technologies & Equipment

| Category | Tools / Equipment |
|---|---|
| Networking | Cisco 2500 Series, Cisco Catalyst 1900, Allied Telesyn CentreCOM FH724SW |
| Protocols | TCP/IP, DHCP, DNS, VLANs, LAN |
| Operating Systems | Windows 10, Windows 11, Linux Mint |
| Desktop Hardware | Dell OptiPlex / Tower series, RAM, CPU coolers, HDDs (Seagate), PSUs |
| AV / Projectors | NEC NP-V260 DLP (NP13LP lamp, TI DLP chipset, VGA/S-Video I/O) |
| Safety Equipment | ESD wrist strap, anti-static mat, multimeter, compressed air |
| Network Testing | ping, ipconfig, tracert, port status verification |
| Other Lab Equipment | 3D Printers, FPV/consumer drones (IoT section) |

---

## 📸 Lab Photos

### Computer Inventory — Pre-Deployment
> 20+ desktop units staged and ready for processing. Mixed fleet of Dell tower and small form factor units.

![Computer Inventory](photos/computer-inventory.jpg)

---

### Hardware Assembly Workbench — General
> Open desktop chassis during component installation. ESD wrist strap in use. Multimeter and soldering equipment visible.

![Hardware Workbench](photos/hardware-workbench.jpg)

---

### Dell Motherboard — Bench Assembly
> Dell desktop motherboard outside the case during inspection. CPU cooler, Seagate HDD, and PSU visible alongside ESD mat and cleaning brush.

![Dell Bench Assembly](photos/desktop-bench-assembly.jpg)

---

### Dell Desktop — Interior Hardware (Motherboard & RAM)
> Dell OptiPlex motherboard inside chassis. RAM slots, SATA connectors (blue/red), 24-pin ATX power connector, and CPU cooler fan visible. Full cable bundle routed along chassis wall.

![Dell Desktop Interior 1](photos/desktop-interior-ram.jpg)

---

### Dell Desktop — Motherboard Close-Up
> Dell motherboard detail: chipset, CMOS battery, SATA ports, PCIe slots, and Dell.com branding. Component-level inspection to verify functionality before OS deployment.

![Dell Motherboard Close-up](photos/desktop-motherboard-closeup.jpg)

---

### Dell Tower — Full Interior View
> Full tower interior with HDD installed (Seagate), CPU cooler fan, cable management, and motherboard. Ready for OS deployment.

![Dell Tower Interior](photos/desktop-tower-full.jpg)

---

### NEC V260 DLP Projector — Exterior
> NEC NP-V260 DLP projector. Lamp housing open during maintenance. Model manufactured June 2011.

![NEC Projector Exterior](photos/projector-exterior.jpg)

---

### NEC V260 — Rear I/O Panel
> Rear panel connections: Audio In, Computer In (VGA), Monitor Out (COMP), PC Control (RS-232), S-Video In, Video In, AC power input. Model: NP-V260 1601691EB, Manufactured June 2011.

![NEC Projector Rear I/O](photos/projector-rear-io.jpg)

---

### NEC V260 — Top Panel (Lamp Compartment Open)
> Top view of NEC V260 with lamp door removed. Controls visible: Power, Status, Lamp indicators; Source, Auto Adj., Exit, Enter, Menu, Volume, Zoom/Focus. Lamp Type: NP13LP.

![NEC Projector Top](photos/projector-nec-v260-top.jpg)

---

### NEC V260 — Lamp Assembly Removed
> NP13LP lamp module fully removed from projector housing. Connector visible at top. Lamp is the primary consumable in DLP projectors.

![NEC Lamp Assembly](photos/projector-lamp-assembly.jpg)

---

### NEC V260 — Lamp Bulb Detail
> Close-up of the NP13LP DLP lamp bulb held during inspection. Reflector and arc lamp visible. ESD wrist strap worn throughout disassembly.

![NEC Lamp Bulb](photos/projector-lamp-bulb.jpg)

---

### NEC V260 — Lamp Door Cover
> Lamp door (black plastic cover) removed from housing. Caution labels indicate mercury vapor content — handled per safety guidelines.

![NEC Lamp Cover](photos/projector-lamp-cover.jpg)

---

### NEC V260 — Full Interior Disassembly
> Projector fully open: optical engine visible with lens assembly, cooling fans, wiring harness, and sensor boards. Main PCB and I/O board removed for inspection.

![NEC Projector Interior](photos/projector-interior.jpg)

---

### NEC V260 — Main DLP Board
> Main projector PCB featuring Texas Instruments DLP chipset. NEC branding visible. Board manages image processing, power distribution, and I/O signal routing.

![NEC DLP Main Board](photos/projector-dlp-board.jpg)

---

### NEC V260 — I/O Board
> Input/output board removed for inspection. Handles all external signal connections (VGA, RS-232, S-Video, Audio). Connects to main board via ribbon connectors.

![NEC I/O Board](photos/projector-io-board.jpg)

---

### NEC V260 — Reassembly
> Projector during reassembly phase. Main board reinstalled, lens assembly and optical path intact, wiring reconnected before housing closure.

![NEC Reassembly](photos/projector-reassembly.jpg)

---

### Lab Overview
> Active lab workspace with Dell monitors, NEC projector configured, network topology diagram on wall, and Fluke Networks reference materials.

![Lab Overview](photos/lab-overview.jpg)

---

### Network Rack — Equipment View
> Rack-mounted network equipment: Allied Telesyn 24-port switch (top), two Cisco 2500 Series units, and Cisco Catalyst 1900 Series (bottom) with active port LEDs.

![Network Rack](photos/network-rack.jpg)

---

### Network Rack — Labeled & Verified
> Completed port verification and status labeling. Each unit tagged with operational status ("W ON", "ALL PORTS OK") and known issues ("Ports 4 8 12 off") for ongoing support reference.

![Network Rack Labeled](photos/network-rack-labeled.jpg)

---

### Additional Lab Equipment
> 3D printing station, GoPro camera, and various hardware components — part of the broader Seahawk technology ecosystem.

![Lab Equipment](photos/lab-equipment.jpg)

---

### Drone / IoT Lab
> FPV racing drones, consumer drones, and camera equipment maintained as part of the lab's IoT and embedded systems section.

![Drones](photos/drones.jpg)

---

## 📂 Repository Structure

```
keiser-cyber-sprint/
│
├── README.md                      ← You are here
├── photos/                        ← Lab documentation photos
│   ├── hardware-workbench.jpg
│   ├── computer-inventory.jpg
│   ├── desktop-bench-assembly.jpg
│   ├── desktop-interior-ram.jpg
│   ├── desktop-motherboard-closeup.jpg
│   ├── desktop-tower-full.jpg
│   ├── lab-overview.jpg
│   ├── network-rack.jpg
│   ├── network-rack-labeled.jpg
│   ├── projector-nec-v260-top.jpg
│   ├── projector-rear-io.jpg
│   ├── projector-exterior.jpg
│   ├── projector-lamp-assembly.jpg
│   ├── projector-lamp-bulb.jpg
│   ├── projector-lamp-cover.jpg
│   ├── projector-interior.jpg
│   ├── projector-dlp-board.jpg
│   ├── projector-io-board.jpg
│   ├── projector-reassembly.jpg
│   ├── lab-equipment.jpg
│   └── drones.jpg
│
└── docs/
    ├── network-setup.md           ← Network configuration details
    ├── hardware-deployment.md     ← PC assembly & deployment process
    └── projector-repair.md        ← NEC V260 DLP repair documentation
```

---

## 🎯 Skills Demonstrated

- **Hardware (PCs):** Component-level Dell desktop assembly, BIOS/UEFI setup, RAM/CPU/HDD installation, PSU integration, OS deployment, hardware diagnostics
- **Hardware (AV/Projectors):** Full DLP projector disassembly (NEC NP-V260), lamp replacement (NP13LP), board-level inspection (TI DLP chipset), optical path documentation, reassembly
- **Networking:** Cisco switch configuration, DHCP/DNS setup, VLAN configuration, cabling, port status verification
- **Safety:** ESD best practices (wrist strap, anti-static mat), mercury lamp handling per safety guidelines
- **Documentation:** Technical write-ups, port status labeling, component inventory, troubleshooting guides

---

## 🎓 About the Program

The Seahawk Cyber-Sprint is part of Keiser University's IT program in Tallahassee, FL — a hands-on initiative designed to give students real-world experience building and maintaining IT infrastructure. This project was completed in parallel with coursework toward an **Associate of Science in Information Technology**.

---

## 📬 Contact

**Leonardo da Silveira Moutinho**
- 📧 leosilveira2009@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/leonardomoutinho)
- 🐙 [GitHub](https://github.com/leonardosmoutinho)

---

### Dell Desktop — Optical Drive Installation
> DVD/optical drive being removed and reinstalled. SATA POWER and SATA SIGNAL connectors clearly labeled on the drive bracket. Orange SATA data cable connected to motherboard. Blue HDD caddy visible alongside.

![Dell Optical Drive](photos/desktop-optical-drive.jpg)

---

### Dell Desktop — Drive Bay & Locking Mechanism
> Close-up of Dell's tool-less drive bay locking bracket. Spring-loaded retention clips secure optical drives without screws — a common feature in Dell OptiPlex business-class systems.

![Dell Drive Bay](photos/desktop-drive-bay-mechanism.jpg)

---

### Dell Desktop — Seagate Barracuda HDD in Caddy
> Seagate Barracuda 250GB HDD (7200 RPM, SATA) mounted in Dell's blue plastic caddy. Drive caddy snaps into chassis rail without tools. SATA data and power cables routed cleanly to motherboard and PSU.

![Seagate HDD in Caddy](photos/desktop-hdd-seagate-caddy.jpg)

---

### Dell Desktop — HDD Removal (Hands-On)
> HDD being removed from chassis for inspection/replacement. Demonstrates proper component handling — supporting the drive from below, SATA cables disconnected before extraction.

![Dell HDD Removal](photos/desktop-hdd-removal.jpg)

---

### Dell Desktop — Alternate Motherboard (MS0520)
> Second Dell motherboard model (Board ID: MS0520, Factory ID: J). CMOS password jumper visible (1-2: Clear Password / 2-3: Normal Default). Yellow front-panel connector, CMOS/RTC lithium battery, and multiple expansion slots. Shows familiarity working across multiple Dell hardware generations.

![Dell MS0520 Board](photos/desktop-motherboard-ms0520.jpg)

---

### Dell Desktop — Full Interior with SATA Cable Routing
> Full interior view showing cable management: orange and black SATA data cables, multi-color PSU harness (24-pin ATX, 4-pin CPU, SATA power), front-panel connector bundle, and Dell motherboard. Demonstrates organized cable routing for airflow and serviceability.

![Dell Interior Cable Routing](photos/desktop-sata-cable-routing.jpg)

---

### Dell Desktop — Classroom Deployment Scale
> Multiple Dell towers open simultaneously across classroom workbenches. Demonstrates the scale of the deployment — each unit processed individually through hardware inspection, cleaning, component verification, and OS deployment.

![Classroom Deployment Scale](photos/desktop-classroom-scale.jpg)

