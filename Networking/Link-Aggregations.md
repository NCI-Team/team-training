# Link Aggregations – Trainee Guide

### Goals

- Understand what is PortChanneling and Virtual PortChanneling (VPC).
- Learn the diffrences between Port Channel and VPC.
- Understand when and how Port Channel and VPC are used.

### Tasks

- What is link aggregation, and why is it used in networking? (Explain the benefits)
- What is EtherChannel?
- Describe how EtherChannel works and its main configuration modes.


#### PortChannel
- What is a Port Channel (PC)?
- How does a Port Channel combine multiple physical links?
- What protocols can be used for Port Channel negotiation?
- What happens if one of the physical links in a Port Channel fails?
- How does load balancing work in a Port Channel?
- What parameters must match on both ends of a Port Channel to form successfully?
- How would you identify and resolve a misconfigured Port Channel? 


#### VPC
- What is a Virtual Port Channel (VPC)?
- How is a VPC different from a traditional Port Channel?
- What is the purpose of the VPC peer-link?
- What are the main advantages of using VPC in a data center environment?
- What are the potential risks if the VPC peer-link goes down?


---

#### 🧪 Lab: Configuring PortChannel (EtherChannel) in Cisco Packet Tracer

##### 🎯 Objective
- Configure a Layer 2 EtherChannel between two Cisco switches using LACP.
- Verify EtherChannel operation using built-in commands.

##### 🧰 Devices Required

- 2 × Cisco 2960 Switches (SW1, SW2)
- 2 × PCs (PC1, PC2)
- 4 × Copper Straight-Through Cables

##### 🔌 Physical Connections

| Device | Interface         | Connected to | Interface         |
|--------|-------------------|--------------|-------------------|
| SW1    | FastEthernet 0/1  | SW2          | FastEthernet 0/1  |
| SW1    | FastEthernet 0/2  | SW2          | FastEthernet 0/2  |
| SW1    | FastEthernet 0/3  | PC1          | FastEthernet 0    |
| SW2    | FastEthernet 0/3  | PC2          | FastEthernet 0    |
---
