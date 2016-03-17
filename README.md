Ansible Role for User
====================

[![Build Status](https://travis-ci.org/vitalied/ansible-role-user.svg?branch=master)](https://travis-ci.org/vitalied/ansible-role-user)
[![GitHub tag](https://img.shields.io/github/tag/vitalied/ansible-role-user.svg)](https://github.com/vitalied/ansible-role-user)
[![GitHub license](https://img.shields.io/github/license/vitalied/ansible-role-user.svg)](https://github.com/vitalied/ansible-role-user/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/ansible/role/8749.svg)](https://galaxy.ansible.com/vitalied/user)

Ansible Role for User Management.

Requirements
------------

This role require Ansible 2.1 or higher.

This role was designed for Ubuntu Server 14.04+.

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
<td>user_name</td>
<td>yes</td>
<td>deploy</td>
<td></td>
<td>Name of user to create.</td>
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
        - role: vitalied.user

License
-------

-   Code released under [MIT](https://github.com/vitalied/ansible-role-user/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
