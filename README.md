# SOHO Network Lab

## Overview

This project simulates a **Small Office/Home Office (SOHO) network** using Cisco Packet Tracer. The objective was to design and configure a functional network that provides automatic IP address assignment, DNS name resolution, and web server access for multiple client devices.

## Network Topology

### Devices Used
- Cisco 1941 Router
- Cisco Catalyst 3650 Multilayer Switch
- 2 Client PCs
- Web Server
- DNS/DHCP Server
- Network Printer

## Project Objectives

- Design a basic SOHO network
- Configure network devices for communication
- Automatically assign IP addresses using DHCP
- Configure DNS for hostname resolution
- Deploy a web server accessible by domain name
- Verify network connectivity between all devices

## Configuration

### Router
- Configured as the default gateway for the network.

### Multilayer Switch
- Connected all network devices.
- Forwarded traffic between connected hosts.

### DHCP Server
- Configured a DHCP pool to automatically assign:
  - IP Address
  - Subnet Mask
  - Default Gateway
  - DNS Server

### DNS Server
Configured DNS to resolve:

```
www.alianit.com → 192.168.1.3
```

### Web Server
- Assigned a static IPv4 address.
- Enabled HTTP service.
- Hosted a test webpage accessible by hostname.

### End Devices
Configured client PCs and printer to obtain network settings automatically using DHCP.

## Testing and Verification

The following tests were successfully completed:

- Successfully received IP addresses through DHCP
- Verified connectivity using the `ping` command
- Confirmed communication between all devices
- Successfully resolved **www.alianit.com** using DNS
- Accessed the hosted webpage through a web browser
- Verified printer connectivity on the network

## Skills Demonstrated

- IPv4 Addressing
- DHCP Configuration
- DNS Configuration
- Router Configuration
- Layer 3 Switching
- Static and Dynamic IP Configuration
- Web Server Configuration
- Network Troubleshooting
- Connectivity Testing
- Cisco Packet Tracer

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4
- DHCP
- DNS
- HTTP

## Future Improvements

- Implement VLAN segmentation
- Configure inter-VLAN routing
- Configure NAT for simulated Internet access
- Add Access Control Lists (ACLs)
- Add wireless connectivity
- Implement network security best practices

## Project Screenshot
<img width="1826" height="775" alt="image" src="https://github.com/user-attachments/assets/2aa106ca-3f5c-416a-bcd7-21edd9b5b015" />


