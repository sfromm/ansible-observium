Observium
=========

Ansible role to manage [Observium](https://www.observium.org/), a network
monitoring platform.

Observium is a low-maintenance auto-discovering network monitoring
platform supporting a wide range of device types, platforms and
operating systems.

It is licensed under the *Observium Professional License*, a simplified
version of the QPL.  See: https://observium.org/docs/licenses/

Requirements
------------

There are no external dependencies.

Role Variables
--------------

For now, pleae refer to the variables documented in *defaults/main.yml*.

Dependencies
------------

There are no dependencies on other roles.

Example Playbook
----------------

A trivial example:

    - hosts: nms
      roles:
        - role: sfromm.observium
          observium_devices:
            - db1.example.com
            - db2.example.com
            - core-sw.example.com
            - core-gw.example.com
            - car-gw.example.com
       

License
-------

MIT

Author Information
------------------

See https://github.com/sfromm
