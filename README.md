[![Build Status](https://travis-ci.org/opspluslove/ansible-docker.svg?branch=master)](https://travis-ci.org/opspluslove/ansible-docker)

docker
======

Ansible role to install docker-engine

Requirements
------------

- Python 2.6+

Role Variables
--------------

```
# Defaults
docker_dockerpy_version: 1.9.0
dockercompose_version: 1.9.0-rc1
dockercompose_platform: Linux-x86_64
dockercompose_url: https://github.com/docker/compose/releases/download/{{ dockercompose_version }}/docker-compose-{{ dockercompose_platform }}
dockercompose_install_dir: /usr/local/bin/docker-compose
```

Example Playbook
----------------

_TODO_
