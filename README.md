ansible-role-anaconda
=====================

[![Build Status](https://travis-ci.org/kevincoakley/ansible-role-anaconda.svg?branch=master)](https://travis-ci.org/kevincoakley/ansible-role-anaconda)

Install Anaconda Python for all users - https://www.anaconda.com . Tested with Anaconda 5.2.0 on CentOS 7 and Ubuntu 18.04.

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
