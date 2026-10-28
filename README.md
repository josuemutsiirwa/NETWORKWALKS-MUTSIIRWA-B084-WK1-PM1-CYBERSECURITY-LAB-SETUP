# NETWORKWALKS-MUTSIIRWA-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP

![VirtualBox](https://img.shields.io/badge/VirtualBox-VM-blue)
![Kali Linux](https://img.shields.io/badge/Kali-Linux-blue)
![Cybersecurity](https://img.shields.io/badge/Project-Cybersecurity-red)

## Project Overview

This repository documents my Week 1 cybersecurity lab setup for NetworkWalks.

The project involves installing and configuring VirtualBox, setting up Kali Linux as the attacking machine, configuring a NAT Network, assigning a static IP address, and verifying internet connectivity.

## Objectives

- Install and configure VirtualBox.
- Set up Kali Linux as the attacking machine.
- Create a NAT Network using the `10.0.0.0/24` subnet.
- Configure Kali Linux with the static IP address `10.0.0.2/24`.
- Ensure Kali Linux has full internet access.
- Enable bidirectional shared clipboard and drag-and-drop.
- Configure a shared folder between Windows and Kali Linux.
- Verify network configuration and connectivity.

## Lab Environment

| Component | Configuration |
|---|---|
| Host Operating System | Windows |
| Virtualization Software | Oracle VirtualBox |
| Attacking Machine | Kali Linux |
| Network Mode | NAT Network |
| Network Name | NatNetwork |
| Network Subnet | 10.0.0.0/24 |
| Kali Linux IP Address | 10.0.0.2/24 |
| Gateway | 10.0.0.1 |
| Internet Access | Required |
| Shared Folder | Windows Downloads folder |

## Implementation and Evidence

### 1. VirtualBox Installation

VirtualBox is used to create and manage the virtual machine environment for the cybersecurity lab.

![VirtualBox Version](01-vm-installation.png)

### 2. NAT Network Configuration

The NAT Network is configured with the required IPv4 subnet `10.0.0.0/24`.

![NAT Network Settings](02-nat-network.png)

### 3. Kali Linux Network Adapter

The Kali Linux virtual machine is connected to the configured NAT Network.

![Kali Network Adapter](03-kali-VM-NATNetwotk-settings.png)

### 4. Shared Clipboard and Drag-and-Drop

Bidirectional shared clipboard and drag-and-drop are configured to support file and text transfer between Windows and Kali Linux.

![Clipboard and Drag-and-Drop](04-shared-clipboard-drag-drop..png)

### 5. Shared Folder Configuration

A shared folder is configured to provide access to the Windows Downloads folder from Kali Linux.

![Shared Folder Settings](05-shared-downloads.png)

### 6. Kali Linux IP Address

The Kali Linux network interface is configured to use the required IP address `10.0.0.2/24`.

![Kali IP Address](06-kali-ip-address.png)

### 7. Routing Table Verification

The routing table is checked to confirm the configured network route and default gateway.

![IP Route](07-ip-route.png)

### 8. Gateway Connectivity Test

The gateway is tested using the `ping` command.

![Gateway Ping](08-gateway-ping.png)

### 9. Internet Connectivity Test

Internet connectivity is tested using an external IP address.

![Internet Connectivity](09-internet-connectivity.png)

### 10. DNS Resolution Test

DNS resolution is tested to confirm that domain names can be resolved to IP addresses.

![DNS Resolution](10-dns-resolution.png)

## Challenges and Troubleshooting

This section documents any configuration issues encountered during setup and the steps taken to resolve them.

## Conclusion

This project demonstrates the setup of a cybersecurity testing environment using VirtualBox and Kali Linux. It covers virtual networking, IP address configuration, shared resources, and connectivity verification.

The screenshots provide evidence of the configuration and testing performed.

## Author

**Name:** MUTSIIRWA

**Project Code:** B084

**Assignment:** WK1-PM1

**Program:** Cybersecurity internship
