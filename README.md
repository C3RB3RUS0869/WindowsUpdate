windowsupdate
=========

LEARNING ANSIBLE, THIS IS A TEST ROLE! DO NOT USE IN PRODUCTION!!!

Requirements
------------
AWX/Ansible Tower
ansible 2.9


Create YML file at /var/lib/awx/projects/<projectname>/role.yml

## EXAMPLE ##
---
- name: <general description of role's function>
  hosts: all
  roles:
    - { role: <rolename> }
...

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Please do not contact me regarding this role. This is a test role and should not be utilized by the public.
