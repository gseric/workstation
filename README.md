# Workstation

## Running

First time/forced:
```
sudo ansible-pull -U https://github.com/gseric/workstation.git
```

Command above installs cron job which executes itself periodically.

During development (from project directory):
```
sudo ansible-playbook local.yml
```
