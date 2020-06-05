Ansible Role: Docker
====================

Installs the latest version of Docker on a host.

Requirements
------------

This role is designed to run on CentOS 7. It is modular, and can have other operating system flavors added rather easily in the future. This role requires Ansible 2.9 or later.

Role Variables
--------------

This role has no variables to declare.

Dependencies
------------

This role has no dependencies on other Ansible roles.

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - docker
```

License
-------

MIT
