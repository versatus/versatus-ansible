versatus_common
===============

Common Ansible orchestration tasks for all Versatus nodes. Not intended to be included directly. It's pulled in as a dependency by other roles.

Requirements
------------

None at this stage.

Role Variables
--------------

* service_name -- the name of the systemd service (eg, versatus-protocol)
* service_user -- the name of the user to create and run the service as (eg, versatus-protocol)
* service_executable -- the path to the local file that is the executable to become the remote service.

Others exist in defaults/main.yml

Dependencies
------------

None.

Example Playbook
----------------

Don't include this role directly. Instead use one of the versatus service roles.

License
-------

MIT

Author Information
------------------

https://versatus.io
