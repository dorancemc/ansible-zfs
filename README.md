ansible-zfs
=========

Role to create basic zfs pools

Requirements
------------

None 

Role Variables
--------------

To details about variables could be find in defaults/main folder

Dependencies
------------

None 

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: dorancemc.ansible-zfs, tags ["zfs"] }
```

License
-------

BSD

Author Information
------------------

Dorance Martinez @dorancemc

References
------------------
https://github.com/mrlesmithjr/ansible-zfs
