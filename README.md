# NATS Ansible Role

NATS.io is a simple, secure and high performance open source messaging system for cloud native applications, IoT messaging, and microservices architectures.

## Installation

``` yaml
# requirments.yaml
- src: git@github.com:4lie/ansible-role-nats.git
  scm: git
  version: master
  name: nats
```

## Role Variables

``` yaml
nats_version: "2.1.6"
nats_custom_conf: []
```

## Example Playbook

``` yaml
- hosts: servers
  roles:
    - nats
```
