# ansible-hadoop
================
- Install Hadoop Cluster with Ansible.
- OS: CentOS 7
- JDK: Openjdk-1.8
- Hadoop version: 3.0.3

## Before Install
Use DNS Server or update /etc/hosts for all servers
Update the the variables in vars/main.yml

### Install Master
Run the playbook.

```
ansible-playbook -i hosts master.yml
```

### Install Workers

Run the playbook.
```
ansible-playbook -i hosts workers.yml

```
