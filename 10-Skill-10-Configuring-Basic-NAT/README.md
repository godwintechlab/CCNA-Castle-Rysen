# Skill 10 — Configuring Basic NAT

Completed Skill 10 of my CCNA training, covering how Network Address Translation (NAT) works and how to configure it on Cisco routers.

### What I Learned
- Static NAT — one-to-one IP address translation.
- Dynamic NAT — translating private addresses using a public IP pool.
- NAT Overload (PAT) — allowing multiple devices to share a public IP using port numbers.
- Cisco NAT terminology: inside local, inside global, outside local and outside global.
- Configuring standard and extended ACLs, NAT pools and overload using both an interface and a pool.

### Hands-on Practice
Configured static NAT, dynamic NAT and NAT overload in Packet Tracer, including defining inside/outside interfaces, creating address pools and ACLs, and verifying translations using Cisco IOS commands.

### Key Commands
- `ip nat inside` / `ip nat outside`
- `ip nat inside source static`
- `ip nat pool`
- `ip nat inside source list ... pool ...`
- `ip nat inside source list ... interface ... overload`
- `ip nat inside source list ... pool ... overload`
- `show ip nat translations`
- `show ip nat statistics`

### Tools
Cisco Packet Tracer | Cisco IOS
