📌 What is a Network?
A network = devices connected together to communicate
Can range from 2 devices → billions of devices
Examples:
Internet
Power grid
Transport systems

💡 In computing:

Network = interconnected devices (phones, laptops, servers, etc.)

🌍 What is the Internet?
The Internet = network of networks
Made up of:
Private networks (small/local)
Public networks (Internet itself)
📜 History:
First network: ARPANET (1960s)
Modern Internet (WWW): Tim Berners-Lee (1989)
🔑 Types of Networks
Type	Description
Private Network	Internal network (home, office)
Public Network	Global network (Internet)
🖥️ Identifying Devices on a Network

Devices have 2 identities:

1️⃣ IP Address (Changeable)
Logical address of a device
Used to identify device on a network

👉 Format:

IPv4 → 4 sections (octets)
Example: 192.168.1.1

📌 Types:

Private IP → inside local network
Public IP → on Internet (given by ISP)

💡 Important:

Same public IP can be shared (NAT)
IP can change over time
🌐 IPv4 vs IPv6
Feature	IPv4	IPv6
Size	32-bit	128-bit
Addresses	~4.3 billion	Huge (2^128)
Example	192.168.1.1	2001:db8::

📌 IPv6 solves IP shortage problem

2️⃣ MAC Address (Permanent)
Physical address of device
Assigned at factory
Format: a4:c3:f0:85:ac:2d

📌 Structure:

First 6 → Manufacturer
Last 6 → Unique device ID

⚠️ Can be spoofed (fake identity) → security risk

📡 Ping (ICMP)
What is Ping?
Tool to test connection between devices
Uses:
Check if device is reachable
Measure response time (latency)
Protocol:
Uses ICMP (Internet Control Message Protocol)
Syntax:
ping <IP or website>

Example:

ping 10.10.10.10

📌 Ping works using:

ICMP Echo Request
ICMP Echo Reply
🚀 Key Takeaways
Network = connected devices
Internet = network of networks
Devices identified by:
IP (logical, changeable)
MAC (physical, mostly fixed)
IPv6 solves IPv4 limitation
Ping helps test connectivity using ICMP
