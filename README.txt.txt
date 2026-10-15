Project: Inter-Office Routing - 2 Sites, 8 Hosts
Tool: Cisco Packet Tracer 9.0.1

What I built:
- 1 Router (2901) as gateway
- Left office 192.168.1.0/24 (G0/0 = 192.168.1.1)
- Right office 192.168.2.0/24 (G0/1 = 192.168.2.1)

Proof of working:
- ping 192.168.1.1 = 0% loss
- ping 192.168.2.10 from left PC = Reply, TTL=127

Skill: IP Planning, Static Routing, Troubleshooting swapped cables