[packet_tracer_practice_labs_readme.md](https://github.com/user-attachments/files/24787859/packet_tracer_practice_labs_readme.md)
# Packet Tracer Practice Labs

## Overview
A hands-on collection of **Cisco Packet Tracer networking labs** focused on **CCNA-level fundamentals**. This project demonstrates practical skills in **routing, switching, VLANs, NAT, IPv4/IPv6, and troubleshooting** using Cisco IOS.

**Best use:** GitHub portfolio + Resume Project section

---

## What This Project Demonstrates (Resume-Friendly)
- Designed and configured multi-device network topologies in Cisco Packet Tracer
- Implemented **VLANs, trunking (802.1Q), Router-on-a-Stick**, and **static routing**
- Applied **VLSM subnetting** and **NAT (Static, Dynamic, PAT)**
- Configured **IPv6 addressing and routing**
- Verified connectivity and troubleshot issues using IOS commands and ICMP

---

## Lab Structure
- `*-start.pkt` → Practice labs (incomplete configurations)
- `*-solution.pkt` → Reference solutions (fully configured)

Each lab focuses on a specific networking concept and is intended for step-by-step practice.

---

## Topics Covered
- IPv4 Addressing & Subnetting
- VLANs & Trunking
- Router-on-a-Stick
- Static Routing
- VLSM
- NAT (Static, Dynamic, PAT)
- VTP & STP
- IPv6 Configuration

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS (Routers & Switches)
- TCP/IP, VLANs, NAT, STP

---

## How to Run
1. Install **Cisco Packet Tracer** (free via Cisco Networking Academy)
2. Extract the repository
3. Open Packet Tracer → **File → Open** → select any `.pkt` file
4. Start with `*-start.pkt`, validate using `*-solution.pkt`

---

## Sample IOS Commands
```bash
enable
configure terminal
interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
```

---

## Resume Entry (Copy-Paste)
**Cisco Packet Tracer Networking Labs**  
- Built and configured simulated enterprise networks using Cisco Packet Tracer
- Implemented VLANs, trunking, static routing, NAT, and IPv6
- Performed subnetting (VLSM) and verified connectivity using ICMP and IOS tools
- Tools: Cisco Packet Tracer, TCP/IP, VLAN, NAT, Routing

---

## License
Educational use only.

---

## Notes
This project is intended to showcase **practical networking skills** for internships and entry-level roles (Network Engineer, NOC, Cloud/DevOps foundation).
