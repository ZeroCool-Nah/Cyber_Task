# TryHackMe - What is Networking?

## Overview

This repository contains my notes and completed tasks from the **What is Networking?** room on TryHackMe.

The room introduces the basic concepts of computer networking, explaining how devices communicate over networks and the Internet. It covers IP addresses, MAC addresses, public and private networks, IPv4 and IPv6, and the use of ICMP for testing network connectivity.

**Platform:** TryHackMe  
**Room:** What is Networking?

---

## Learning Objectives

After completing this room, I was able to:

- Understand what computer networking is
- Differentiate between public and private networks
- Learn the purpose of IP and MAC addresses
- Compare IPv4 and IPv6
- Understand how devices communicate across networks
- Use the `ping` command to test connectivity
- Build a networking foundation for cybersecurity

---

# Task 1 – What is Networking?

## What is Networking?

Networking is the process of connecting two or more devices so they can exchange information and share resources.

Examples include:

- Browsing websites
- Sending emails
- Downloading files
- Playing online games
- Video conferencing

---

# Task 2 – What is the Internet?

The Internet is a global network made up of millions of connected devices.

It allows computers around the world to communicate using standard networking protocols.

### Benefits

- Fast communication
- Information sharing
- Cloud services
- Online learning
- Remote collaboration

---

# Task 3 – Identifying Devices on a Network

Every device connected to a network requires an address.

## IP Address

An IP address is a logical address assigned to a device.

Example:

```
192.168.1.10
```

It helps devices find and communicate with each other.

---

## MAC Address

A MAC (Media Access Control) address is a unique physical address assigned to a network interface.

Unlike an IP address, a MAC address normally remains fixed for the hardware.

Example:

```
00:1A:2B:3C:4D:5E
```

---

# Task 4 – Public vs Private Networks

## Public Network

A public network is accessible by anyone.

Examples:

- Internet
- Public Wi-Fi

Characteristics:

- Accessible worldwide
- Less secure
- Uses public IP addresses

---

## Private Network

A private network is limited to authorized users.

Examples:

- Home Wi-Fi
- School network
- Office network

Characteristics:

- More secure
- Uses private IP addresses
- Not directly accessible from the Internet

---

# Task 5 – IPv4 and IPv6

## IPv4

- 32-bit addressing
- Four decimal numbers separated by dots

Example:

```
192.168.1.1
```

Advantages

- Simple
- Widely supported

Limitation

- Limited number of available addresses

---

## IPv6

- 128-bit addressing
- Uses hexadecimal values

Example:

```
2001:0db8:85a3::8a2e:0370:7334
```

Advantages

- Huge address space
- Better scalability
- Improved efficiency

---

# Task 6 – Ping (ICMP)

## What is Ping?

The `ping` command checks whether another device is reachable on a network.

Example:

```bash
ping google.com
```

Ping uses the **Internet Control Message Protocol (ICMP)** to send Echo Requests and receive Echo Replies.

Common uses:

- Verify network connectivity
- Measure response time
- Troubleshoot network issues

---

# Important Networking Terms

| Term | Description |
|------|-------------|
| Network | A group of connected devices |
| Internet | Global network connecting millions of devices |
| IP Address | Logical address used for communication |
| MAC Address | Physical hardware address |
| IPv4 | 32-bit addressing system |
| IPv6 | 128-bit addressing system |
| ICMP | Protocol used by Ping |
| Ping | Tests connectivity between devices |

---

# Commands Practiced

## Test connectivity

```bash
ping google.com
```

Example output:

```
64 bytes from ...
Reply from ...
```

---

# Skills Gained

- Basic networking concepts
- Understanding Internet communication
- Identifying devices using IP addresses
- Understanding MAC addresses
- Comparing IPv4 and IPv6
- Testing connectivity using Ping
- Troubleshooting simple networking problems

---

# Room Summary

During this room I learned:

- How networks allow devices to communicate
- The difference between the Internet and private networks
- Why every device needs an IP address
- The purpose of MAC addresses
- Why IPv6 was introduced
- How ICMP and Ping help diagnose network connectivity

---

# Flags / Answers

| Task | Answer |
|------|--------|
| Networking Room | Successfully completed all questions and practical exercises ✅ |

> **Note:** This room primarily focuses on answering conceptual questions and does not include traditional Capture-the-Flag (CTF) flags like `THM{YOU_GOT_ON_TRYHACKME}`. The completion of all tasks verifies understanding of the networking concepts. :contentReference[oaicite:1]{index=1}

---
---
# Screenshots 

---

# Conclusion

The **What is Networking?** room provided an excellent introduction to computer networking. Understanding how devices communicate, how IP and MAC addresses work, and how tools like Ping test connectivity is essential for anyone beginning a journey in cybersecurity. These concepts serve as the foundation for more advanced networking, penetration testing, and network security topics.

---

**Completed by:** Nahusenai Minalu  
**Platform:** TryHackMe  
**Status:** ✅ Completed
