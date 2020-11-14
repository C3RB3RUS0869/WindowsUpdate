windowsupdate
=========

LEARNING ANSIBLE, THIS IS A TEST ROLE! DO NOT USE IN PRODUCTION!!!

Requirements
------------
AWX/Ansible Tower
ansible 2.9
Create role.yml file at /var/lib/awx/projects/<project>/<rolename>.yml


Dependencies
------------
python-pip
python36
krb5-libs
krb5-workstation
krb5-devel
openldap-clients
openldap-devel
epel-release
ansible

Example Playbook
----------------
---
- name: general description of role's function
  hosts: all
  roles:
    - { role: rolename }


License
-------

BSD

Author Information
------------------

Please do not contact me regarding this role. This is a test role and should not be utilized by the public.
