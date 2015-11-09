# 4pisky-voeventdb

These are the ansible scripts used to set up and maintain our web-service at 
http://voeventdb.4pisky.org.

This configuration builds upon [Ansible][] [roles][] for installing 
the [voeventdb][] service, alongside a Comet broker to keep it continuously updated:
 - https://github.com/timstaley/ansible-voeventdb
 - https://github.com/timstaley/ansible-comet
 
[Ansible]: http://www.ansible.com/configuration-management
[roles]: http://docs.ansible.com/ansible/playbooks_roles.html
[voeventdb]: https://github.com/timstaley/voeventdb
