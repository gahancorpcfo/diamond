Diamond
=======

Install Diamond for collecting system statistics and pushing to graphite.

Requirements
------------

Working Python installation.

Role Variables
--------------

No variables may be set at this time.

Dependencies
------------

No other roles required.

Example Playbook
----------------

```yaml
- name: Install and configure Diamond.
  hosts: servers
  roles:
    - { 
        role: gahancorpcfo.diamond,
        some_variable: 42 
    }
```

License
-------

BSD

Author Information
------------------

This was written by Xander Harris for the Gahan Corporation.
