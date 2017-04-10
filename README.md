[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-ssl-key.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-ssl-key)
andrewrothstein.ssl-key
===========================

A role for copying a key/certificate combo to a remote machine. Useful when managing a PKI as a collection of files on the file system.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.ssl-key
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
