# Hospital Network — Design Notes

## 1. Project Context

This project simulates a hospital network infrastructure using Cisco Packet Tracer. The design focuses on network segmentation, IP telephony, inter-VLAN routing, redundancy, and security.

## 2. Current Topology

- 1 Cisco router
- 2 Cisco Catalyst 2960 switches
- 6 PCs
- 6 IP phones

The topology will be expanded progressively with servers, wireless access, and simulated Internet connectivity.

## 3. VLAN Plan

| VLAN ID | Purpose |
|---|---|
| 10 | Administration |
| 20 | Technical users |
| 30 | General users |
| 40 | IP telephony |
| 99 | Network management |
| 100 | Unused ports |
| 150 | Native VLAN |

## 4. IP Addressing

| VLAN | Network | Default Gateway |
|---|---|---|
| 10 | 192.168.10.0/26 | 192.168.10.1 |
| 20 | 192.168.10.64/27 | 192.168.10.65 |
| 30 | 192.168.10.96/28 | 192.168.10.97 |
| 40 | 192.168.10.128/26 | 192.168.10.129 |
| 99 | 192.168.10.112/29 | 192.168.10.115 |

## 5. Switching and Routing

The network uses 802.1Q trunks and router-on-a-stick for inter-VLAN routing. LACP EtherChannel and Rapid PVST+ are part of the redundancy and Layer 2 configuration exercises.

## 6. Validation

Inter-VLAN connectivity and IP telephony have been tested in the current Packet Tracer environment. Additional redundancy, security, and external connectivity tests will be documented as they are completed.

## 7. Scope

This is an educational simulation, not a production-ready hospital network. No real patient information is used.
