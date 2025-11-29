# Mini-Corporate Network in Docker

## Project Overview

A fully simulated network using Docker containers, each acting as a device:

- A router (using Ubuntu + ip route)

- A DNS server (Bind9 or dnsmasq)

- A VPN server (WireGuard)

- Two internal “client” machines

- A monitoring machine for performance tests

### Repository Structure
```mini-network-lab/
│
├── docker-compose.yml
├── router/
│   └── config.sh
├── dns/
│   └── named.conf.local
├── vpn/
│   └── wg0.conf
├── clients/
│   └── clientA/
│   └── clientB/
└── docs/
    ├── architecture_diagram.png
    ├── routing.md
    ├── dns.md
    ├── vpn.md
    └── performance_tests.md
```

## What is routing?


## What is DNS?


## What is a VPN?


## Performance results
