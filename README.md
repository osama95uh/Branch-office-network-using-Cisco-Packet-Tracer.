#  Network Lab


Branch office network using Cisco Packet Tracer.

## Technologies
- Router-on-a-Stick
- VLAN segmentation
- OSPF
- SSH
- STP

## Structure
- Topology/ - Packet Tracer files
- configs/R1_Core_Config.ios - Router config
- configs/SW1.configs.ios - Switch config

## Devices
- R1 - 192.168.10.1, 192.168.20.1
- SW1 - VLAN 10, 20, 99

## VLANs
- 10 Sales - 192.168.10.0/24
- 20 Guest - 192.168.20.0/24
- 99 Management - Native

## Setup
1. Install Packet Tracer 8.x
2. Open Topology/
3. Load configs/

## Status
- Done: VLAN, trunking, ROAS, OSPF, SSH
- Planned: DHCP, ACL

