# ppansibleadv
## 1. Introduction
### Demo - Setup Environment
inventory.txt
```
target1 ansible_host=192.1.1.1 ansible_ssh_pass=passw)rd
```
ansible.cfg
```
host_key_checking = False # default=true
```
```
ansible target1 -m ping -i inventory.txt
```
## 2. Web Application
### Web Application
step
- Identity server
- Python
- Install Configure Start
- Install Flask
- Source Code

### Demo - Developing Playbook for Web Application

```
- name: create database user
  mysql_user:
    name: db_user
    password: Passw0rd
    priv: '*.*:ALL'
    state: present
    host: '%'
- name: copy
  copy: src=app.py dest=/opt/app.py
```

## 3. File Seperation
## 4. Roles
### Demo - Roles
