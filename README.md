Ansible Role for dumb-init
==========================

[![Build Status](https://travis-ci.org/alvistack/ansible-role-dumb-init.svg?branch=master)](https://travis-ci.org/alvistack/ansible-role-dumb-init)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-dumb-init.svg)](https://github.com/alvistack/ansible-role-dumb-init)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-dumb-init.svg)](https://github.com/alvistack/ansible-role-dumb-init/blob/master/LICENSE)

Ansible Role for Yelp dumb-init Installation.

Requirements
------------

This role require Ansible 2.3 or higher.

This role was designed for Ubuntu 16.04/14.04 and CentOS 7/6.

Role Variables
--------------

No additional role variables.

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: dumb-init
          dumb_init_dest: "/usr/local/bin"

License
-------

-   Code released under [Apache License 2.0](https://github.com/alvistack/ansible-role-dumb-init/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

