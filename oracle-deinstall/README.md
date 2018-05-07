Role Name
=========

This role deinstalls Oracle RDBMS homes.

Requirements
------------

Oracle Grid Infrastructure or Oracle Restart is required

Role Variables
--------------

All variables that can be configured are set in role ilmarkerm.oracle-meta

Dependencies
------------

- ilmarkerm.oracle-meta - this role defines the main Oracle database installation variables including all registered homes

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache 2.0

Author Information
------------------

Ilmar Kerm, ilmar.kerm@gmail.com
https://ilmarkerm.eu
