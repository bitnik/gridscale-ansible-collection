# Ansible Collection for gridscale

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/bitnik/gridscale-ansible-collection/main.svg)](https://results.pre-commit.ci/latest/github/bitnik/gridscale-ansible-collection/main)

An ansible collection for gridscale.

Currently only an inventory plugin is implemented.

Documentation: https://bitnik.github.io/gridscale-ansible-collection/

## Installation

```sh
ansible-galaxy collection install git+https://github.com/bitnik/gridscale-ansible-collection.git,0.1.0
```

```sh
collections:
  - name: https://github.com/bitnik/gridscale-ansible-collection.git
    type: git
    version: 0.1.0
```
