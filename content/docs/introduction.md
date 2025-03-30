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

## Configuration
{{< cards >}}
  {{< card link="/docs/hardware/" title="Hardware Configuration" icon="chip" subtitle="Overview of the hardware powering the ProxLink." >}}
  {{< card link="/docs/network/" title="Network Configuration" icon="globe-alt" subtitle="Managing virtual networks within Proxmox." >}}
  {{< card link="/docs/firewall/" title="Firewall Configuration" icon="shield-check" subtitle="Securing the network using pfSense firewall rules." >}}
  {{< card link="/docs/vpn/" title="VPN Configuration" icon="lock-closed" subtitle="Enabling remote access through Tailscale VPN." >}}
{{< /cards >}}

## Features

- **Powerful Virtualization** – ProxLink leverages Proxmox VE's intuitive web interface to efficiently manage virtual machines and containers, ensuring flexibility and scalability.

- **Robust Network Security** – The lab integrates pfSense firewall/router capabilities, delivering advanced security features, VPN connectivity, and comprehensive network monitoring.

- **Seamless Remote Access** – TailScale provides secure, reliable remote connectivity within the lab environment, with minimal setup and low-maintenance operation.

- **Reliable Storage Management** – TrueNAS is used for data organization, advanced snapshotting, redundancy, and secure file-sharing, enhancing overall data resilience. (In-Progress)

- **Extensible and Customizable** – ProxLink offers extensibility through scripting, automation, thorough documentation, and powerful integrations, allowing flexible customization.

- **Optimized for Learning and Growth** – The project is structured to provide a practical, accessible learning environment suitable for all skill levels, from beginners to experienced IT professionals.

## Questions or Feedback?

{{< callout emoji="❓" >}}
  ProxLink is still in active development.
  Have a question or feedback? Feel free to [open an issue](https://github.com/heydc7/proxlink)!
{{< /callout >}}
