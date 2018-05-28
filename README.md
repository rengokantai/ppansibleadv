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
