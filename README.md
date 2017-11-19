# Ansible Role: Nginx

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.nginx.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.nginx) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nginx-blue.svg)](https://galaxy.ansible.com/sbaerlocher/nginx)

## Description

Ansible role for installing and Configuration Nginx on RHEL/CentOS, Debian/Ubuntu or ArchLinux.

## Installation

```bash
ansible-galaxy install sbaerlocher.nginx
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| | | |
| | | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.nginx
```

## Changelog

### 1.2

* add feature site disable

### 1.1

* clean role
* add more feature

### 1.0

* initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2016, Simon Bärlocher