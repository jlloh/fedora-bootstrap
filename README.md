Prerequisites:
- ansible
- docker

ansible-playbook --vault-id @prompt -i inventory/hosts.yml playbook.yml --tags plex
