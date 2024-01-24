Lighthouse
=========

This role can install lighthouse.

Role Variables
--------------

| vars | description |
|------|-------------|
| lighthouse_location_dir | installation directory |
| lighthouse_vcs | dowloading a resource |
| nginx_user_name | nginx user name |

Dependencies
------------

To download a resource, you a need to install git

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      remote_user: root
      roles:
        - lighthouse-role

License
-------

MIT

Author Information
------------------

Anikeev Ilya.
