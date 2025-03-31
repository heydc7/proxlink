---
title: VPN Configuration
weight: 5
---

This section covers how VPN access is configured in the ProxLink homelab using Tailscale. Tailscale provides secure, encrypted, and authenticated remote access to internal services across the LAN and DMZ without the complexity of traditional VPNs.

### Why Tailscale?

Tailscale is a mesh VPN built on **WireGuard**, designed to simplify secure networking across devices and networks. It is ideal for homelabs because:

- **Zero-config** networking over the internet  
- **Device-level access control (ACLs)**  
- **Works through NAT/firewalls**  
- **Supports full-tunnel VPN routing**

### ProxLink VPN Topology

- Tailscale is installed directly on the **pfSense VM** (via a Linux package or Tailscale daemon).
- pfSense acts as a **subnet router** and **exit node**, routing all VPN traffic to internal networks.
- Remote clients connect to the Tailscale network and gain access to the **LAN** (`192.168.2.0/24`) and optionally the **DMZ** (`192.168.3.0/24`).