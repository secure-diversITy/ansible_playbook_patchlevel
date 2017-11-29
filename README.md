# ansible_playbook_patchlevel
Check and report Linux patchlevels

Example command to make it machine readable:

`ANSIBLE_STDOUT_CALLBACK=json ansible-playbook -i hosts check_upgrades.yml`

