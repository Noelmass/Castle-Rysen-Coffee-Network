# Castle Rysen Network Security Architecture

A beginner-level Cisco networking and network security project built in Cisco Packet Tracer as part of a CCNA-focused learning project.

## Project Overview

Castle Rysen Coffee is a fictional organization requiring a scalable network infrastructure connecting its cafe environment and a central fallout shelter.

The project was built from the requirements defined in the Castle Rysen Coffee RFP and implemented progressively while studying CCNA networking concepts.

The main goal of this project was to gain practical experience designing, configuring, securing, and troubleshooting a small enterprise-style network.

## Architecture

The project contains two primary network environments:

### Cafe Network

The cafe network provides connectivity for:

- Administration
- Cafe patrons / guests
- Network infrastructure and services
- Wireless access
- Plex-based media services

### Fallout Shelter Network

The fallout shelter provides a larger network environment containing separate segments for:

- Network Management
- Internal users
- Video surveillance
- Guests

The shelter also provides upstream connectivity toward the Internet and the cafe network.

## Main Technologies Implemented

### Layer 2

- VLAN segmentation
- 802.1Q trunking
- Rapid-PVST / STP
- PortFast
- BPDU Guard
- LACP EtherChannel
- Switch port security

### Layer 3

- IPv4 addressing and subnetting
- IPv6 addressing
- Inter-VLAN routing
- OSPF
- Static/default routing
- HSRP
- NAT/PAT

### Network Services

- DHCP
- DNS-related configuration
- NTP
- SSH
- Syslog
- SNMP-related configuration
- QoS concepts/configuration

### Security

- VLAN-based network segmentation
- Extended and standard ACLs
- Management-plane access restrictions
- Switch port security
- DHCP Snooping / Dynamic ARP Inspection concepts
- SSH-based administrative access

## Project Objectives

The project was designed to provide:

- Structured IP addressing
- Logical network segmentation
- Inter-VLAN communication
- Dynamic routing
- Gateway redundancy
- Internet connectivity
- Basic network security controls
- Secure remote device administration
- Practical Cisco configuration experience

## Network Security Approach

Security was implemented primarily through segmentation and access control.

Different types of systems are placed into separate VLANs so that network traffic can be controlled at Layer 3. ACLs are used where required to restrict communication between network segments and management access is separated from normal user traffic.

Layer 2 security mechanisms such as port security, DHCP Snooping, DAI, PortFast, and BPDU Guard were also explored as part of the project.

## Learning Context

This project was developed alongside a four-month CCNA study plan covering networking fundamentals, switching, routing, subnetting, VLANs, STP, EtherChannel, OSPF, HSRP, IPv6, ACLs, Layer 2 security, network services, monitoring, QoS, wireless networking, and network automation concepts.

The study progression included dedicated Castle Rysen implementation exercises throughout the course, followed by project completion and documentation.

## Validation

The final Packet Tracer topology is included in:

```text
packet-tracer/network-project.pkt
```

The `documentation/` directory contains the supporting project documentation, including the topology, addressing plan, security design, and testing results.

## Disclaimer

This is an educational CCNA-level Packet Tracer project. It is intended to demonstrate practical networking and introductory network-security concepts rather than represent a production enterprise deployment.

Some features and behaviors are represented within the limitations of Cisco Packet Tracer and the scope of the project.
