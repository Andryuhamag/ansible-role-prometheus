
`Ansible` роль для установки `Prometheus`
------------

Пример использования:
```
---
- name: Install Prometheus
  hosts: prometheus
  become: true
  roles:
    - role: ansible-role-prometheus

```
