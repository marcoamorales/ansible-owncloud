ansible-owncloud
================

Work in progress.

Ansible playbook to install a owncloud server.


## Use:

`ansible-playbook -i hosts site.yaml -e 'password=$(pwgen 24)'`

hosts = your host file with the IP address of the server you're running the playbook on.
password = the root password that will be set on MySQL to secure it.
