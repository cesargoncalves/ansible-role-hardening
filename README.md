Ansible role hardening
=========

Ansible role that applies essential system hardening practices to improve security.

- SSH authentication via public keys only
- root login disabled

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  become: true
  roles:
     - cesargoncalves.hardening 
```

License
-------

GPL-3.0

Author Information
------------------

Role created by [cesargoncalves](https://github.com/cesargoncalves)
