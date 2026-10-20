# Hospital Network Infrastructure

## Project Overview

This project aims to design, configure, and document a simulated hospital network infrastructure using Cisco Packet Tracer.

The goal is to build a segmented, reliable, and secure network that supports communication between hospital departments, IP telephony, network services, and external connectivity.

## Objectives

- Design a logical network topology for a hospital.
- Implement VLANs and 802.1Q trunking.
- Configure inter-VLAN routing.
- Deploy IP telephony using Cisco CME.
- Implement DHCP and IPv4/IPv6 addressing.
- Improve Layer 2 security and network segmentation.
- Simulate Internet connectivity through an ISP router.
- Test, troubleshoot, and document the infrastructure.

## Technologies and Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- VLANs and trunking
- Inter-VLAN routing
- DHCP and IP telephony
- Access Control Lists (ACLs)
- NAT/PAT and static routing

## Project Status

**Status: In progress**

### Implemented
- VLAN segmentation for administration, technical users, general users, IP telephony, and network management.
- 802.1Q trunking with a dedicated native VLAN.
- Voice VLAN and Cisco IP telephony using CME.
- Inter-VLAN routing using router-on-a-stick.
- LACP EtherChannel between access switches.
- STP root bridge selection.
- Rapid PVST+ configuration and verification.

### Planned
- DHCPv4, DHCPv6, and IPv6 implementation.
- Switch port security and Layer 2 security mechanisms.
- Internal network services and server integration.
- ISP router, NAT/PAT, and simulated Internet access.
- Network testing, troubleshooting, and technical documentation.

*Note: Features are progressively implemented and validated in Cisco Packet Tracer. The project status will be updated as testing is completed.*

## Repository Structure

The repository will contain the Packet Tracer topology, device configurations, IP addressing documentation, network diagrams, and connectivity test results as the project develops.

## Disclaimer

This is an educational network simulation. It does not represent a production hospital network or contain real patient data.
