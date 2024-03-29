Ansible Role: Kubectl
=====================

[![Build Status](https://github.com/webarchitect609/ansible-role-kubectl/actions/workflows/build.yml/badge.svg)](https://github.com/webarchitect609/ansible-role-kubectl/actions/workflows/build.yml)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-kubectl?sort=semver)](https://github.com/webarchitect609/ansible-role-kubectl/releases)

[![Downloads](https://img.shields.io/ansible/role/d/webarchitect609/kubectl)](https://galaxy.ansible.com/ui/standalone/roles/webarchitect609/kubectl)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-kubectl)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/ui/standalone/namespaces/7493/)

Installs [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/) from the official apt repo.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: webarchitect609.kubectl }
```

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
