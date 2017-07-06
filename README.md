# Ansible-testwork
ansible playbook for install mariadb, zabbix-server,agent and dependencies

# Example Playbook
```
- hosts: zabbix-servers
  user: root
  roles:
    - Debian_Mariadb
    - Debian_Zabbix_Server
    - Debian_Zabbix_Agent
```
