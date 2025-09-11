# ACL – Trainee Guide

## Goals

- The trainee will be familiar with ACL and it types
- The trainee will have an understanding on creating ACLs

## Tasks

- Read about [Access-Lists](https://www.cisco.com/c/en/us/support/docs/security/ios-firewall/23602-confaccesslists.html)
- What is an Access Control List (ACL) in networking, and what is its primary purpose?
- Explain about the different types of ACLs.
- When should we use standard or extended ACL?
- How do you apply an ACL to an interface on a router or switch?
- How can you log matches to ACL rules for auditing or troubleshooting purposes?
- Explain that parts of a line in an ACL.
- What is the Remark part in the ACL?
- Configure ACLs in your lab environment. Make sure it works.

### Addressing Table

| Hostname | Interface | IP Address     |
|----------|-----------|----------------|
| R1       | G0/0      | 192.168.10.1/24|
| R1       | G0/1      | 192.168.20.1/24|
| S1       | Vlan10    | 192.168.10.2/24|
| S2       | Vlan20    | 192.168.20.2/24|
| PC1      | NIC       | 192.168.10.10/24 (Vlan 10)|
| PC2      | NIC       | 192.168.10.20/24 (Vlan 10)|
| PC3      | NIC       | 192.168.20.10/24 (Vlan 20)|
| PC4      | NIC       | 192.168.20.20/24 (Vlan 20)|

### Lab Tasks

- Configure interfaces and assign IP addresses. (Verify all PCs can ping each other.)
- Create a standard ACL to block PC1 (192.168.10.10) from accessing any device in VLAN 20 (192.168.20.0/24). (Apply the ACL in the correct direction and interface.)
- Create an extended ACL to allow only HTTP (port 80) traffic from PC2 (192.168.10.20) to PC3 (192.168.20.10), but deny all other traffic between these two hosts.
- Verify the following:
    1. PC1 cannot ping or access any device in VLAN 20.
    2. PC2 can access HTTP on PC3, but cannot ping or use other protocols.
    3. All other traffic is unaffected.
