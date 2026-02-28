# linux-personal-firewall
Designed and implemented a Linux host-based firewall using iptables to enforce a default-deny policy, restrict unauthorized access, and secure network traffic through rule-based IP and port filtering.
# Linux Personal Firewall

## Overview
This project demonstrates the design and implementation of a basic personal firewall using iptables on Linux. The firewall is configured to block unauthorized access, filter IP traffic, and enforce secure communication policies.

## Objectives
- Understand networking fundamentals and packet filtering
- Configure IP-based filtering rules
- Block unauthorized inbound traffic
- Allow only trusted services and ports
- Implement default-deny security model

## Features
- Drops all unsolicited incoming connections
- Allows established and related connections
- Supports whitelist-based IP filtering
- Blocks unused ports
- IPv4 and IPv6 rule support

## Technologies Used
- Linux
- iptables / ip6tables
- Netfilter Framework

## Learning Outcomes
- Practical firewall rule configuration
- Hands-on experience with Linux networking
- Understanding of traffic filtering and port control
- Implementation of host-based security controls

## Future Improvements
- Add logging and monitoring
- Implement intrusion detection rules
- Create automated rule management scripts
