# Ansible-Roles for various games servers

## Roles
- Base
- ut99 (Unreal Tournament 99)
- sotf (Sons of the Forest)
- pal (Palword)

## Requirements
- Rocky Linux 9 vm

## Quick start
1. Add the servers to your inventory
```bash
vim inventories/default
```

2. Select the role you need and start the play

```bash
ansible-playbook plays/site.yml
```
