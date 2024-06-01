## Домашнее задание LDAP

### Описание домашнего задания
```
- Ansible-playbook установивает FreeIPA, конфигурирует клиентов
- Firewall включен
- VMs разворачиваются в среде VMware vSphere 7 из шаблона Centos 8 Stream

Файлы:

- network.yml:            ansible playbook создания и настройки VMs
- vars.yml:               переменные для создания VMs в VMware vSphere 7
- host:                   inventory
- protocol.pdf:           протокол работы       
- templates\host.j2:      /etc/hosts сервера и клиентов
