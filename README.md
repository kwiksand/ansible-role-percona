ansible-role-percona
=========

This role will:
- install Percona's YUM Repository (can be disabled)
- install Percona Server (select which version required)
- configure my.cnf
- manage SElinux and Server runtime

Requirements
------------

EPEL should probably be enabled (CentOS)


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: mysql_serfers
      roles:
         - { role: ansible-role-percona, x: 42 }

License
-------

BSD

Author Information
------------------

Shannon Carver (shannon.carver@gmail.com)
