OpenStack-Ansible pxelinux Provisioning
#######################################
:date: 2018-04-24
:tags: rackspace, openstack, ansible
:category: \*openstack, \*nix


About this repository
---------------------

This repository provides for basic "pxelinux" provisioning using debian based
operating systems.

A complete set of options can be seen within the ``playbook/group_vars/all.yml``
file.

These provisioning playbooks have been created to use static inventory. Example
static inventory used for these playbooks can be seen in the
``playbooks/inventory.yml`` file.

Scripts have been created to simplify the deployment of these playbooks and
install ansible however they are 100% optional.
