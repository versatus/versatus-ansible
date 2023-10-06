versatus_protocol_node
======================

This role configures a node to participate in the Versatus blockchain protocol network.

Requirements
------------

A pre-built copy of the Versatus protocol binary.

Role Variables
--------------

TBD for now. See meta/main.yml and the versatus_common role for variables.

Dependencies
------------

Depends on versatus_common within this collection.

Example Playbook
----------------

    - hosts: protocol_nodes
      roles:
         - role: versatus_protocol_node

License
-------

MIT

Author Information
------------------

https://versatus.io
