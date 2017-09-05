Role Name
=========

Builds Ignite 2.1.0 from source

Role Variables
--------------

- `IGNITE_HOME` pointing to location of Ignite installation folder

    It is set to /opt/ignite

Example Playbook
----------------

How to use your role:

    - hosts: ignites
      roles:
         - { role: dropoutlabs.ignite }

License
-------

BSD
