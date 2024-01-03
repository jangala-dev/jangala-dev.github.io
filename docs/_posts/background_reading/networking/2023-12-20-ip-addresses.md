---
layout: post
title: IP Addresses
meta: An IP address is a unique identifier for a device on a network...
posted: 12/20/2023
source: ''
category: background_reading/networking
---
## What is an IP Address?
An IP address is a unique identifier for a device on a network. It plays a crucial role in ensuring that data packets - small chunks of digital information - find their way to the correct destination, much like a postal address ensures your mail reaches your doorstep.

## What Role do IP Addresses Serve?

When a device, such as your computer, wants to send or receive information to another device (for example, accessing a website hosted on a server in some data center), it breaks the information into packets. Each packet is tagged with the IP address of the destination device.

Within a smaller network, like a home or office network (Local Area Network, or LAN), IP addresses are used to identify specific devices or applications. This helps in efficient communication and data transfer within the local network.

If the destination IP address is not on the local network, the network's router passes the packet onto a wider network, the Wide Area Network (WAN), where other routers further assist in guiding the packet to its final destination.

__Communication over the internet__: 

## Types of IP Addresses

There are various categorisations of IP addresses that you will commonly come across in networking discussions, and it's important to understand these distinctions.

### IPv4 vs. IPv6
There are two versions of IP addresses. IPv4, the older version, consists of four integers between 0 and 255, inclusive, separated by periods (e.g., 192.168.1.1). However, due to the vast number of devices online, IPv4 addresses are running out. This led to the creation of IPv6, which has a much larger address space. An IPv6 address looks quite different, consisting of eight groups of four hexadecimal digits, separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

### Static vs. Dynamic IP Addresses
Static IP Addresses remain constant every time a device joins a network. They are useful for devices that need a permanent address, like a printer within an office network.
Dynamic IP Addresses change each time a device connects to the network. These are assigned by a DHCP (Dynamic Host Configuration Protocol) server, usually a router, and are common in home and business networks for devices like laptops and smartphones.

### Private vs. Public IP Addresses
Private IP Addresses are used within a LAN and don't need to be unique across the entire internet. These addresses allow multiple devices to have a distinct identity within a local network.
Public IP Addresses are used on the WAN and must be unique across the entire internet. Your home or office network will have a public IP address that connects it to the wider internet.

## Conclusion
Understanding IP addresses is key to grasping how the internet works. They are the cornerstone of network communication, ensuring that data packets reach their intended destinations. Whether it's a local network in your home or the vast internet, IP addresses keep our digital world interconnected and functioning smoothly.
