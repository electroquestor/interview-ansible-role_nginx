Ansible-role_nginx_ng
=========

Роль для установки NGINX в качестве reverse-proxy. Не создает конфиги и не запускает NGINX.

Requirements
------------
Копирование конфигов и запуск сервиса осуществляется в роли приложения для которого устанавливается nginx  в качестве reverse-proxy

Role Variables
--------------
```yaml
nginx_version: ""
```
Example Playbook
----------------
```yaml
- hosts: 
  become: yes
  roles:
    - { role: ansible-role_nginx_ng }
```
Example Run
-----------

ansible-playbook ansible-role_nginx_ng.yml -i ~/.ansible/hosts

License
-------

MIT

Author Information
------------------

Serebryakov Evgeniy
