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

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>dumb_init_url</td>
<td>yes</td>
<td><code>https://github.com/Yelp/dumb-init/releases/download/v1.2.0/dumb-init_1.2.0_amd64</code></td>
<td></td>
<td>URL for download dumb-init binary</td>
</tr>
<tr class="even">
<td>dumb_init_dest</td>
<td>yes</td>
<td><code>/usr/binn/dumb-init</code></td>
<td></td>
<td>Absolute path of where to download the file to</td>
</tr>
<tr class="odd">
<td>dumb_init_group</td>
<td>yes</td>
<td><code>root</code></td>
<td></td>
<td>Name of the group that should own the file</td>
</tr>
<tr class="even">
<td>dumb_init_mode</td>
<td>yes</td>
<td><code>0755</code></td>
<td></td>
<td>Mode the file should be</td>
</tr>
<tr class="odd">
<td>dumb_init_owner</td>
<td>yes</td>
<td><code>root</code></td>
<td></td>
<td>Name of the user that should own the file</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: dumb-init
          dumb_init_dest: "/usr/local/bin/dumb-init"

License
-------

-   Code released under [Apache License 2.0](https://github.com/alvistack/ansible-role-dumb-init/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

