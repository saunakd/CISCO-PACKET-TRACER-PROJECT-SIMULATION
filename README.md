# CISCO-PACKET-TRACER-PROJECT-SIMULATION

![Topology Preview](https://github.com/saunakd/CISCO-PACKET-TRACER-PROJECT-SIMULATION/blob/main/Screenshot%202025-05-29%20151916.png)

A hands-on networking lab built with **Cisco Packet Tracer**, demonstrating core enterprise networking concepts.

## Project Overview

This repository contains a Cisco Packet Tracer simulation (`topo.pkt`) of a small-to-medium scale enterprise network. It showcases:

* Network topology design across multiple departments
* Router and switch configurations
* VLAN segmentation and inter-VLAN routing
* Static and dynamic routing protocols (RIP, OSPF)
* DHCP service implementation
* Basic network security using Access Control Lists (ACLs)

## Repository Structure

```
cisco-packet-tracer-network-simulation/
├── README.md                  # Project documentation
├── topo.pkt                   # Packet Tracer simulation file
├── configs/                   # Exported device configuration snapshots
│   ├── router1-config.txt
│   └── switch1-config.txt
└── screenshots/               # Visual previews of the simulation
    └── topology-overview.png
```

## Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/saunakd/cisco-packet-tracer-network-simulation.git
   cd cisco-packet-tracer-network-simulation
   ```
2. **Open `topo.pkt`** in **Cisco Packet Tracer** (version 7.x or later).
3. **Explore** the topology, view device CLI, and test connectivity using `ping` and `traceroute`.

## Configuration Snapshots

Plain-text exports of device configs are provided for quick review without opening Packet Tracer:

* `configs/router1-config.txt`
* `configs/switch1-config.txt`

## Skills Demonstrated

* Computer Networking & Simulation
* IP Addressing & Subnetting
* VLANs & Inter-VLAN Routing
* Static & Dynamic Routing (RIP, OSPF)
* DHCP & ACL Configuration
* Network Troubleshooting

## License

Licensed under the MIT License. See [LICENSE](LICENSE.md) for details.
