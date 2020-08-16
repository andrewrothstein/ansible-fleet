andrewrothstein.fleet
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-fleet.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-fleet)

Installs Ranchers [fleet](https://github.com/rancher/fleet).

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
    - andrewrothstein.fleet
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
