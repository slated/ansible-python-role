[![Build Status](https://travis-ci.org/slated/ansible-python-roles.svg?branch=master)](https://travis-ci.org/slated/ansible-python-roles)

Role Name
=========

Add an apt repo and install Python if no `python_python` found . Many
distros lag.

Requirements
------------

None

Role Variables
--------------

Pick your python. These are the defaults

    python_repo: ppa:jonathonf/python-3.6
    python_package: python3.6
    python_pip: python3-pip
    python_python: /usr/bin/python3.6

Dependencies
------------

None.


Example Playbook
----------------

    - hosts: servers
      - import_role:
          name: python
