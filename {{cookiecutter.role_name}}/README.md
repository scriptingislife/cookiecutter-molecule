{{cookiecutter.role_name}}
=========

{{cookiecutter.description}}

Requirements
------------

None.

Role Variables
--------------

```
my_var
  42 - Creates 42 gold coins.
```

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

{{ cookiecutter.author }} @{{ cookiecutter.github_username }}