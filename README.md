# H&M Boutique Law Firm Network Design

## Overview

This project simulates a segmented network infrastructure for a small law firm using Cisco Packet Tracer.

## Network Topology 

This project was designed for a small law firm environment. The network uses VLAN segmentation to separate staff devices, servers, printers, and guest wireless users. Inter-VLAN communication is provided through Router-on-a-Stick routing using a Cisco 2911 router. 

## Features

- VLAN 10 - Staff
- VLAN 20 - Server
- VLAN 30 - Printers
- VLAN 40 - Guest WiFi
- Router-on-a-Stick Inter-VLAN Routing
- 802.1Q Trunking
- Wireless Connectivity
- Connectivity Verification

## VLAN Design 

| VLAN | Purpose | Network | Gateway |
|------|----------|----------|----------|
| 10 | Staff | 192.168.1.0/24 | 192.168.1.1 |
| 20 | Server | 192.168.2.0/24 | 192.168.2.1 |
| 30 | Printers | 192.168.3.0/24 | 192.168.3.1 |
| 40 | Guest WiFi | 192.168.4.0/24 | 192.168.4.1 |

## Technologies

- Cisco Packet Tracer
- Cisco 2911 Router
- Cisco 2960 Switches
- VLANs
- Inter-VLAN Routing
- Network Troubleshooting

## Verification

The network was validated using Cisco IOS verification commands and connetivity testing. 

- show vlan brief
- show interfaces trunk
- show ip interface brief
- show ip route
- Ping testing between devices and printers
