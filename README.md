# AnsibleRoleCassandraAddRepo
=========

This Ansible role will add repository for the latest Cassandra version.

Requirements
------------

None.

Role Variables
--------------

There is one variable present in this role, "cassandra_version". This variable was added to easly follow Cassandra releases, and also to allow add repository for older version of the Cassandra. By default variable is set to "311x" which will add Cassandra repo in latest availeble version.

Dependencies
------------

None.

Example Playbook
----------------

Below there's example playbook which can be used:

    - hosts: servers
      roles:
         - { role: kamikazestar.AnsibleRoleCassandraAddRepo }

License
-------

BSD

Author Information
------------------

[Marcin Slabonski](https://github.com/kamikazestar)
