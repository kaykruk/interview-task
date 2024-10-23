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