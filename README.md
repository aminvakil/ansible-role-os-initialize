Role Name
=========

OS Initialize

Requirements
------------

None.

Role Variables
--------------

`hostname` which will set hostname if the vm has not been set up by cloud-init.

`unnecessary_packages` which are some packages which I have found them unnecessary over time.

`unnecessary_services` which are some services which I have found them unnecessary over time in my environments.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - role: aminvakil.os_initialize

License
-------

MIT

Author Information
------------------

[Amin Vakil](https://www.aminvakil.com/)
