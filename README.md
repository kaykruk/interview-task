# interview-task

# Windows and Linux Server Management with Ansible

This repository contains Ansible playbooks and roles for managing Windows and Linux servers in a development, testing, and production environment.

## Project Structure

```
.
├── ansible/
│   ├── inventory/          # Server inventory definitions
│   └── roles/             # Different roles for server management
│       ├── basic_services/    # Windows services installation and management
│       ├── basic_monitoring/  # Basic monitoring setup
│       └── updates/          # Windows updates management
└── monitoring/           # Prometheus and alerting configurations

```

## Features

- Basic Windows and Linux server management
- Windows services installation (IIS and SQL Server Express)
- Basic monitoring setup with Prometheus
- Windows updates management
- Simple alerting configuration

## Prerequisites

- Ansible installed on control machine
- WinRM configured on Windows targets
- SSH access configured for Linux targets
- Prometheus and Alert Manager for monitoring
