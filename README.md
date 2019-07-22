awx role
=========
[![License](https://img.shields.io/badge/license-Apache-green.svg?style=flat)](https://raw.githubusercontent.com/lean-delivery/ansible-role-awx/master/LICENSE)
[![Build Status](https://travis-ci.org/lean-delivery/ansible-role-awx.svg?branch=master)](https://travis-ci.org/lean-delivery/ansible-role-awx)
[![Build Status](https://gitlab.com/lean-delivery/ansible-role-awx/badges/master/build.svg)](https://gitlab.com/lean-delivery/ansible-role-awx)
[![Galaxy](https://img.shields.io/badge/galaxy-lean__delivery.awx-blue.svg)](https://galaxy.ansible.com/lean_delivery/awx)
![Ansible](https://img.shields.io/ansible/role/d/role_id.svg)
![Ansible](https://img.shields.io/badge/dynamic/json.svg?label=min_ansible_version&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv1%2Froles%2Frole_id%2F&query=$.min_ansible_version)

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should
be mentioned here. For instance, if the role uses the EC2 module, it may be a
good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: awx, x: 42 }

Known Bugs
----------------
* Idempotency is not working for creation of AWX superuser: [URL](https://github.com/ansible/ansible/issues/29786)

License
-------
Apache

Author Information
------------------

authors:
  - epam-devops@lean-delivery.com
