cloud3rsio.time
=========

Update time setting.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.time
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `time_zone` | `Asia/Tokyo` | String |

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.time
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
