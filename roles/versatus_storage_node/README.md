versatus_storage_node
======================

This role configures a node to participate in the Versatus blockchain storage network.

Requirements
------------

A pre-built copy of the Versatus storage binary.

Role Variables
--------------

TBD for now. See meta/main.yml and the versatus_common role for variables.

Dependencies
------------

Depends on versatus_common within this collection.

Example Playbook
----------------

    - hosts: storage_nodes
      roles:
         - role: versatus_storage_node

License
-------

MIT

Author Information
------------------

https://versatus.io
