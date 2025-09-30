# ACI

## Overview

This part of the training introduces Cisco ACI concepts and hands-on configuration. It gradually builds knowledge of the ACI object model (fabric, tenants, VRFs, bridge domains, and EPGs), policy enforcement with contracts, external connectivity, advanced services like service graphs and load balancing, and monitoring. The section concludes with a final integration lab where trainees configure servers end-to-end from scratch.

## Training Structure

| File Name          | Subjects Covered |
| ------------------ | ---------------- |
| `Fabric`           | VLAN Pools, Domains, Interface Profiles, Switch Profiles: What each component does, how they interrelate, and how they enable attaching endpoints to the fabric. |
| `VRFs_and_Tenants` | Tenant purpose, VRF relationship to tenants, default tenants, VRF route leaking methods with use cases and limitations, and high-level configuration. |
| `EPG`              | Concept and purpose, differences from VLANs, inter-EPG communication, relation to BDs and Application Profiles, subnet assignment, uSeg EPGs and ESGs, and use cases for micro-segmentation. |
| `BridgeDomain`     | Primary functions, hardware proxy vs flood, silent hosts, ARP flooding and GARP, control-plane vs data-plane learning, L2/L3 communication settings, unicast routing, and interaction with EPGs. |
| `Contracts`        | Purpose and components (Filters, Subjects), cross-VRF and L3Out considerations, vzAny relationship, policy enforcement, implicit rules, and ingress vs egress behavior. |
| `AAEP`             | Purpose, association with domains, interface policy management, differences from Interface Policy Groups, encapsulation, and EPG mode assignment. |
| `L3Out`            | Purpose and key functions, GUI components, external route distribution, advertising BD subnets, transit routing, route control and enforcement, interface types, Route Profiles, and default route-maps. |
| `ServiceGraph`     | What they are, how they insert L4–L7 devices like firewalls/load balancers. |
| `BFD`              | Overview, operation with BGP, advantages over adjusting BGP timers, use in Cisco ACI, and production benefits. |
| `Monitoring`       | IP SLA, SPAN, and COOP in ACI, their roles, use cases, and impact on network operations. |
| `NLB`              | ECMP vs PBR load balancing, configuration requirements, health monitoring, and handling node failures. |
| `FinalFight`       | Configuring servers from scratch in ACI, creating all required objects, and verifying connectivity. |
