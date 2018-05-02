# Desktop configuration ansible playbook

A simple ansible-playbook that I keep to quickly install a new machine for me to do development work, whenever I decide to upgrade my computer or have a new one it's very handy. 

Saves me considerable trouble and time. Last used in Ubuntu 16.04 with ansible and playbook 2.5.0

To use it install [ansible](http://docs.ansible.com/ansible/latest/index.html) and [ansible-playbook](http://docs.ansible.com/ansible/latest/cli/ansible-playbook.html) and: 

```bash
ansible-playbook local-config.yml --extra-vars "ansible_sudo_pass=$SUDO_PWD_LOCAL_MACHINE_TO_BE_CONFIGURED"
```


