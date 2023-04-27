ansible-kali-setup
==============================
[![Actively Maintained](https://img.shields.io/badge/Maintenance%20Level-Actively%20Maintained-green.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)

Setup Kali Linux the way I like it.

Installs tools useful for penetration testing, purple-teaming and CTFs.

Requirements
------------
Requires Ansible 2.10 or later.

Will require an additional ~15 GiB disk space With everything enabled.


Quick Start
------------
```bash
## Perform updates (optional)
sudo apt update -y && sudo apt upgrade -y

## Install Ansible
sudo apt install -y ansible

## Download the playbook
git clone https://github.com/dan-kir/ansible-kali-setup

cd ./ansible-kali-setup

## Run Playbook
ansible-playbook ansible-kali-setup.yml -K

```


Role Variables
--------------
Kali user is default 'kali'

This can be changed at `roles/ansible-kali-setup/defaults/main.yml`

License
-------
GPL-3.0 License


Author Information
------------------
This role was created by Dan Kir
