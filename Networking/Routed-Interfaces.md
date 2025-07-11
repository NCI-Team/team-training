# Routed Interface – Trainee Guide

### Goals

- Understand what is Routed Interfaces.
- Understand what is the Usecase of Routed Interfaces.

### Tasks

- What is Routed Interfaces?
- How does a routed interface differ from a switched interface?
- When would you use a routed interface instead of a VLAN interface (SVI)?
- How can you convert a switched port to a routed port on a Cisco Catalyst switch?
- Can you create subinterfaces on a routed interface? If so, in what scenarios is this useful?
- What is the difference between a routed interface and a loopback interface?

----

### 🧪 Packet Tracer Lab: Routed Interfaces

#### ✅ Objective:
- Configure routed interfaces on routers (or Layer 3 switches).
- Enable IP routing.
- Test connectivity between two networks using routed interfaces.

#### 🖥️ Topology:

[ PC1 ] --- [ R1 ] --- [ R2 ] --- [ PC2 ]

- PC1 connected to R1 via GigabitEthernet0/0  
- R1 connected to R2 via GigabitEthernet0/1 ↔ GigabitEthernet0/1  
- R2 connected to PC2 via GigabitEthernet0/0  

#### 🔧 Device List:
- 2 x Routers (R1, R2)  
- 2 x PCs (PC1, PC2)  
- 3 x Copper Straight-Through Cables  
