rubygems_update
=========

Update rubygems and gems for all users.
As follows is the behavior of `rubygems_update` role.

1. Install `rubygems-update` gem.
2. Run `update_rubygems` command.
3. Run `gem update` command.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

- `y10k.rubygems_environment`

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: y10k.rubygems_update
```

License
-------

BSD
