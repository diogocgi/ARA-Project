# ARA-Project
Advanced Network Architecture Project in GNS3

## Table of Contents
- [Objective](#objective)
- [What's included](#whats-included)
- [IPv4 network topology](#ipv4-network-topology)
- [Documentation](#documentation)
- [Improvements](#improvements)
- [Tools](#tools)
- [Testing](#testing)
- [Creators](#creators)

## Objective

The objective of this project is the implementation of an ISP-level network, where we have control over the configurations of the ISP-PT2 Autonomous System. This network is connected to 2 external ASs (ISP-PT1 and IPS-ES) and 1 private AS (Corporate C).

## What's included
```
ARA_project_IPv4/
    +-- Configuration scripts/
        +-- cdn/
        +-- InternetCore/
        +-- ISP-ES/
        +-- ISP-PT1/
        +-- ISP-PT2/
            +-- Aveiro/
                +-- netA1/
                +-- netB1/
            +-- Oeiras/
                +-- netC/
                +-- netD/
                    +-- netA2/
                    +-- netB2/
    +-- project-files/
    +-- ARA_project_IPv4.gns3 (main file)
```

## IPv4 network topology

![ipv4_network_topology_image]

[ipv4_network_topology_image]: https://github.com/Diogo525/ARA-Project/blob/master/images/IPv4_network.png

## Documentation

The documentation of this project can be found in the [wiki](https://github.com/Diogo525/ARA-Project/wiki).

## Improvements

The project lacks the following features (which will be implemented in future updates):
- [ ] MPLS VPN for Corporate A
- [ ] CDN rotating decision
- [ ] VoIP with SIP
- [ ] IPv6 implementation (without MPLS)

## Tools

The software **GNS3 v2.1.11** was used for the network simulation.

- Router firmware image: **Router 7200 Firmware 15.1(4) Image**

## Testing

To upload the project in a working state, all VMs used were removed (being replaced by blank squares). In order to test functionalities like the CDN, DNS and SIP, the blank squares must be replaced by VMs and configured according to the [wiki](https://github.com/Diogo525/ARA-Project/wiki/IPv4-Network-Configuration#CDN-configuration).

## Creators

**Diogo Guedes**

- <https://github.com/Diogo525>
