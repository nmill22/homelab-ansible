# Ansible Role: Hub

[![Build Status](https://travis-ci.org/fubarhouse/ansible-role-hub.svg?branch=master)](https://travis-ci.org/fubarhouse/ansible-role-hub)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/fubarhouse/ansible-role-hub/master/LICENSE)

* Installs Jetbrains' Hub on Ubuntu, Debian, RedHat, CentOS and REHL servers.

## Preview
![screenshot](https://github.com/fubarhouse/ansible-role-jetbrains-hub/raw/master/images/splash-screen.png)

## Role Variables

    hub_install_dir: /usr/local/hub
    hub_domain: hub.vagrant.dev
    hub_port: 8115
    hub_user: hub
    hub_mode: 0777

## Dependencies

* Java 1.8

## Installation

* Add the role to your playbook.
* No special settings are required if the dependencies are met.

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Karl Hepworth](https://twitter.com/fubarhouse).
