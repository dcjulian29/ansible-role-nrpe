# Ansible Role: nrpe

[![CI](https://github.com/dcjulian29/ansible-role-nrpe/actions/workflows/ci.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-nrpe/actions/workflows/ci.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-nrpe.svg)](https://github.com/dcjulian29/ansible-role-nrpe/issues)

This an Ansible role to install and configure NRPE which allows Nagios plugin executions for checks

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.nrpe
  src: https://github.com/dcjulian29/ansible-role-nrpe.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

None

## Role Variables

TODO

## Example Playbook

The examples directory include one or more example playbooks.
