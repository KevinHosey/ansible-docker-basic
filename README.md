# ansible-docker-basic
Ansible playbooks for installing Docker and running basic services

## Instructions

Update `inventory.yml` with the IP address of the server to run on.

Run the playbook with
```
ansible-playbook provision.yml -i inventory.yml
```
