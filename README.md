# OpenStack Deployment using Ansible

## Description
This project automates the deployment of an OpenStack environment (Nova, Swift, Trove) using Ansible on an EC2 instance running Ubuntu 22.04.

## How to Run
```bash
ansible-playbook site.yml
```

## How to Destroy
```bash
ansible-playbook destroy.yml
```

## How to Provision EC2 (Terraform)
```bash
cd terraform
terraform init
terraform apply
```
