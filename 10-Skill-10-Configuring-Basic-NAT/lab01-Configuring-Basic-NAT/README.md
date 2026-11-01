Skill 10 - Skill Lab 01 - Configuring Basic NAT
Overview
Configured Static NAT, Dynamic NAT, and NAT Overload (PAT) on Cafe-Rtr, allowing devices on the private network (192.168.1.0/24) to communicate with the simulated internet through public IP addresses.

Lab Objectives
Configured ISP-Rtr with WAN address 216.0.5.1/30 and loopback addresses 1.1.1.1 and 8.8.8.8.
Established connectivity between Cafe-Rtr (216.0.5.2) and ISP-Rtr.
Configured Static NAT to map PC1 (192.168.1.50) to public IP 216.0.5.20.
Removed Static NAT and configured Dynamic NAT using the Cafe-Public pool (216.0.5.50–216.0.5.100).
Used ACL 1 to identify internal hosts within 192.168.1.0/24 for translation.
Verified PC1 (192.168.1.50) and PC2 (192.168.1.51) received separate public IP addresses through Dynamic NAT.
Removed the Dynamic NAT mapping and configured NAT Overload using the WAN interface Ethernet0/1.
Verified both PCs shared public IP 216.0.5.2 using different port identifiers.
Confirmed successful connectivity to the simulated internet.
Result
Successfully configured and verified all three NAT methods: Static NAT, Dynamic NAT, and PAT. The final configuration allowed multiple internal devices to access the simulated internet through a single public IP address, 216.0.5.2.
