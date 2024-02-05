# Dynatrace OneAgent Configuration Playbook and Role

In its current state, collection consist of a single role that uses `oneagentctl` to configure Dynatrace OneAgent on Linux and Windows operating systems using dedicated configuration and ensures the OneAgent service maintains a running state.

## Requirements

Using this collection requires the following:

* Ansible >= 2.9.0, < 2.10.0

## Use

Edit the inventory.yml, oneagent_config.yml and roles/default/main.yml  

Use `ansible-playbook oneagentctl_config.yml -i inventory.yml` to run the playbook
