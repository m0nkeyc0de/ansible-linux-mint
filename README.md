# Ansible workstation
Playbooks for a predictable hassle-free workstation setup.

## Boostrap
Quick and easy on Linux Mint
```bash
sudo apt install git ansible
git pull https://url.to.this/git/repo
```

## Usage
Run them locally

```bash
ansible-playbook -i localhost, mint22.yml --ask-become-pass
```
## To-Do
* Tags on tasks
* VSCodium
* Brave
* LTE modem with snap
* Dirty bytes