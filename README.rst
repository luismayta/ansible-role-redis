Ansible Role for Redis
======================

|Build Status| |GitHub issues| |GitHub license|

:Version: 0.0.0
:Web: https://github.com/equipindustry/ansible-role-redis
:Download: http://github.com/equipindustry/ansible-role-redis
:Source: http://github.com/equipindustry/ansible-role-redis
:Keywords: ansible-role-redis

.. contents:: Table of Contents:
    :local:

Ansible Galaxy role for `Redis`_.

Requirements:
=============

List of applications:

- `Python 3.7.3`_
- `Docker`_
- `Docker Compose`_

Install
=======

Install it with the following command:

.. code-block:: bash

    $ ansible-galaxy install equipindustry.redis

Role Variables
==============

The default role variables in ``defaults/main.yml`` are:

.. code-block:: yaml

    redis_nro_databases: 16
    redis_dbfilename: root
    redis_bind_ip: 0.0.0.0

Dependencies
============

None

Example Playbook
================

See the `examples <./examples/>`__ directory.

To run this playbook with default settings, create a basic playbook like
this:

.. code:: yaml

    - hosts: servers
        roles:
        - equipindustry.redis

License
=======

Apache2

Changelog
=========

Please see `CHANGELOG`_ for more information what
has changed recently.

Contributing
============

Please see `CONTRIBUTING`_ for details.

Credits
=======

-  `author`_
-  `contributors`_

Made with :heart: :coffee: and :pizza: by `author`_ and `company`_.

.. Badges:

.. |Build Status| image:: https://travis-ci.org/equipindustry/ansible-role-redis.svg
   :target: https://travis-ci.org/equipindustry/ansible-role-redis
.. |Ansible Galaxy| image:: https://img.shields.io/badge/galaxy-equipindustry.redis-blue.svg
   :target: https://galaxy.ansible.com/equipindustry/ansible-role-redis/
.. |GitHub issues| image:: https://img.shields.io/github/issues/equipindustry/ansible-role-redis.svg
   :target: https://github.com/equipindustry/ansible-role-redis/issues
.. |Average time to resolve an issue| image:: http://isitmaintained.com/badge/resolution/equipindustry/ansible-role-redis.svg
   :target: http://isitmaintained.com/project/equipindustry/ansible-role-redis
.. |Percentage of issues still open| image:: http://isitmaintained.com/badge/open/equipindustry/ansible-role-redis.svg
   :target: http://isitmaintained.com/project/equipindustry/ansible-role-redis
.. |GitHub license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE

.. Links
.. _`changelog`: CHANGELOG.rst
.. _`contributors`: AUTHORS
.. _`contributing`: CONTRIBUTING.rst

.. _`company`: https://github.com/equipindustry
.. _`author`: https://github.com/luismayta

.. dependences
.. _Redis: https://redis.io
.. _Python: https://www.python.org
.. _Python 3.7.3: https://www.python.org/downloads/release/python-373
.. _Docker: https://www.docker.com/
.. _Docker Compose: https://docs.docker.com/compose/
