Zookeeper Role
=========

Configure and start calico node

This role has been specifically developed to be used for the deployment of calico for Mesos in the framework of INDIGO-DataCloud project.

Role Variables
--------------


Dependencies
------------

- `indigo-dc.docker`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: indigo-dc.calico }

License
-------

Apache Licence v2 [1]

[1] http://www.apache.org/licenses/LICENSE-2.0

