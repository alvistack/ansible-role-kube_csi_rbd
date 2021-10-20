# Ansible Role for CSI RBD Driver on Kubernetes

<img src="/alvistack.svg" width="75" alt="AlviStack">

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-kube_csi_rbd/master)](https://gitlab.com/alvistack/ansible-role-kube_csi_rbd/-/pipelines)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-kube_csi_rbd.svg)](https://github.com/alvistack/ansible-role-kube_csi_rbd/releases)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-kube_csi_rbd.svg)](https://github.com/alvistack/ansible-role-kube_csi_rbd/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.kube_csi_rbd-blue.svg)](https://galaxy.ansible.com/alvistack/kube_csi_rbd)

Ansible Role for CSI RBD Driver on Kubernetes Installation.

## Requirements

This role require Ansible community package 4.7 or higher.

This role was designed for:

  - Ubuntu 18.04, 20.04, 21.04, 21.10
  - CentOS 7, 8 Stream
  - openSUSE Leap 15.2, Leap 15.3, Tumbleweed
  - Debian 10, 11
  - Fedora 34, 35
  - RHEL 7, 8

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
