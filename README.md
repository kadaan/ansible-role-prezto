# Ansible Role: Prezto

[![Build Status](https://travis-ci.com/kadaan/ansible-role-prezto.svg?branch=master)](https://travis-ci.com/kadaan/ansible-role-prezto)

Installs prezto and the powerlevel9k theme.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - [kadaan.zsh](https://galaxy.ansible.com/kadaan/zsh/)

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.prezto, prezto_execute: true }

## License

Apache 2.0
