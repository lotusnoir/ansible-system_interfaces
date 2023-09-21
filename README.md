# ansible-system_interfaces

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_interfaces-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_interfaces)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_interfaces.svg)](https://github.com/lotusnoir/ansible-system_interfaces/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_interfaces?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_interfaces)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/system_interfaces)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/system_interfaces)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Configure network interfaces (forked from https://github.com/michaelrigart/ansible-role-interfaces)
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_interfaces
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_interfaces


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
