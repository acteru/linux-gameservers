# Ansible-Roles for various games servers

Install gameserver to play with your friends on a root-server and enjoy.

## Roles
- base
- ut99 (Unreal Tournament 99)
- sotf (Sons of the Forest)
- satisfactory

## Requirements
- Rocky Linux 9
- Alma Linux 9

## Quick start
1. Add the servers to your inventory
```bash
vim inventories/default
```

2. Select the role you need and start the play

```bash
ansible-playbook plays/<game_you_want>.yml
```
