{{cookiecutter.role_name}}
=========

{{cookiecutter.description}}

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: {{cookiecutter.role_name}}, my_var: 42 }

Author Information
------------------

Me! @github