## An ansible artifact + role to install the... 

Installs onto (tested):

- OpenSUSE: v15.5
- Ubuntu: 22.04

### Dependencies:

Host:

- ansible: v6.7.0
- python:  v3.8.10

### Steps to prepare:

```
git clone --recurse-submodules https://github.com/joe-opensrc/ansible-harness-hashicorp-vault.git
cd ansible-harness-hashicorp-vault  
ansible-playbook -i hosts hashicorp-vault.yml --limit docker-container-name  
```

