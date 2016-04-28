ansible-elasticsearch-packages
==============================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-elasticsearch-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-elasticsearch-packages)

Install elasticsearch v 5.0 packages for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lsst-sqre.elasticsearch-packages }

License
-------

See the [LICENSE file](https://github.com/lsst-sqre/ansible-elasticsearch-packages/blob/master/LICENSE).
