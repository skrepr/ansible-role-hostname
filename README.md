<a href="https://skrepr.com/">
  <p align="center">
    <img width="200" height="100" src="https://skrepr.com/theme/skrepr/img/skrepr.svg?a3d5f79941" alt="skrepr" />
  </p>
</a>
<h1 align="center">Ansible Role Hostname</h1>
<div align="center">
  <a href="https://github.com/skrepr/ansible-role-hostname/releases"><img src="https://img.shields.io/github/release/skrepr/ansible-role-hostname.svg" alt="Releases"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/blob/main/LICENSE"><img src="https://img.shields.io/github/license/skrepr/ansible-role-hostname" alt="LICENSE"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/actions/workflows/ci.yml"><img src="https://github.com/skrepr/ansible-role-hostname/actions/workflows/ci.yml/badge.svg" alt="CI"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/issues"><img src="https://img.shields.io/github/issues/skrepr/ansible-role-hostname.svg" alt="Issues"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/pulls"><img src="https://img.shields.io/github/issues-pr/skrepr/ansible-role-hostname.svg" alt="PR"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/commits"><img src="https://img.shields.io/github/commit-activity/m/skrepr/ansible-role-hostname" alt="Commits"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/stars"><img src="https://img.shields.io/github/stars/skrepr/ansible-role-hostname.svg" alt="Stars"/></a><a> </a>
  <a href="https://github.com/skrepr/ansible-role-hostname/releases"><img src="https://img.shields.io/github/forks/skrepr/ansible-role-hostname.svg" alt="Forks"/></a><a> </a>
</div>

# About

This Ansible role is used for changing the hostname on your server. 

It works by taking your `{{ inventory_hostname }}` and using it for changing the hostname.

[![Ansible Role](https://img.shields.io/ansible/role/56457)](https://galaxy.ansible.com/skrepr/hostname)
[![Ansible Role](https://img.shields.io/ansible/role/d/56457)](https://galaxy.ansible.com/skrepr/hostname)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56457)](https://galaxy.ansible.com/skrepr/hostname)

## Requirements

- SSH access to the server

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
#!/usr/bin/env ansible-playbook


- hosts: production
  become: true

  roles:
   - skrepr.hostname
```

## License

MIT / BSD

## Author Information

This role was created in 2021 by [Jeroen van der Meulen](https://github.com/jeroenvandermeulen), commisioned by [Skrepr](https://skrepr.com)
