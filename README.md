# f5-bigip-aws
Ansible Playbooks to create/update/delete F5 BIG-IP in Amazon Web Services

## Create a F5 BIG-IP CFT stack:
`$ ansible-playbook create-f5-bigip-aws.yml`

## Delete a F5 BIG-IP CFT stack:
`$ ansible-playbook delete-f5-bigip-aws.yml`

Further BIG-IP configuration (i.e LTM) is not included !
There are F5 modules available with Ansible to perform such tasks but that’s not the point here
