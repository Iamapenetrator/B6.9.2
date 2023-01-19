# B6.9.2

1. Роль DNSMASQ

```
ansible-playbook -i /etc/ansible/inventory/inventory.yml /etc/ansible/dnsmasq.yml -kK
```

2. Плейбук для создания пользователей user2 и user3

```
ansible-playbook -i /etc/ansible/inventory/inventory.yml /etc/ansible/users23.yml -kK
```

3. Роль NGINX + PHP-FPM

```
ansible-playbook -i /etc/ansible/inventory/inventory.yml /etc/ansible/nginx-php-fpm.yml -kK
```
