Role Name
=========

Ansible role for installing and configuring Let's Encrypt client in Fedora and CentOS.

Requirements
------------

Ansible version >= 2.0.0.

Role Variables
--------------

They are two variables specifying time when daily renewal of certificates happens. Defaults:

    renewal_minute: 41
    renewal_hour: 3

Dependencies
------------

- shellbro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: shellbro.certbot
           renewal_minute: 13
           renewal_hour: 1

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
