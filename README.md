## racker
(in progress...) 

A simple docker registry for aws supplied by Ansible

## Configure:
Review vars/common_vars.yml and configure your vars

# run:

ansible-playbook racker.yml

ansible-playbook test.yml -vvvv --extra-vars "boto_profile=your aws credentials  ansible_ssh_private_key_file=your path.pem"
