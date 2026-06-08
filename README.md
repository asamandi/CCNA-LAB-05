# Inter-VLAN Routing (Router-on-a-Stick)

### TOPOLOGY

- 1 switch (S1)
- 1 router (R1)

# Connections:

- PC VLAN10 ── S1 ── R1
- PC VLAN20
- PC VLAN30

# Configurations:

- VLAN 10
- VLAN 20
- VLAN 30
- Router subinterfaces
- IP gateways for each VLAN

# IP Addressing Plan:

VLAN 10
- R1 subinterface: 10.10.10.1/24
- PCs in VLAN10: 10.10.10.x

VLAN 20:
- R1 subinterface: 10.20.20.1/24
- PCs in VLAN20: 10.20.20.x

VLAN 30:
- R1 subinterface: 10.30.30.1/24
- PCs in VLAN30: 10.30.30.x

The router will do all the routing between VLANs.
