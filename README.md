# Packet Tracer Networking Labs

Network topologies I designed and configured in **Cisco Packet Tracer 9.0** while studying ICT at the University of Prishtina (FIEK) and preparing for the **Cisco CCNA (200-301)**.

Each lab folder contains:

- the `.pkt` file (open with Packet Tracer 9.0 or newer)
- `configs/`: the `running-config` of every router, exported as plain text
- `README.md`: topology diagram, addressing table, design notes and verification commands

## Labs

| Lab | Topics | Devices |
|---|---|---|
| [Site-to-Site IPsec VPN](./vpn-site-to-site) | IKEv1 / ISAKMP, IPsec, crypto maps, ACLs, static routing | 3 routers, 2 switches, 4 PCs |
| [Multi-site OSPF enterprise network](./ospf-enterprise-network) | OSPF (single area), redundant core ring, router-on-a-stick, 802.1Q, centralized DHCP (`ip helper-address`) | 10 routers, 10+ switches, ~30 PCs, 1 server |

## Author

**Urim Dragusha**: ICT student (FIEK, University of Prishtina), focused on computer networking.
