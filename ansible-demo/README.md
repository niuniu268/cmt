# Ansible playbook example

Let's write a playbook to:

- ALL HOSTS
  - [x] update all packages on the system (`apt upgrade`)
  - [x] install some needed tools (`nano`, `vim`, `sudo`)
  - [x] install a firewall (`ufw`)
  - [x] start and enable `ufw`
  - [x] configure firewall (port `22` open on all hosts, port `80` and `443` for webserver, port `3306` for db)
  - [x] set up users with passwords, ssh-pubkeys, groups, sudo permissions, etc
- WEBSERVER
  - [x] install a webserver
  - [x] configure webserver
- DATABASE
  - [ ] install db server
  - [ ] configure db server
  