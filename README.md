# AWS-VPC

![Screenshot](Screenshot%202022-08-30%20at%2014.40.05.png)

## What is VPC?

A virtual private cloud (VPC) is a secure, isolated private cloud hosted within a public cloud. VPC customers can run code, store data, host websites, and do anything else they could do in an ordinary private cloud, but the private cloud is hosted remotely by a public cloud provider.

### Subnet

Subnets: A subnet is a range of IP addresses within a network that are reserved so that they're not available to everyone within the network, essentially dividing part of the network for private use. In a VPC these are private IP addresses that are not accessible via the public Internet, unlike typical IP addresses, which are publicly visible.

## IP addressing
We can assign IPv4 addresses and IPv6 addresses to our VPCs and subnets. We can also bring your public IPv4 and IPv6 GUA addresses to AWS and allocate them to resources in your VPC, such as EC2 instances, NAT gateways, and Network Load Balancers.

## Routing
We use route tables to determine where network traffic from your subnet or gateway is directed.

## Gateways and endpoints
A gateway connects your VPC to another network. For example, use an internet gateway to connect your VPC to the internet. Use a VPC endpoint to connect to AWS services privately, without the use of an internet gateway or NAT device.

## CIDR

- Classless Inter-Domain Routing, or CIDR, is a means of allocating Internet Protocol addresses, also known as host addresses, more efficiently compared to the traditional classful network addressing system.
- CIDR blocks represent groups of IP addresses that have the same network prefixes and number of bits. Combining CIDR blocks that share a network prefix into a larger routing network is called supernetting, the single most important trait of CIDR.
