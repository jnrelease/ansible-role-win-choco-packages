Ansible Role: win_choco_packages
=========

Installs [chocolatey](https://community.chocolatey.org/packages) packages on a Windows host.

Requirements
------------

None.

Role Variables
--------------

    choco_packages:
      - notepadplusplus
      - googlechrome
      ...

Sets the list of chocolately packages to install.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: win_choco_packages

License
-------

BSD

Author Information
------------------

This role was created by Javel Wilson.
