# Cisco-VLAN-InterVLAN-Routing-Lab
Enterprise Cisco networking lab covering VLANs, 802.1Q trunking and Inter-VLAN Routing using Cisco Packet Tracer.
# Cisco VLAN & Inter-VLAN Routing Lab

## 📌 Project Overview

This project demonstrates an enterprise-style Cisco networking lab using Cisco Packet Tracer.

The lab covers VLAN creation, VLAN assignment, 802.1Q trunking, Inter-VLAN Routing, IP addressing, connectivity verification, and basic network troubleshooting.

## 🎯 Project Objectives

- Configure VLANs on Cisco switches
- Assign switch ports to VLANs
- Configure 802.1Q trunking
- Configure Inter-VLAN Routing
- Configure router subinterfaces
- Configure IP addressing
- Verify VLAN and trunk status
- Verify routing and connectivity
- Troubleshoot common VLAN and routing issues

## 🏢 Enterprise Scenario

A company has multiple departments:

- VLAN 10 – HR
- VLAN 20 – Finance
- VLAN 30 – IT

Users from different departments need to communicate through Inter-VLAN Routing while maintaining logical network segmentation.

## 🌐 Network Topology

The topology is designed using Cisco Packet Tracer.

```text
                +----------------+
                |    Router R1   |
                |                |
                | Inter-VLAN     |
                | Routing        |
                +-------+--------+
                        |
                  802.1Q Trunk
                        |
                +-------+--------+
                |   Switch SW1   |
                +---+---+---+----+
                    |   |   |
                  VLAN VLAN VLAN
                   10   20   30
                    |   |   |
                   PC  PC  PC
