Ansible Role: FileSystem Settings
=========

Ansible role to configure filesystem security settings on Linux Servers.

Requirements
------------

The role does not require anything to run on Ubuntu, Debian or RHEL and its derivatives.

Dependencies
------------

None.

Example Playbook
----------------

``` yaml
    - hosts: servers
      roles:
         - role: mikepruett3.filesystem-security
```

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-filesystem-security)
