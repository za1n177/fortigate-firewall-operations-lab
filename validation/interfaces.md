# FortiGate Interface Configuration

## Interfaces Overview

This lab uses a simple two-interface FortiGate deployment to simulate a real-world perimeter firewall.

### WAN Interface (port1)
- Purpose: Internet connectivity
- Connection type: NAT (via host)
- Role: Outbound access for internal users

### LAN Interface (port2)
- Purpose: Internal network
- Subnet: 192.168.10.0/24
- Gateway IP: 192.168.10.1
- Connected devices: Client VM

## Design Rationale
- Separates internal and external traffic
- Aligns with enterprise firewall best practices
- Allows clear policy and NAT enforcement
