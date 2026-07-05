# IPv4 Addressing

## Objective

To understand IPv4 addressing, its structure, address classes, private and public IP addresses, and subnet masks.

## What is an IPv4 Address?

An IPv4 (Internet Protocol Version 4) address is a 32-bit logical address used to identify devices on a network.

Example:
192.168.1.10

## Structure of an IPv4 Address

* 32 bits
* Divided into 4 octets
* Each octet ranges from 0 to 255

Example:

192.168.1.10

## IPv4 Address Classes

| Class | Range                       | Default Subnet Mask |
| ----- | --------------------------- | ------------------- |
| A     | 1.0.0.0 – 126.255.255.255   | 255.0.0.0           |
| B     | 128.0.0.0 – 191.255.255.255 | 255.255.0.0         |
| C     | 192.0.0.0 – 223.255.255.255 | 255.255.255.0       |
| D     | 224.0.0.0 – 239.255.255.255 | Multicast           |
| E     | 240.0.0.0 – 255.255.255.255 | Reserved            |

## Private IP Address Ranges

* 10.0.0.0 – 10.255.255.255
* 172.16.0.0 – 172.31.255.255
* 192.168.0.0 – 192.168.255.255

## Public IP Address

A public IP address is assigned by an Internet Service Provider (ISP) and is accessible over the Internet.

## Subnet Mask

A subnet mask separates the network portion from the host portion of an IP address.

Example:

IP Address: 192.168.1.10

Subnet Mask: 255.255.255.0

## Why IPv4 Addressing is Important

* Identifies devices on a network.
* Enables communication between systems.
* Supports routing across networks.
* Forms the foundation of TCP/IP networking.

## Skills Learned

* IPv4 Addressing
* IP Address Classes
* Private vs Public IP
* Subnet Masks
* Networking Fundamentals

