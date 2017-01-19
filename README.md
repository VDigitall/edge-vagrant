# edge-vagrant
## System requirements (sandbox):
* RAM: 2GB;
* HDD: 10 GB;
* CPU: DualCore

## Requirements:
* [Vagrant](https://www.vagrantup.com/docs/getting-started/);
* [Ansible](http://docs.ansible.com/ansible/intro.html).

### Settings:
1. Change in vars/dredge.yml `user_agent`;
2. Set in vars/dredge.yml `resources`: example `resource: [tenders, plans, contracts]`. Allowed values (auctions, contracts, plans, tenders)

## Usage:
From directory where placed Vagrant file run command in terminal:
```
vagrant up --provider=<your_provider>
```
example:
```
vagrant up --provider=virtualbox
```
More informations: https://www.vagrantup.com/docs/providers/
