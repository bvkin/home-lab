# home-lab
Configurations for my homelab

# Galaxy Dependancies
`ansible-galaxy install -r requirements.yml -p galaxy`

# Ansible Vault
### Encrypting with password file

### Using password file in playbooks
`ansible-playbook --vault-password-file /path/to/password-file -i /path/to/inventory /path/to/playbook`

# Important Links
[Setting up qcows](https://www.cyberciti.biz/faq/create-vm-using-the-qcow2-image-file-in-kvm/)
