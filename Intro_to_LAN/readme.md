# TryHackMe - Intro to LAN

## Overview

This repository contains my notes and learning outcomes from the **Intro to LAN** room on TryHackMe.

The room introduces the fundamentals of Local Area Networks (LANs), including network topologies, subnetting, ARP, and DHCP. Understanding these concepts provides a strong networking foundation for cybersecurity and penetration testing.

**Platform:** TryHackMe  
**Room:** Intro to LAN

---

## Learning Objectives

After completing this room, I was able to:

- Understand what a Local Area Network (LAN) is
- Compare different network topologies
- Learn the role of routers and switches
- Understand why subnetting is important
- Learn how ARP resolves IP addresses to MAC addresses
- Understand how DHCP automatically assigns IP addresses
- Build a stronger networking foundation for cybersecurity

---

# Task 1 – Introducing LAN Topologies

## Topics Covered

### Local Area Network (LAN)

A Local Area Network (LAN) connects multiple devices within a limited geographic area, such as a home, school, or office.

### Router

A router connects different networks together and forwards data between them through a process called **routing**.

### Switch

A switch connects multiple devices inside the same local network and forwards data only to the intended destination.

### Network Topologies

I learned about three common LAN topologies:

### Star Topology

Advantages

- Reliable
- Easy to troubleshoot
- One cable failure doesn't stop the network
- Most commonly used today

Disadvantages

- Requires more cabling
- More expensive because it depends on a central switch

---

### Bus Topology

Advantages

- Simple design
- Low installation cost

Disadvantages

- Difficult to troubleshoot
- Backbone cable failure can bring down the entire network

---

### Ring Topology

Advantages

- Predictable data flow
- Equal access for devices

Disadvantages

- One failure may interrupt communication
- More difficult to maintain

---

## Practical Lab

Completed the interactive LAN topology exercise and observed how different network designs react when devices or cables fail.

---

# Task 2 – A Primer on Subnetting

## What is Subnetting?

Subnetting is the process of dividing a large network into smaller networks.

Benefits include:

- Better organization
- Improved security
- Reduced network congestion
- Efficient IP address management

---

## Important Address Types

### Network Address

Identifies the network itself.

Example:

192.168.1.0

---

### Host Address

Identifies an individual device within the network.

Example:

192.168.1.100

---

### Default Gateway

The device responsible for forwarding traffic outside the local network.

Example:

192.168.1.254

---

# Task 3 – ARP (Address Resolution Protocol)

## What is ARP?

ARP (Address Resolution Protocol) maps an IP address to a MAC address.

### ARP Request

Broadcasts a request asking:

> "Who owns this IP address?"

### ARP Reply

The device owning that IP address responds with its MAC address.

---

## Key Concepts

### MAC Address

- Physical hardware identifier
- Unique to each network interface

### IP Address

- Logical network identifier
- Used for communication across networks

---

# Task 4 – DHCP

## What is DHCP?

Dynamic Host Configuration Protocol (DHCP) automatically assigns IP addresses to devices joining a network.

Without DHCP, every device would need to be configured manually.

---

## DHCP Process

The process follows four steps:

1. Discover
2. Offer
3. Request
4. Acknowledge (ACK)

This process is commonly abbreviated as:

DORA

---

# Key Networking Terms Learned

| Term | Description |
|------|-------------|
| LAN | Local Area Network |
| Router | Connects different networks |
| Switch | Connects devices within a LAN |
| Topology | Physical or logical network layout |
| Subnetting | Dividing a network into smaller networks |
| ARP | Resolves IP addresses to MAC addresses |
| DHCP | Automatically assigns IP addresses |
| MAC Address | Physical hardware address |
| IP Address | Logical network address |
| Default Gateway | Sends traffic to other networks |

---

# Skills Gained

- Basic networking concepts
- Understanding LAN communication
- Identifying different network topologies
- Understanding subnetting fundamentals
- Learning ARP communication
- Understanding automatic IP assignment with DHCP
- Building networking knowledge for cybersecurity

---

# Key Takeaways

- Most modern networks use the **Star Topology** because it is reliable and scalable.
- Routers forward traffic between different networks.
- Switches efficiently connect devices within a LAN.
- Subnetting improves network organization and security.
- ARP maps IP addresses to MAC addresses.
- DHCP simplifies network administration by automatically assigning IP addresses.

---
---
# Screenshots

## LAN Topologies 
![LAN Topologies](LAN_images

---

# Conclusion

The **Intro to LAN** room provided a solid introduction to networking concepts that are essential for anyone pursuing cybersecurity or ethical hacking. Understanding how devices communicate on a network makes it easier to analyze network traffic, troubleshoot issues, and prepare for more advanced topics such as network security, penetration testing, and packet analysis.

---

**Completed by:** Nahusenai Minalu  
**Platform:** TryHackMe  
**Status:** ✅ Completed
