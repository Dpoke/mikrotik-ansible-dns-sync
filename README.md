# mikrotik-ansible-dns-sync
Allow sync static dns records between 2 or more mikrotik routers.

# This repo just an example how such task can be done.
Use it at your own risk without warranty

- Playbook was checked with RouterOS version 6.47
- Clone this repo
- Edit vars/dns.yml vars/routers.yml files.
- Run ansible-playbook setup_router.yml --ask-vault-pass
