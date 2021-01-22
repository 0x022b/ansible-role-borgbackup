# Ansible Role: borgbackup

![Ansible Galaxy](https://github.com/0x022b/ansible-role-borgbackup/workflows/Ansible%20Galaxy/badge.svg)

Ansible role that configures borgbackup package.

## Requirements

None.

## Role Variables

Available variables are listed below with default values.

```yaml
borgbackup_package_state: present
```

Variable to control the state of borgbackup package.

## Dependencies

- 0x022b.epel

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: 0x022b.borgbackup
```

## Versioning

This project uses [Semantic Versioning][semver].

## License

MIT

[semver]: https://semver.org/
