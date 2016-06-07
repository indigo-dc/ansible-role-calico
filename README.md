Calico Role
=========

Configure and start calico node according to 

https://github.com/projectcalico/calico-containers/blob/master/docs/mesos/UsageGuideDockerContainerizer.md

This role has been specifically developed to be used for the deployment of calico for Mesos in the framework of INDIGO-DataCloud project.

Role Variables
--------------
- `etcd_peers` (optional): list of etcd nodes - alternatively, you can use a proper inventory file specifying the hosts group [etcd_servers]

Dependencies
------------

- `indigo-dc.docker`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: indigo-dc.calico, etcd_peers: ["10.10.10.1", "10.10.10.2", "10.10.10.3"] }

License
-------

Apache Licence v2 [1]

[1] http://www.apache.org/licenses/LICENSE-2.0

