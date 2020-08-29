Ansible role for Guake3 terminal
================================

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-icamys.guake3--terminal-blue)](https://galaxy.ansible.com/icamys/ansible_guake3)

Use this role to install Guake 3 terminal to Ubuntu from sources in your playbook:
```yaml
roles:
  - icamys.ansible-guake3
```

## Variables

Add Guake to startup:
```yaml
guake_add_to_startup: yes
```

Start Guake after setup:
```yaml
guake_start_after_setup: yes
```

Select Guake version 
(see [Guake releases page](https://github.com/Guake/guake/tags) for details) :
```yaml
guake_git_version: 3.7.0
```

The place to clone Guake source:
```yaml
guake_git_path: /tmp/guake
```