Ansible_role_install_docker 
=========

Роль устанавливает пакеты `docker`и `docker-compose` из оффициального репозитория Docker.

Requirements
------------

- система на базе Ubuntu

Role Variables
--------------

Переменные определены в файле defaults/main.yml:
```
url_path # URL расположения ключа GPG оффициального репозитория Docker
```

Example Playbook
----------------

Пример плейбука применительно к хостам группы `Ubuntu`:
```
    - hosts: Ubuntu
      roles:
         - ansible_role_install_docker 
```

License
-------

BSD

Author Information
------------------
AlZa 2022
