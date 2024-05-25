Ansible
=========

This role installs Ansible on remote server using pip

Requirements
------------

- needs pip package manager

Role Variables
--------------

- No variables

Dependencies
------------

- pip 

Example Playbook
----------------
```bash
- hosts: servers
  become: yes
  roles:
      - gara2000.ansible
```

License
-------

BSD