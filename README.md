Role Name
=========

Ansible role for installing and configuring Let's Encrypt client in Fedora and CentOS.

Requirements
------------

Ansible version >= 2.0.0.

Role Variables
--------------

None

Dependencies
------------

- shellbro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
         - shellbro.certbot

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
