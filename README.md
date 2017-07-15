erlang
======

[![Build Status](https://travis-ci.org/markosamuli/ansible-erlang.svg?branch=master)](https://travis-ci.org/markosamuli/ansible-erlang)

Installs Erlang.

This is a fork from [kbrebanov.erlang](https://github.com/kbrebanov/ansible-erlang) role.

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name           | Default | Description                  |
|:---------------|:--------|:-----------------------------|
| erlang_version | 20.0    | Version of Erlang to install |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - markosamuli.erlang
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
