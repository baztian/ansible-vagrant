# Ansible role to install vagrant

![CI](https://github.com/baztian/ansible-vagrant/workflows/CI/badge.svg)

Role to install vagrant and associated virtualization tools in ubuntu.

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: baztian.vagrant

License
-------

GPLv3
