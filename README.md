ansible-clamav
=========
This role installs clamav on Centos (tested on Centos 7)

Requirements
------------
Ansible 2.0+ and Python.

Use in playbook
------------
```- name: Playbook for clamav installation</br>
  hosts: someserver
  roles:
      - ansible-clamav
```
Author Information
------------------
Anton Chernysh. AntonChernysh@gmail.com
