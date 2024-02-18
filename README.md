# Install ansible
```shell
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

# Run playbook
```shell
ansible-playbook -i inventory.yaml playbook.yaml
```

# Helpers
## Generate SSH keypare
```shell
ssh-keygen -t ed25519 -C "your_email@example.com"
# ssh-keygen
# ssh-keygen -t rsa -b 4096
```

## Copy keypare to `~/.ssh/authorized_keys`
```shell
ssh-copy-id username@remote_host
```

## Connecting to a remote server via SSH
```shell
ssh username@remote_host
```
