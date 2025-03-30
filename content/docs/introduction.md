---
title: Introduction
weight: 1
next: /docs/installation
prev: /docs
---

👋 Welcome to my ProxLink Project Documentation!

## What is ProxLink?

ProxLink is more than just a project, ProxLink is my exploration into building a versatile home lab using open-source technologies like Proxmox, pfSense, Tailscale, and TrueNAS. It enables me to test cybersecurity concepts, virtualized environments, networking strategies, and software integrations securely and conveniently at home.


## Network Topology
![Network](/images/ProxLink.png)

{{< cards >}}
  {{< card link="/docs/network/" title="Network Configuration" icon="document-text" subtitle="Managing virtual networks within Proxmox environment." >}}
  {{< card link="/docs/firewall/" title="Firewall Configuration" icon="document-text" subtitle="Securing the network using pfSense firewall rules." >}}
  {{< card link="/docs/vpn/" title="VPN Configuration" icon="document-text" subtitle="Enabling remote access through Tailscale VPN." >}}
{{< /cards >}}

## Features

- **Powerful Virtualization** - Easily manage virtual machines and containers through Proxmox VE’s intuitive web interface, delivering flexibility and scalability for your home lab.
- **Robust Network Security** - Leverage PfSense firewall/router integration to provide advanced security, VPN functionality, traffic shaping, and comprehensive monitoring.
- **Seamless Remote Access** - Utilize TailScale's secure VPN solution, allowing secure and reliable remote connectivity with minimal setup and zero-maintenance requirements.
- **Reliable Storage Management** - Organize and protect your data efficiently using TrueNAS, offering resilient storage solutions with advanced snapshotting, redundancy, and file-sharing capabilities.
- **Extensible and Customizable** - Expand and customize your home lab environment with scripting, automation, detailed documentation, and powerful integrations.
- **Optimized for Learning and Growth** - Whether you're new to virtualization or a seasoned IT pro, ProxLink offers an accessible learning environment and practical tools to build expertise.


## Hardware Configuration

To create a reliable yet compact setup, I've carefully selected the following hardware components:

#### **1. Beelink SER5 Pro Mini PC**
- **Processor**: AMD Ryzen 7 5800H (8C/16T, Up to 4.4GHz)
- **RAM**: 32GB DDR4
- **Storage**: 1TB NVMe SSD
- **Graphics**: Integrated AMD Radeon (Supports 4K@60Hz Output)
- **Networking**:
  - **WiFi 6** (Primary connection)
  - **Bluetooth 5.2**
  - **Ethernet via WiFi Extender**
- **Operating System**: Proxmox VE 8.x (Replaces Windows 11 Pro)

#### **2. WiFi Extender (Ethernet Connection)**
- Extends network coverage for Proxmox.
- Provides an **Ethernet bridge** for better stability.

#### **3. Cooling System (Optional)**
- An external cooling fan or additional thermal management can be used to maintain performance under high loads.

#### **4. Small Rack for Organization (Optional)**
- A small rack is used to neatly organize the mini PC and manage cables, ensuring a tidy setup and improved airflow.

## Questions or Feedback?

{{< callout emoji="❓" >}}
  ProxLink is still in active development.
  Have a question or feedback? Feel free to [open an issue](https://github.com/heydc7/proxlink)!
{{< /callout >}}
