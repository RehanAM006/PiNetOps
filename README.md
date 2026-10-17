
# PiNetOps

## Overview

PiNetOps is a Raspberry Pi-based network operations and security project designed to provide continuous network monitoring, secure remote access, and infrastructure automation.

The project aims to transform a Raspberry Pi 4 into a lightweight, always-on network operations platform using open-source technologies.

PiNetOps is being developed as a hands-on DevOps and network engineering learning project.

## Objectives

The primary objectives of PiNetOps are:

- **Network Monitoring:** Monitor network availability, latency, uptime, and service health.
- **Secure Remote Access:** Implement encrypted remote connectivity using Tailscale.
- **Network Security:** Explore DNS filtering, network discovery, and security monitoring.
- **Observability:** Visualize network metrics and performance using Grafana and Prometheus.
- **Infrastructure Automation:** Automate configuration and deployment using Ansible.
- **Reliability:** Ensure services automatically recover after reboots and unexpected failures.

## Hardware and Operating System

### Production Server
- **Device:** Raspberry Pi 4 Model B
- **RAM:** 4GB
- **Storage:** 32GB microSD card
- **Connectivity:** Ethernet (Home LAN)
- **Operating System:** Raspberry Pi OS Lite (64-bit) — planned

### Development Environment
- **Primary Development Machine:** Omarchy Linux (Alpha)
- **Testing Machine:** Windows 11
- **Version Control:** Git and GitHub

## Technology Stack

The following technologies are planned for the project:

| Technology | Purpose |
|------------|---------|
| Tailscale | Secure VPN and remote network access |
| Prometheus | Metrics collection and monitoring |
| Grafana | Metrics visualization and dashboards |
| Docker Compose | Containerized service management |
| Ansible | Infrastructure configuration and automation |
| Python | Custom network discovery and automation |
| GitHub | Version control and project collaboration |

## Learning Outcomes

Through this project, I aim to develop practical skills in:

- Linux system administration
- Network engineering and TCP/IP
- VPN tunneling and routing
- Infrastructure as Code (IaC)
- Containerization and service orchestration
- Monitoring and observability
- Git and GitHub workflows
- DevOps practices and CI/CD
- System reliability and troubleshooting
- Technical documentation

## Project Status

**Current Phase:** Planning and development environment setup.

**Target for v0.1:** Deploy a secure, reliable remote-access gateway using Tailscale on the Raspberry Pi.

Additional network monitoring and security capabilities will be introduced in later releases.

## License

License to be determined.
