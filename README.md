# Ansible Role: motd

An Ansible Role to rewrite the `/etc/motd` and `/etc/issue` files.

[![Actions Status](https://github.com/tristan-weil/ansible-role-motd/workflows/molecule/badge.svg?branch=master)](https://github.com/tristan-weil/ansible-role-motd/actions)

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

Mandatory variables:

| Variable      | Description |
| :------------ | :---------- |

Optional variables:

| Variable      | Default | Description |
| :------------ | :------ | :---------- |
| motd_message  |         | a message to display |
| motd_issue    |         | an issue to display  |

## Example Playbook

    - hosts: 'webservers'
      roles:
        - role: 'ansible-role-motd'
    
## Todo

None.

## Dependencies

None.

## Supported platforms

See [meta/main.yml](https://github.com/tristan-weil/ansible-role-motd/blob/master/meta/main.yml)

## License

See [LICENSE.md](LICENSE.md)
