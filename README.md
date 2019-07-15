[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Servidor%20DHCP-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-dhcp-server) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-dhcpd.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-dhcpd)

---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [ISC DHCP Server](https://www.isc.org/downloads/dhcp/)
------------

Description
------------

 *

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.dhcpd
```

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
    - dhcpd
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)