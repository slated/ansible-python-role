[![Build Status](https://travis-ci.org/slated/ansible-python-role.svg?branch=master)](https://travis-ci.org/slated/ansible-python-role)

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

    python_repo: ppa:deadsnakes/ppa
    python_package: python3.8
    python_pip: python3-pip
    python_python: /usr/bin/python3.8

Dependencies
------------

None.


Example Playbook
----------------

    - hosts: servers
      - import_role:
          name: python
