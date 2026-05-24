# Lab 01 - Basic Routed LAN Connectivity

A Cisco Packet Tracer lab that demonstrates basic routed LAN connectivity between two separate networks using a Cisco 2911 router.

## Lab Overview

This lab focuses on the foundation of routing between two LANs. It verifies that hosts in different IP networks can communicate through a router when interfaces, IP addressing, default gateways, and end-to-end connectivity are configured correctly.

## Topology

| Device | Role |
|---|---|
| R1 | Cisco 2911 router connecting both LANs |
| SW1 | Access switch for LAN 1 |
| SW2 | Access switch for LAN 2 |
| PC-A | Client host in LAN 1 |
| PC-B | Client host in LAN 2 |

## Main Objectives

- Build a simple routed LAN topology in Cisco Packet Tracer
- Configure router interfaces for two separate LANs
- Assign IPv4 addresses to hosts and network interfaces
- Configure default gateways on client PCs
- Verify connectivity between different networks using ping
- Document the lab with clear evidence images

## Skills Demonstrated

- Basic network topology design
- IPv4 addressing
- Router interface configuration
- Default gateway configuration
- LAN-to-LAN connectivity testing
- Packet Tracer documentation
- Network troubleshooting fundamentals

## Verification Summary

The lab was verified by checking:

- Correct physical/logical topology
- Router interfaces are configured and operational
- End devices have valid IPv4 settings
- Default gateways are correctly assigned
- PC-A can reach PC-B across the router
- PC-B can reach PC-A across the router
- Ping tests complete successfully with 0% packet loss

## Project Files

This repository contains the Packet Tracer project file and supporting evidence images for Lab 01.

Recommended Packet Tracer file name:

`Lab_01_Basic_Routed_LAN_Connectivity_Dahman_AlShehri.pkt`

## Notes

This lab represents the first step in a practical networking portfolio. It establishes the core routing and connectivity concepts needed before moving into VLANs, trunking, DHCP, IPv6, SSH, and network security in later labs.

## Author

**Dahman Fayez Al-Shehri**  
Networking and Telecommunications Student  
GitHub: [dahman0al0shahri](https://github.com/dahman0al0shahri)
