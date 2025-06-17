# IP

## Q&A

    1. Describe the packet header of IPv4 packets.
    1. Explain the flow of the ARP protocol.
    2. What is ARP Spoofing?
    3. Explain what is a gratuitous ARP and how it prevents flooding. Familiarize yourself with the term "silent host".
    4. In IPv6, what is a link-local address? Why does every IPv6-enabled device have one, and how is it different from a global unicast address?
    5. Compare ARP operation in IPv4 networks versus how address resolution is handled in IPv6 networks.
    6. What is the purpose of the loopback IP address (127.0.0.1)? How is it useful during troubleshooting?
    7. What is the meaning of a static route with 0.0.0.0/0 as the destination network? Why is this sometimes called a "default route"?
    8. Can you configure multiple default gateways on a single device? If so, how does the device decide which one to use?
    9. Imagine a router has multiple static routes to the same destination network with different next-hop IP addresses. How does the router decide which route to use?
    10. Using Packet Tracer,
        You are tasked to build a basic network connecting two remote offices through routers.
        You must configure default gateways for all PCs and set up static routes between routers to ensure full communication across the network.

        2 Routers: R1 and R2
        2 Switches: SW1 and SW2

        4 PCs:

        - PC0 and PC1 connected to SW1
        - PC2 and PC3 connected to SW2

        IP Addressing Plan:

        | Device |  Interface  |  IP Address  | Subnet Mask
        |  ----  | ----------- | ------------ | ---------
        |  R1    | G0/0        | 192.168.1.1  | 255.255.255.0
        |  R1    | Serial0/0/0 | 10.0.0.1     | 255.255.255.252
        |  R2    | Serial0/0/0 | 10.0.0.2     | 255.255.255.252
        |  R2    | G0/0        | 192.168.2.1  | 255.255.255.0
        |  PC0   | —           | 192.168.1.10 | 255.255.255.0
        |  PC1   | —           | 192.168.1.11 | 255.255.255.0
        |  PC2   | —           | 192.168.2.10 | 255.255.255.0
        |  PC3   | —           | 192.168.2.11 | 255.255.255.0

        Configuration Requirements:
            Cable the network properly

        Assign IP addresses:
            PCs: Static IPs according to the table above.
            Routers: Configure G0/0 and Serial0/0/0 interfaces with IPs.

        Set Default Gateways on PCs:
            PC0 and PC1 ➔ Default Gateway: 192.168.1.1
            PC2 and PC3 ➔ Default Gateway: 192.168.2.1

        Configure Static Routes on Routers:
            On R1, add a static route to the 192.168.2.0/24 network via 10.0.0.2.
            On R2, add a static route to the 192.168.1.0/24 network via 10.0.0.1.

        Verify Connectivity:
            1. Ping from PC0 to PC2 and PC3.
            2. Ping from PC1 to PC2 and PC3.
            3. PCs in the same site should also ping each other.
