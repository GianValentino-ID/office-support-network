# office-support-network
Documentation of building a support office network infrastructure, Linux server deployment, and centralized network services.

## Overview
This project documents the planning, configuration, and implementation of a local IT infrastructure operating alongside an existing corporate network.
The goal is to build a centralized network services, file distribution, monitoring, and dedicated wireless connectivity.

## Project Objectives

- Establish an independent local network.
- Deploy centralized DNS filtering.
- Implement centralized file storage and software distribution.
- Provide consistent wireless connectivity across the building.
- Implement network segmentation and access control.
- Monitor server health and network devices.

## Existing Devices

# Local PC/Server
| Component | Specification |
|---|---|
| CPU | Intel Core i7-7700 |
| RAM | 8 GB |
| Storage | 1 TB HDD |
| Operating System | Ubuntu Server |
| Containerization | Docker |

# ONT
| Component | Specification |
|---|---|
| ISP | Indibiz |
| ONT | ZTE F6600P |
| Bandwidth | 300 Mbps 'unverified' |

## Current Services

# Local PC/Server
| Service | Purpose |
|---|---|
| AdGuard Home | DNS filtering |
| Netdata | Server monitoring |
| Uptime Kuma | Service availability |
| NetAlertX | Network device discovery |

## Documentation
Detailed technical documentation is maintained in the `docs/` directory.

## Project Status
**Status:** Initial server deployment and infrastructure planning.
Network separation, wireless deployment, and centralized storage are planned.

## Technical Areas
- Network Engineering
- Linux Systems Administration
- IT Infrastructure
- DNS Management
- Network Monitoring
- Network Security
