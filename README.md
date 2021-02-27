# jtprogru.admins_access


![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-admins-access/CI?label=CI) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-admins-access/Release?label=Release) ![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-admins-access)

Simple role for configuration access for admins

## Role Variables

See [`defaults/main.yml`](defaults/main.yml).

## Example Playbook

Example playbook:
```yaml
---
- name: Configuration admins access
  hosts: all
  become: true

  roles:
    - jtprogru.admins_access
```

## License

See [LICENSE](LICENSE.md)
