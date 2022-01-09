# Workstation

## Provisioning

Instructions:
1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu)
2. Provision localhost and configure periodical auto-provisioning:
    ```
    sudo ansible-pull -U https://github.com/gseric/workstation.git
    ```

During development (from project directory):
```
sudo ansible-playbook -i hosts local.yml
```

Keep in mind that device drivers are not provisioned since they are hardware dependent.
