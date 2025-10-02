# Dummy Role

This is a dummy Ansible role to install and start httpd service.

## Variables

- `httpd_package`: Package to install (default: httpd)
- `httpd_service`: Service name (default: httpd)
- `httpd_port`: Service port (default: 80)

## Usage

```yaml
- name: Test dummy_role
  hosts: all
  roles:
    - dummy_role
