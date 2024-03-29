build-ppl-ubuntu-ansible
========================

[![Actions Status](https://github.com/MasWag/build-ppl-ubuntu-ansible/workflows/Xenial/badge.svg)](https://github.com/MasWag/build-ppl-ubuntu-ansible/actions)
[![Actions Status](https://github.com/MasWag/build-ppl-ubuntu-ansible/workflows/Bionic/badge.svg)](https://github.com/MasWag/build-ppl-ubuntu-ansible/actions)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An Ansible playbook to build [Parma Polyhedra Library](https://www.bugseng.com/parma-polyhedra-library) from scratch on Ubuntu. We use checked-int64 as the coefficients.

This playbook is tested on Ubuntu 16.04 LTS (Xenial) and 18.04 LTS (Bionic).

Usage
-----

```bash
ansible-playbook ./build_ppl.yaml
```
