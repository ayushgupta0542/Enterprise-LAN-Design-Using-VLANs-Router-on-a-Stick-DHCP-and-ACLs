# Enterprise-LAN-Design-Using-VLANs-Router-on-a-Stick-DHCP-and-ACLs
Overview
Built and configured a secure enterprise network in Cisco Packet Tracer using VLAN segmentation, Router-on-a-Stick for Inter-VLAN Routing, DHCP for automated IP address allocation, and ACLs for traffic filtering. Verified connectivity and enforced access policies across multiple VLANs.

# Scenario
You work as the network administrator for a small branch office. The office has 3 departments – Admin, Sales and IT . Your management has asked you to design and implement a secure and efficient network using Cisco Packet Tracer. The network will function autonomously from the head office and must satisfy the following:
a) There will be two Cisco switches and one Cisco router.
b) Three departments: Admin (VLAN 10), Sales (VLAN 20) and IT (VLAN 30).
c) Trunk links should be configured between router and switches and between switches.
d) All VLANs should be able to communicate with the Router-on-a-Stick configuration.
e) All devices should receive IP addresses automatically from a DHCP server configured on the router.
f) ACL restriction: Sales VLAN (VLAN 20) should NOT be able to reach the IT VLAN (VLAN 30), but all other communication should be allowed.

# Network Topology
![image alt](https://github.com/ayushgupta0542/Enterprise-LAN-Design-Using-VLANs-Router-on-a-Stick-DHCP-and-ACLs/blob/60e9a2f76a6c8a9339b5dc42d0553eff79098000/Network%20Topology.png)

# VLAN Creation
Configured VLAN segmentation in Cisco Packet Tracer to logically separate network traffic, improve security, and enable efficient communication between departments.
Three Departments were created as Admin, Sales, IT and are logically separate network traffic.
![image alt](https://github.com/ayushgupta0542/Enterprise-LAN-Design-Using-VLANs-Router-on-a-Stick-DHCP-and-ACLs/blob/fa83d5db7f5f9f1ff34f95f15b16fb6557b0ec5d/VLAN%20on%20Switch%201.png)

# Trunking
Configured IEEE 802.1Q trunk links in Cisco Packet Tracer to carry traffic from multiple VLANs across switches and enable efficient network segmentation.
![image alt]()


