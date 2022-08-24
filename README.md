Ansible Role: ansible_role_hpe_proliant_repos
=========

Installs HPE repositories for Proliant servers on the following Linux distributions:

<ul>
<li>Red Hat Enterprise Linux 7
<li>Red Hat Enterprise Linux 8
</ul>


Requirements
---------------

None.

Role variables
---------------

None.


Dependencies
------------

None.


Example Playbook
----------------


    - hosts: servers

      roles:
         - ansible_role_hpe_spp_repo

License
-------

MIT

Author Information
------------------

Mattias Jonsson