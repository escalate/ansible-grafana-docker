# Ansible Role: Raspberry - Grafana (Docker)

[![CI](https://github.com/escalate/ansible-raspberry-grafana-docker/actions/workflows/ci.yml/badge.svg?event=push)](https://github.com/escalate/ansible-raspberry-grafana-docker/actions/workflows/ci.yml)

An Ansible role that manages [Grafana](https://grafana.com/oss/grafana/) Docker container on Raspberry Pi OS.

## Install

```
$ ansible-galaxy install escalate.grafana
```

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-raspberry-grafana-docker/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

* Roles: [requirements.yml](https://github.com/escalate/ansible-raspberry-grafana-docker/blob/master/requirements.yml)
* Collections: [collections.yml](https://github.com/escalate/ansible-raspberry-grafana-docker/blob/master/collections.yml)

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.grafana
      tags: grafana
```

## License

MIT
