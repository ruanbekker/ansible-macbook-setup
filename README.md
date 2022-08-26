# ansible-macbook-setup
Installs homebrew packages via Ansible

## Install

Install dependencies:

```bash
pip install ansible==4.9.0
```

## Run Playbook

Run the playbook with:

```bash
ansible-playbook playbooks/homebrew.yaml --limit=my.laptop
```

To target specific tasks:

```bash
ansible-playbook playbooks/homebrew.yaml --limit=my.laptop --tags=packages
```
