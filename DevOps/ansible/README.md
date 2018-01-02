# Ansible
## Getting Started

## Requirements
### Ubuntu Machine
You can use last version of Ubuntu or any other OS 
(Note: unit test done on Ubuntu 14.04 ubuntu/images/hvm-ssd/ubuntu-trusty-14.04-amd64-server-20170727 (ami-841f46ff), available through AWS).

### Ansible
```
$ sudo apt-get update
$ sudo apt-get install ansible
```

### Set up Hosts and Groups
Ansible works against multiple systems in your infrastructure at the same time. It does this by selecting portions of systems listed in Ansible’s inventory, which defaults to being saved in the location /etc/ansible/hosts. You can specify a different inventory file using the -i <path> option on the command line.

### Dependencies
Run the dependencies playbook to install all dependencies needed for Stow
```
~$ ansible-playbook dependencies.yml -u ubuntu
```
### Add Project
Set up a cronjob to periodically pull the latest changes from your git repo.

### Set up Nginx
```
~$ ansible-playbook nginx.yml -u ubuntu
```

### Configure wellness.conf
Configure the environmental variables located at /roles/stow/files/wellness.conf and then run the following command:

```
~$ ansible-playbook stow.yml -u ubuntu
```


### Resources
* [Hosts and Groups in Ansible](http://docs.ansible.com/ansible/latest/intro_inventory.html)
