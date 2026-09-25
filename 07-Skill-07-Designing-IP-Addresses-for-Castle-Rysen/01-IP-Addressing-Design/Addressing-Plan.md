# Castle Rysen Initial Addressing Plan

## Internal Network Allocation

Each café receives four /24 networks.

| Purpose | Subnet |
|----------|---------|
| Internal devices | 192.168.x.0/24 |
| VoIP | 192.168.x.1/24 |
| Guest Wi-Fi | 192.168.x.2/24 |
| Guest Rooms / Expansion | 192.168.x.3/24 |

Example:

Cafe 1
- 192.168.0.0/24
- 192.168.1.0/24
- 192.168.2.0/24
- 192.168.3.0/24

Cafe 2
- 192.168.4.0/24
- 192.168.5.0/24
- 192.168.6.0/24
- 192.168.7.0/24

---

## Enterprise Structure

- 5 District Shops per Fallout Shelter
- 30 Fallout Shelters per Central Office

---

## Address Allocation Strategy

Instead of assigning addresses from low to high, fallout shelters are planned from the top of the available address space downward.

Example:

Fallout Shelter 1

- 192.168.255.0/24
- 192.168.254.0/24
- 192.168.253.0/24

This approach reserves large continuous address ranges for future expansion and keeps enterprise addressing organised as the network grows.
