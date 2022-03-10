ansible-role-anaconda
=====================

![](https://github.com/kevincoakley/ansible-role-anaconda/workflows/Molecule%20Test/badge.svg)

Install Anaconda Python for all users - https://www.anaconda.com . Tested with Anaconda 2021.11 on CentOS 7, CentOS 8, 
Ubuntu 18.04 and Ubuntu 20.04.

Requirements
------------

None

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - name: Test the Anaconda role for CentOS and Ubuntu
      hosts: anaconda
      become: yes
      become_method: sudo
    
      roles:
        - ansible-role-anaconda
    
      tags:
        - anaconda
    
License
-------

BSD

Author Information
------------------

Kevin Coakley (https://github.com/kevincoakley)
