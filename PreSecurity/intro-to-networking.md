# Intro to Networking 🌐

**Platform**: TryHackMe  
**Room**: [Intro to Networking](https://tryhackme.com/room/introtonetworking)  
**Difficulty**: Easy  
**Tags**: `#networking`, `#basics`, `#ip`, `#dns`, `#subnetting`  
**Date Completed**: March 2025

---

## 🎯 Objectives

- Understand what networks are and how data moves through them
- Learn about IP addresses, MAC addresses, DNS, DHCP, and subnetting
- Practice basic networking tools and concepts

---

## 🔧 Key Concepts

### 🧩 What is a Network?
- A group of devices connected to share resources and data.
- Can be **LAN** (Local) or **WAN** (Wide), public or private.

### 📇 IP vs MAC
- **IP address** = Logical address (e.g., `192.168.1.10`)
- **MAC address** = Physical hardware address (e.g., `00:1B:44:11:3A:B7`)

### 🌍 Public vs Private IPs
- **Private IPs**: Not routable on the internet (e.g., `192.168.x.x`, `10.x.x.x`)
- **Public IPs**: Routable on the internet

### 🧙 DNS (Domain Name System)
- Converts domains like `google.com` into IPs
- Tool used: `nslookup`, `dig`

### nslookup tryhackme.com
dig tryhackme.com +short


## 🧅 DHCP (Dynamic Host Configuration Protocol)

Automatically assigns IP, gateway, DNS server to devices

## 🧮 Subnetting

    Used to divide a network into smaller sub-networks

    Example: 192.168.1.0/24 has 256 IPs (254 usable)


# Practice Highlights

## Ping
```ping 8.8.8.8```

- Sends ICMP packets
- Measures latency and reachability

## 🔍 Traceroute
```traceroute tryhackme.com```

- Maps route packets take to reach a host
- Useful for identifying network hops and delays

## 🧰 ipconfig / ifconfig

``ipconfig  # Windows``
``ifconfig  # Linux``
- Shows local IP address, gateway, etc.


## 📚 Learned Commands

| Command             | Purpose                 |
|---------------------|-------------------------|
| `ping`              | Test connectivity       |
| `traceroute`        | Track route to host     |
| `ipconfig` / `ifconfig` | Show network config    |
| `nslookup` / `dig`  | DNS queries             |
| `whois`             | Info on domain ownership |


🧠 Final Thoughts

This room sets a solid foundation for anyone diving into pentesting or blue team work. Even experienced hackers should revisit networking basics now and then—it all starts here.

    🔥 "Before you pwn ports, understand the wires." — Goblin proverb

🧤 This writeup is part of my personal cybersecurity journey. For educational use only.

