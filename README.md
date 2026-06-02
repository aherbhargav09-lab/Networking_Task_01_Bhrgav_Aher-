NETWORKING TASK 01: UNDERSTANDING YOUR NETWORK ENVIRONMENT
Student Information

Name: Bhargav Aher
Date: 02 June 2026

Objective

The objective of this task is to understand the basic components of a computer network and identify the network configuration of my own system. This task also helps in learning networking tools such as ping and traceroute.

Part A: Network Information

The following network information was collected from my Kali Linux system.

Parameter	Value
Hostname	kali
IPv4 Address	192.168.181.136
MAC Address	00:0c:29:b9:98:27
Default Gateway	192.168.181.2
DNS Server	192.168.181.2
Part B: Basic Networking Concepts
1. What is an IP Address?

An IP Address (Internet Protocol Address) is a unique numerical address assigned to a device on a network. It allows devices to communicate with each other over a network.

2. What is a MAC Address?

A MAC (Media Access Control) Address is a unique hardware identifier assigned to a network interface card (NIC). It is used for communication within a local network.

3. What is a Default Gateway?

A Default Gateway is the router that forwards network traffic from a local network to external networks such as the Internet.

4. What is DNS?

DNS (Domain Name System) is a service that converts human-readable domain names such as google.com into IP addresses.

5. Difference Between Public IP and Private IP
Public IP	Private IP
Used on the Internet	Used inside local networks
Assigned by ISP	Assigned by local router
Globally unique	Reusable in different networks
Example: 8.8.8.8	Example: 192.168.181.136
Part C: Network Diagram

Network connection flow:

Internet

↓

Router / WiFi (192.168.181.2)

↓

Kali Linux Device (192.168.181.136)

Insert Network_Diagram.png here.

Part D: Network Connectivity Test
Command 1: Ping Test

Command Used:

ping google.com

Result
Packets Sent: 3
Packets Received: 3
Packet Loss: 0%
Was the ping successful?

Yes. The ping was successful because replies were received from Google's server with 0% packet loss.

Command 2: Traceroute Test

Command Used:

traceroute google.com

Result
Hop 1: 192.168.181.2
Remaining hops did not respond and displayed * * *
How many hops were shown?

One hop was successfully displayed.

What is the purpose of traceroute?

Traceroute is used to determine the path taken by data packets from a source device to a destination server. It helps identify network delays and connectivity problems.
