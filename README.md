# Docker Swarm in Vagrant
## Requirements
* ansible
* vagrant
## Running
Before running `vagrant up` download all ansible-roles:
```
ansible-galaxy install --roles-path roles -r requirements.yml
vagrant up
ansible-playbook swarm.yml
```