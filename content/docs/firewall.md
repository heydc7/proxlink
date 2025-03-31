---
title: Firewall Configuration
weight: 4
---

This guide covers the Firewall Configuration for the ProxLink homelab, utilizing pfSense as the primary firewall and router. The firewall sits at the core of the ProxLink network topology and manages traffic between WAN, LAN, and DMZ subnets, as well as access control for services and remote VPN connections via Tailscale.

### Firewall Overview

ProxLink uses **pfSense**, a robust open-source firewall/router software, deployed as a virtual machine inside the Proxmox environment. pfSense handles:

- **Inter-VLAN Routing**
- **NAT and Port Forwarding**
- **Traffic Filtering (Inbound & Outbound)**
- **VPN Gateway via Tailscale**
- **Access Control between LAN, DMZ, and WAN**

### Interface Mapping

| Interface | pfSense Name | Bridge | Subnet | Purpose |
|----------|---------------|--------|--------|---------|
| net0     | WAN           | vmbr0  | 192.168.1.0/24 | External / Internet access |
| net1     | LAN           | vmbr1  | 192.168.2.0/24 | Internal trusted network |
| net2     | DMZ           | vmbr2  | 192.168.3.0/24 | Exposed services network |
