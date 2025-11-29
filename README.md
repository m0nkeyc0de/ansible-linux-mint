# Ansible Linux Mint
Playbooks for a predictable hassle-free Linux Mint workstation setup.

## Boostrap
Quick and easy on Linux Mint
```bash
sudo apt install git ansible
git pull https://url.to.this/git/repo
```

## Usage
System level modifications

```bash
ansible-playbook mint22_system.yml --ask-become-pass
```

User level modifications
```bash
ansible-playbook mint22_user.yml
```