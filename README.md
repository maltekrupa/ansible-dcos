# dcos-ansible

## About

This repo uses [Ansible](https://www.ansible.com/) to configure a [Mesosphere](https://mesosphere.com/) stack following the [DC/OS Advanced Installation Guide](https://dcos.io/docs/1.7/administration/installing/custom/advanced/)

Currently all IPs are hardcoded in the hosts.ini. If you want to use a dynamic inventory, you'll need to alter the code.

- [hosts.ini](https://github.com/OldCrowEW/dcos-ansible/blob/master/hosts.ini)

## Requirements:

Ansible 2.0

## Usage
```
ansible-playbook -i hosts.ini playbook-dcos.yaml
```
