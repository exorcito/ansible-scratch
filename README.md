# Prerequisites

You will need:

- Ansible installed ( view 01-install)
- Verify the inventory file

## How to use it

1) ansible-galaxy install -r requirements.yml

2) Run as you want:

- ansible-playbook -i inventory-docker launch.yml -K --limit wsl