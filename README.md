Role Name
=========

Create Oracle Database Restore Point.

Requirements
------------

Ensure that `/etc/profile.d/oracle.sh` is present and is setting all variables correctly and sqlplus command is present in $PATH

Role Variables
--------------

- restore_point_name: Name of target restore point


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: embedit-ansible.oracle-tools-create_restore_point, restore_point_name: some_restore_point }

License
-------

MIT

Author Information
------------------

- Mario Vejlupek
