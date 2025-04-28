# Subnetting

## Q&A

    1. Explain what is subnetting, and why is it needed.
    2. 
    1. What happens when two subnets overlap? Provide an example of overlapping subnets and describe the problems it could cause for routing and security.
    2. Compare and contrast Classful addressing (A, B, C) with Classless Inter-Domain Routing (CIDR). Why did CIDR replace classful addressing?
    3. Why is Variable Length Subnet Masking (VLSM) more efficient than traditional fixed-length subnetting? Give an example to support your explanation.
    4. Describe the difference between FLSM (Fixed Length Subnet Masking) and VLSM (Variable Length Subnet Masking). When would you choose one over the other in a network design?
    
    5. Using Packet Tracer:
    You are a network engineer at a new company! The company has 3 departments: Core, BD, Platforms.
    Each department has 2 PCs.
    You are given a 192.168.10.0/24 network.
    Subnet the 192.168.10.0/24 network into at least 3 subnets, one for each department.
        Assign IP addresses to all PCs, ensuring:
            1. First usable IP is assigned to the first PC in each department.
            2. Use three switches (one per department) and one router.
            3. Configure router interfaces with the correct subnet IPs (Router-on-a-Stick if you want extra difficulty!).

    Test connectivity:
        PCs in the same department must ping each other.
        PCs across departments must NOT ping each other.
