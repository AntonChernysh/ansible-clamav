ansible-clamav
=========
This role installs clamav on Centos (tested on Centos 7)

Requirements
------------
ANsible 2.0+ and Python.

Use in playbook
------------
```- name: Playbook for clamav installation</br>
  hosts: someserver</br>
  roles:<br>
      - ansible-clamav</br>
```
Author Information
------------------
Anton Chernysh. AntonChernysh@gmail.com
