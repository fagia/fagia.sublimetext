Fagia Sublime Text
=========

[![Build Status](https://travis-ci.org/fagia/sublimetext.svg?branch=master)](https://travis-ci.org/fagia/sublimetext)

Sublime Text editor installer/updater (stable version) for Debian-based distros. Based on: https://www.sublimetext.com/docs/3/linux_repositories.html#apt

Requirements
------------

As of now, only Ubuntu-based distros are supported for this role.

Example Playbook
----------------

    - hosts: dev-machines
      roles:
         - { role: fagia.sublimetext }

Role Variables
----------------

It's possible to customize Sublime Text user preferences, see `defaults/main.yml`

License
-------

BSD

Author Information
------------------

https://github.com/fagia
