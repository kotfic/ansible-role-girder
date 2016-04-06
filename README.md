girder.girder
=============
[![Apache 2.0](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/girder/ansible-role-girder/master/LICENSE)
[![Build Status](https://travis-ci.org/girder/ansible-role-girder.svg?branch=master)](https://travis-ci.org/girder/ansible-role-girder)

An Ansible role to install [Girder](https://github.com/girder/girder).

Requirements
------------

This is intended to be run on a clean Ubuntu 14.04 system.

Role Variables
--------------

The following variables may be overridden:

* `girder_path`: Path to download and build Girder in.
* `girder_version`: Git commit-ish for fetching Girder.

Dependencies
------------

Your `requirements.yml` file should contain:

```
---

- src: nodesource.node
- src: Stouts.mongodb
```
