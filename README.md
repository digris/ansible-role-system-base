Digris Base System Role
=======================

A minimal Ansible role that configures our servers...


Requirements
------------

 - Debian 8.x

Role Variables
--------------

- `system_base_rsyslog_server`: rsyslog server to use, defasults to `no`



Example Playbook
----------------

Minimal usage example:

    - hosts: all
      roles:
        - {
            role: digris.system-base,
            system_base_rsyslog_server: "my.local.syslog-server.example.com",
          }


License
-------

BSD
