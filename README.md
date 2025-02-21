# ACIT-4640-Lab-7
#### Generate key for AWS
'ssh-keygen -t ed25519 -C "aws" -f ~/.ssh/aws'\
If needed, add --region to import key script\
Use SSO login or Environmental Variable for your AWS Profile
#### Terraform
`terraform init`\
`terraform validate`\
`terraform apply`\
#### Hosts.yml
Put your DNS name under host block

#### Ansible
Before running the YAML file, it is good practice to do syntax check before hand
`ansible-playbook --syntax-check playbook.yml`\
`ansible-playbook -i inventory/hosts.yml playbook.yml`
