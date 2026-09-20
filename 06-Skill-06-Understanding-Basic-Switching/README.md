# 06-Skill-06-Basic-Switching

## Overview

This skill focused on understanding how Layer 2 switches forward Ethernet frames using MAC addresses and CAM tables. I explored Ethernet frame structure, MAC address learning, ARP, basic IP addressing, and used Cisco IOS commands to locate end devices across a multi-switch network.

---
## Skills & Topics Covered

- Ethernet frames and MAC addresses
- Frame Check Sequence (FCS) and Cyclic Redundancy Check (CRC)
- CAM (MAC Address) tables and dynamic MAC learning
- Switch forwarding decisions and unknown unicast flooding
- Basic IPv4 addressing (network vs host)
- Address Resolution Protocol (ARP) and ARP cache
- ICMP Ping
- Device tracking across multiple switches
- Layer 2 troubleshooting
- Cisco IOS verification commands

---

## Cisco IOS Commands

```bash
show ip interface brief
show interfaces status
show interfaces description
show mac address-table
show mac address-table address <mac-address>
show mac address-table interface <port>
show arp
show arp | include <ip-address>
ping
show cdp neighbours
```
