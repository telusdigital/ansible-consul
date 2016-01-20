# ansible-consul

Consul is a tool for service discovery and configuration. Consul is distributed, highly available, and extremely scalable.


[![Build Status](https://travis-ci.org/telusdigital/ansible-consul.svg?branch=master)](https://travis-ci.org/telusdigital/ansible-consul)

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Tunables
--------
* None

Dependencies
------------
* [telusdigital.apt-repository](https://github.com/telusdigital/ansible-apt-repository/)

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.consul

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* [Chris Olstrom](https://colstrom.github.io/) | [e-mail](mailto:chris@olstrom.com) | [Twitter](https://twitter.com/ChrisOlstrom)
