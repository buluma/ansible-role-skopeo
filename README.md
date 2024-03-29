# Ansible role [skopeo](https://galaxy.ansible.com/ui/standalone/roles/buluma/skopeo/documentation)

Install and configure Skopeo on your system.

|GitHub|Version|Issues|Pull Requests|Downloads|
|------|-------|------|-------------|---------|
|[![github](https://github.com/buluma/ansible-role-skopeo/actions/workflows/molecule.yml/badge.svg)](https://github.com/buluma/ansible-role-skopeo/actions/workflows/molecule.yml)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-skopeo.svg)](https://github.com/buluma/ansible-role-skopeo/releases/)|[![Issues](https://img.shields.io/github/issues/buluma/ansible-role-skopeo.svg)](https://github.com/buluma/ansible-role-skopeo/issues/)|[![PullRequests](https://img.shields.io/github/issues-pr-closed-raw/buluma/ansible-role-skopeo.svg)](https://github.com/buluma/ansible-role-skopeo/pulls/)|[![Ansible Role](https://img.shields.io/ansible/role/d/buluma/skopeo)](https://galaxy.ansible.com/ui/standalone/roles/buluma/skopeo/documentation)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/buluma/ansible-role-skopeo/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- name: Converge
  hosts: all
  tasks:
    - name: "Include buluma.skopeo"
      include_role:
        name: "buluma.skopeo"
```

Also see a [full explanation and example](https://buluma.github.io/how-to-use-these-roles.html) on how to use these roles.

## [Role Variables](#role-variables)

The default values for the variables are set in [`defaults/main.yml`](https://github.com/buluma/ansible-role-skopeo/blob/master/defaults/main.yml):

```yaml
---
# defaults file for skopeo
```

## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-skopeo/blob/master/requirements.txt).


## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:

![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-skopeo/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/buluma):

|container|tags|
|---------|----|
|[Alpine](https://hub.docker.com/repository/docker/buluma/alpine/general)|all|
|[Amazon](https://hub.docker.com/repository/docker/buluma/amazonlinux/general)|Candidate|
|[EL](https://hub.docker.com/repository/docker/buluma/enterpriselinux/general)|all|
|[Debian](https://hub.docker.com/repository/docker/buluma/debian/general)|all|
|[Fedora](https://hub.docker.com/repository/docker/buluma/fedora/general)|all|
|[opensuse](https://hub.docker.com/repository/docker/buluma/opensuse/general)|all|
|[Ubuntu](https://hub.docker.com/repository/docker/buluma/ubuntu/general)|all|

The minimum version of Ansible required is 2.12, tests have been done to:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them in [GitHub](https://github.com/buluma/ansible-role-skopeo/issues)

## [Changelog](#changelog)

[Role History](https://github.com/buluma/ansible-role-skopeo/blob/master/CHANGELOG.md)

## [License](#license)

[Apache-2.0](https://github.com/buluma/ansible-role-skopeo/blob/master/LICENSE)

## [Author Information](#author-information)

[Shadow Walker](https://buluma.github.io/)

