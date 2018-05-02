# Desktop configuration ansible playbook

This is the ansible playbook that I keep to quickly install a new machine for me to work on whenever I decide to upgrade my computer or have a new one. It saves me a lot of trouble and time.

To use it install [ansible](http://docs.ansible.com/ansible/latest/index.html) and [ansible-playbook](http://docs.ansible.com/ansible/latest/cli/ansible-playbook.html) and: 

```bash
ansible-playbook local-config.yml --extra-vars "ansible_sudo_pass=$SUDO_PWD_LOCAL_MACHINE_TO_BE_CONFIGURED"
```

