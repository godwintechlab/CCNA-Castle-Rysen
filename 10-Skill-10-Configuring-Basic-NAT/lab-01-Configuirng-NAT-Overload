# Skill 10 - Lesson 06 - NAT Overload

### Overview
Configured NAT Overload (PAT) on **Cafe-Rtr**, allowing multiple private devices to share a single public IP address (**216.0.5.2**) using different port numbers.

### Lab Objectives
- Removed the old dynamic NAT mapping using the `Cafe-Public` pool.
- Temporarily shut down Ethernet0/0 and Ethernet0/1 during reconfiguration.
- Reused **ACL 1** to permit internal devices to use NAT Overload.
- Configured Ethernet0/0 as NAT inside and Ethernet0/1 as NAT outside.
- Restored both interfaces to **up/up** status.
- Tested connectivity from PC1 (**192.168.1.50**) and PC2 (**192.168.1.51**) to **1.1.1.1**.
- Verified both PCs translated to **216.0.5.2** using different port identifiers.
- Checked NAT translations and statistics to confirm PAT was working.

### Result
Both internal PCs successfully accessed the outside network using the same public IP address, **216.0.5.2**, demonstrating NAT Overload.
