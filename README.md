![Ansible Lint](https://github.com/johanneskastl/ansible-role-lego_acme-client/workflows/Ansible%20Lint/badge.svg)

lego_acme-client
=========

Install and configure the lego ACME client (using binary download on Debian to get something fairly recent...)

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.lego_acme-client' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
