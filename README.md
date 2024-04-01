# Kali-configure

Using Ansible to configure my `Kali Linux` to install and configure some tools.

It will install and configure the following Tools:
- GDB + Pwndbg
- Ghidra + Ropper + CheckSec
- Configuring Firebox + Burp

To Run the playbook

1. get a sudo token by running `sudo id`
  
2. Initialte playbook
```bash
ansible-playbook main.yml
```
---

All thanks to [ippsec](https://www.youtube.com/@ippsec), whose vidoes I am following and got motivated to make my own Ansible Playbook.
