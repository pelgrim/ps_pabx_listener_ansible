# PsPabxListener Ansible Playbook
Orchestrates the deploy of a [PsPabxListener container](https://github.com/pelgrim/ps_pabx_listener_docker).

## How to use it
* First of all, this playbook is intended to be run on a 64-bit Ubuntu Server host.
* Configure it by editing the following files:

  * group_vars/all
  * group_vars/behind_proxy
  * hosts

* Then, run it as you would run any other playbook. For example:

      ansible-playbook -i hosts --ask-become-pass site.yml

## What else?
Maintained by Lucas Vieira <lucas@vieira.io>, July 2016.

If you noticed a problem whatsoever, please, let me know.

Also, accepting PRs for better spec tests and anything else, really.
