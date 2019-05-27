[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Servidor%20DHCP-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-dhcp-server)  [![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-dhcp-server.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-dhcp-server)

---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [ISC DHCP Server](https://www.isc.org/downloads/dhcp/)
------------

Description
------------

 *

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-dhcp-server
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
