ansible-role-pritunl-client
=========
[![Build Status](https://travis-ci.org/jugatsu/ansible-role-pritunl-client.svg?branch=master)](https://travis-ci.org/jugatsu/ansible-role-pritunl-client)

An Ansible Role that installs Pritunl Client (https://client.pritunl.com/).

Requirements
------------

This role only supports Ubuntu 12.x, 14.x, 16.x.

Example Playbook
----------------
```yaml
- hosts: servers
  roles:
    - { role: ansible-role-pritunl-client }
```

License
-------

BSD
