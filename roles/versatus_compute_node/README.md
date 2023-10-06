versatus_compute_node
======================

This role configures a node to provide compute to the Versatus network.

Requirements
------------

A pre-built copy of the Versatus compute binary.

Role Variables
--------------

TBD for now. See meta/main.yml and the versatus_common role for variables.

Dependencies
------------

Depends on versatus_common within this collection.

Example Playbook
----------------

    - hosts: compute_nodes
      roles:
         - role: versatus_compute_node

License
-------

MIT

Author Information
------------------

https://versatus.io
