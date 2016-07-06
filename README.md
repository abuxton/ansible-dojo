Ansible Dojo
------------

This repo is for simple purposes of learning Ansible and ansible functionality.

#Install

Installing Ansible, OSX for my needs http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip


Oscar Puppet Enterprise
----------------------------

## Dependancies
To make best use of this lab you will need Vagrant and the Oscar related plugins

### Vagrant
https://www.vagrantup.com/
https://github.com/mitchellh/vagrant

### Oscar
https://github.com/oscar-stack/oscar

### Puppet Enterprise
You'll need a extraction tarball of Puppet Enterprise from Puppet.com.
Unce you have the .tgz in the root of the repo(no do not commit it to git) you need to updated config/pe_build.yml with the version number from the .tgz name.

##Usage

This repository is provided as a Vagrant managed Puppet Enterprise server and agent for Lab work.

Once you have cloned the repository locally simply run `vagrant up`


###Author

Central Delivery Enablement Platform (CDEP)

