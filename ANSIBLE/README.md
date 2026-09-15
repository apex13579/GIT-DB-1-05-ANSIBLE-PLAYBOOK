# Ansible Infrastructure

This repository contains the Ansible configuration used to build and manage the homelab infrastructure.

## Structure

- `ansible.cfg` — Ansible configuration
- `inventory/` — Managed hosts and groups
- `group_vars/` — Variables shared by host groups
- `playbooks/` — Main Ansible playbooks
- `roles/` — Reusable Ansible roles
- `requirements.yml` — Ansible collection dependencies

## Usage

Run the main playbook from the `ansible/` directory:

```bash
ansible-playbook playbooks/site.yml
