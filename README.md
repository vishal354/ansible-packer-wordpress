# Ansible Packer Wordpress
This repo can be used to create an AMI. This AMI can used to horizontally autoscale a WordPress site.

## Dependencies
- Packer
- Ansible

## Instruction
Run this packer commands from the root directory of the repository

```
packer init packer/wordpress.pkr.hcl
packer build packer/wordpress.pkr.hcl
```