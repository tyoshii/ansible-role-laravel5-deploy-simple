Laravel5 Deploy Simple
======================

ref: https://github.com/blacklight-design/ansible-laravel5-deploy

Deployment role for Laravel 5 apps. Deployment can be doen via Git ONLY NOW.

Requirements
------------

- Ansible >= 2.0
- php (ref: https://galaxy.ansible.com/geerlingguy/php/

Role Variables
--------------

ref: https://github.com/blacklight-design/ansible-laravel5-deploy

this role owned variables TBD.

Example Playbook
----------------

- playbook
```
- hosts: servers
  gather_fact: true

  roles:
    - tyoshii.laravel5-deploy-simple
```

License
-------

MIT
