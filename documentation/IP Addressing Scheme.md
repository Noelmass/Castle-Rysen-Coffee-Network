IP Addressing Scheme



**1. Castle Rysen Central Office (\~200 Humans \~4000 IPs)**

&#x20;   Original Network
	10.0.0.0/20

**2. Castle Rysen Fallout Shelter (\~50 Humans \~500 IPs)**

&#x20;   Original Network

&#x09;10.0.16.0/23

&#x20;   Subnets

&#x09;VLAN 10 = Management

&#x09;VLAN 20 = Internal

&#x09;VLAN 30 = Video Surveillance

&#x09;VLAN 40 = Guest

&#x20;   IPv4 Scheme

&#x09;VLAN 10 - 10.0.16.0/25

&#x09;VLAN 20 - 10.0.16.128/25

&#x09;VLAN 30 - 10.0.17.0/25

&#x09;VLAN 40 - 10.0.17.128/25

&#x20;   IPv6 Scheme

&#x09;VLAN 10 - 2001:db8:1:4::1/64

&#x09;VLAN 20 - 2001:db8:1:5::1/64

&#x09;VLAN 30 - 2001:db8:1:6::1/64

&#x09;VLAN 40 - 2001:db8:1:7::1/64



**3. Castle Rysen District Shop (\~15 Humans \~50IPs)**

&#x20;   Original Network

&#x09;10.0.18.0/26

&#x20;   Subnets

&#x09;VLAN 10 = ADMIN

&#x09;VLAN 20 = PATRON-DEVICES

&#x20;   IPv4 Scheme

&#x09;VLAN 10 - 10.0.18.0/27

&#x09;VLAN 20 - 10.0.18.32/27

&#x20;   IPv6 Scheme

&#x09;VLAN 10 - 2001:db8:1:1::1/64

&#x09;VLAN 20 - 2001:db8:1:2::1/64



