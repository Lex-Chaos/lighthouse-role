Lighouse-role
=========

Устанавливает lighthouse.

Requirements
------------

На целевой машине должна быть установлена os fedora 41

Role Variables
--------------

lighthouse_repo: репозиторий lighthouse

Dependencies
------------

На целевой машине должны быть установлены git и nginx

Example Playbook
----------------

```yml
hosts: servers
roles:
  - lighthouse
```

License
-------

MIT

Author Information
------------------

A.A.Borovik
