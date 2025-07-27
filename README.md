
# ansible-k8s-arc-runner

Ansible Playbook for Kubernetes ARC (actions-runner-controller) Runner Installation

## Overview
This project provides an Ansible playbook and roles to automate the deployment of:
- cert-manager (for certificate management)
- actions-runner-controller (ARC) for GitHub Actions self-hosted runners on Kubernetes

## Usage
Edit `main.yaml` to set your variables and run:
```bash
ansible-playbook main.yaml
```

## Roles
- `cert`: Installs cert-manager using the Jetstack Helm chart
- `arc`: Installs actions-runner-controller (ARC) using the official Helm chart

## Requirements
- Ansible
- Kubernetes cluster access
- Helm

See each role's README for more details if available.
