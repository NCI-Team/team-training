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


#### Lab
# Packet Tracer Lab: Practicing Port Channel (PC) and Simulated VPC Concepts

## Objective

- Configure and verify a Port Channel (EtherChannel) between two Cisco switches.
- Simulate a VPC-like setup by connecting a host to two switches with EtherChannels for redundancy.

---

## Lab Topology

```
      +-----------+         +-----------+
      |  Switch1  |---------|  Switch2  |
      +-----------+         +-----------+
          |                     |
          |                     |
        (PC1)                (PC2)
          |                     |
      +-----------------------------+
      |          Host1              |
      +-----------------------------+
```

**Legend:**  
- Switch1 & Switch2: Cisco 2960 or 3560 switches  
- Host1: PC with two NICs (use two FastEthernet links)  
- PC1: Port Channel between Switch1 and Host1  
- PC2: Port Channel between Switch2 and Host1

---

