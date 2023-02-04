# [skopeo](#skopeo)

Install and configure Skopeo on your system.

|GitHub|GitLab|Quality|Downloads|Version|Issues|Pull Requests|
|------|------|-------|---------|-------|------|-------------|
|[![github](https://github.com/buluma/ansible-role-skopeo/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-skopeo/actions)|[![gitlab](https://gitlab.com/buluma/ansible-role-skopeo/badges/master/pipeline.svg)](https://gitlab.com/buluma/ansible-role-skopeo)|[![quality](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/buluma/skopeo)|[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/buluma/skopeo)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-skopeo.svg)](https://github.com/buluma/ansible-role-skopeo/releases/)|[![Issues](https://img.shields.io/github/issues/buluma/ansible-role-skopeo.svg)](https://github.com/buluma/ansible-role-skopeo/issues/)|[![PullRequests](https://img.shields.io/github/issues-pr-closed-raw/buluma/ansible-role-skopeo.svg)](https://github.com/buluma/ansible-role-skopeo/pulls/)|

## [Example Playbook](#example-playbook)

This example is taken from `molecule/default/converge.yml` and is tested on each push, pull request and release.
```yaml
---
- name: Converge
  hosts: all
  tasks:
    - name: "Include buluma.skopeo"
      include_role:
        name: "buluma.skopeo"
```


## [Role Variables](#role-variables)

The default values for the variables are set in `defaults/main.yml`:
```yaml
---
# defaults file for skopeo
```

## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-skopeo/blob/main/requirements.txt).


## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:

![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-skopeo/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/buluma):

|container|tags|
|---------|----|
|alpine|all|
|amazon|Candidate|
|el|all|
|debian|all|
|fedora|all|
|opensuse|all|
|ubuntu|all|

The minimum version of Ansible required is 2.10, tests have been done to:

- The previous version.
- The current version.
- The development version.


If you find issues, please register them in [GitHub](https://github.com/buluma/ansible-role-skopeo/issues)

## [Changelog](#changelog)

[Role History](https://github.com/buluma/ansible-role-skopeo/blob/master/CHANGELOG.md)

## [License](#license)

Apache-2.0

## [Author Information](#author-information)

[buluma](https://buluma.github.io/)

### [Special Thanks](#special-thanks)

Template inspired by [Robert de Bock](https://github.com/robertdebock)
