# Workstation

## Provisioning

Instructions:
1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu)
1. [Install Git](https://git-scm.com/download/linux)
1. Provision localhost and configure periodical auto-provisioning (add `--check` for dry run):
    ```
    sudo ansible-pull --url=https://github.com/gseric/workstation.git
    ```

During development (from project directory; add `--check` for dry run):
```
sudo ansible-playbook --inventory=hosts local.yml
```

Keep in mind that device drivers are not provisioned since they are hardware dependent.
