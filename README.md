# Ansible

Для запуска нужно выполнить:
```bash
$ vagrant up && ansible-playbook /playbook/nginx.yml
```
Поднимутся 2 виртуальные машины с NGINX на порту 8080 **nginx01** и **nginx02**

Для проверки 
```bash
$ curl 192.168.56.50:8080
```

```bash
$ curl 192.168.56.51:8080
```
