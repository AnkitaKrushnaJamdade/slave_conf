slave_conf
=========

This role will configure 2 k8s slaves or worker nodes for you which will have tag as key = Name and value = k8s_slave_an in aws instance

Requirements
------------

The requirements are you should have boto installed, dynamic inventory, ansible configuration file installed

Role Variables
--------------

There are no role variables in this role.

Dependencies
------------

To run this role you should first run this role:
master_instance
master_conf
slave_instance

Example Playbook
----------------

    - hosts: k8s_slave_an
      roles:
         - slave_conf

