# Multi-Site Network Design | Cisco Packet Tracer

## Project Overview
A multi-router network lab built using Cisco Packet Tracer to practice VLAN segmentation, inter-VLAN routing, DHCP, DHCP relay, and dynamic routing with OSPF.

## Network Devices
- 3 Routers: R1, R2, R3
- 3 Switches: SW1, SW2, SW3
- PCs and end devices

## Technologies
- VLANs and 802.1Q Trunking
- Router-on-a-Stick
- DHCP and DHCP Relay
- OSPF Single Area (Area 0)
- IPv4 Addressing and Subnetting
- Switch Management

## IP Addressing Plan

| Network | Subnet | Default Gateway |
|---|---|---|
| IT - VLAN 10 | 192.168.10.0/24 | 192.168.10.1 |
| Sales - VLAN 20 | 192.168.20.0/24 | 192.168.20.1 |
| Service - VLAN 30 | 192.168.30.0/24 | 192.168.30.1 |
| Branch 1 | 192.168.50.0/24 | 192.168.50.1 |
| Branch 2 | 192.168.60.0/24 | 192.168.60.1 |

## Repository Structure
- `configs/` - Router and switch configurations
- `project.pkt` - Cisco Packet Tracer project
- `topology.png` - Network topology diagram

## Verification Commands
```text
show ip interface brief
show ip route
show ip ospf neighbor
show ip dhcp binding
show running-config
```

Connectivity can be tested using `ping`.

## Tools
- Cisco Packet Tracer
- Cisco IOS CLI

## Author
CCNA Learner | Aspiring Network Engineer