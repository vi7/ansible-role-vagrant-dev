Ansible role: Vagrant dev environment
=====================================

The role configures local dev environment based on a Vagrant machine

Requirements
------------

The role should be invoked from the Vagrantfile. Other ways of the role usage are possible but have not been tested.

Role Variables
--------------

**TBD**

Dependencies
------------

The role doesn't have any deps

Example Playbook
----------------

    - hosts: all
      become: true
      roles:
        - ansible-role-vagrant-dev

License
-------

BSD

Author Information
------------------

Vitaliy Dmitriev <vi7alya@gmail.com>
