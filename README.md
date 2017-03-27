[![Build Status](https://travis-ci.org/wtanaka/ansible-role-zsh.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-zsh)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-zsh.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-zsh)

wtanaka.zsh
===========

This ansible role installs the Z shell (zsh), a Unix shell that can be
used as an interactive login shell and as a powerful command
interpreter for shell scripting.

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.zsh

### `zsh_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "zsh" is already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
