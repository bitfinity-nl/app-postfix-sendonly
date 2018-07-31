Role Name
=========

Postfix sendonly configuration.

Requirements
------------

- Ubuntu 18.04

Role Variables
--------------

- postfix_relay_host
- postfix_relay_port

Dependencies
------------


Example Playbook
----------------

    - hosts: servers

      vars:
        postfix_relay_host : '192.168.0.184'
        postfix_relay_port : '25'

      roles:
         - app-postfix-sendonly

License
-------

GPLv3

Author Information
------------------

E: lrutten@bitfinity.nl

I: https://www.bitfinity.nl
