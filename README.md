slave_conf
=========

This role will configure k8s slaves for you

Requirements
------------

The requirements are you should have boto installed, dynamic inventory, ansible configuration file installed

Role Variables
--------------

There are no role variables in this role.

Dependencies
------------

To run this role you should first run this role:
master-instance
master_conf
slave-instance

Example Playbook
----------------

    - hosts: k8s_slave_an
      roles:
         - slave_conf

