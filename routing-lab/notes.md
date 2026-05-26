# Static Routing Lab

## Objective
To configure static routes between two routers.

## Network Design
- R1 connected to Network 192.168.1.0/24
- R2 connected to Network 192.168.2.0/24
- Router-to-router link: 10.0.0.0/30

## Key Concepts

### Static Route
A manually configured route used to reach a specific network.

### Example:
ip route 192.168.2.0 255.255.255.0 10.0.0.2

## Verification
- Use `ping` to test connectivity between networks
- Use `show ip route` to verify routing table

## Result
Devices from both networks can communicate via routers.
