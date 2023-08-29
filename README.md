# Kali-configure

Using Ansible to configure my `Kali Linux` to install and configure some tools.

It will install and configure the following Tools:
- GDB + Pwndbg
- Ghidra + Ropper + CheckSec
- Configuring Firebox + Burp
- ~VsCode~

To Run the playbook

1. Install dependencies
```bash
ansible-galaxy install -r requirements.yml
```
2. get a sudo token by running `sudo id`
  
3. Initialte playbook
```bash
ansible-playbook main.yml
```
---

All thanks to [ippsec](https://www.youtube.com/@ippsec), whose vidoes I am following and got motivated to make my own Ansible Playbook.
