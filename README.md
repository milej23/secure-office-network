# secure-office-network

This project simulates a secure office network using Cisco Packet Tracer. It includes VLAN segmentation, inter-VLAN routing, router-to-router connection, internet simulation via the Cloud, and firewall/router security configurations.

## Topology Components
- Cloud-PT: Simulates the internet
- 2x Routers: ISR4331
- 3x Switches: 2960-24TT and 24PS
- Firewall: (If configured, specify device or simulated via ACLs)
- PCs: Clients across multiple VLANs (Admin, Guest, etc.)
- Server: Internal resource
- VLANs: Configured for segmentation and access control

## Key Features

- VLAN Segmentation
- Router on a stick
- Inter-VLAN Routing
- SSH/ACL simulation
- Internet access simulation
- Ping and Web browser testing


##  Notes

- **Cloud-PT** simulates the internet. You cannot ping the cloud, but you can use it to forward internet traffic via a modem or router.
- Ensure `NAT`, `route`, or `default gateway` are configured properly for internet access.
- PC web browser tool can be used to test HTTP access.
- Packet loss may occur if **routing** or **ACLs** are misconfigured.

## Security Configurations

- Port Security on switches
- Access Control Lists (ACLs) on routers
- SSH access to router

