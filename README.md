# Workstation

## Running

1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu)
2. Provision localhost and configure periodical auto-provisioning:
    ```
    sudo ansible-pull -U https://github.com/gseric/workstation.git
    ```

During development (from project directory):
```
sudo ansible-playbook local.yml
```
