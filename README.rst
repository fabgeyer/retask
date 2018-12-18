Welcome to retask
=================
retask is a python module to create distributed task
queues using Redis.

You can read the latest documentation `here <http://retask.readthedocs.org/>`_.

This version contains the following changes:

- The expire time for a result can now be set using the default_expire attribute of the queue
- Ability to send data in a queue without the default JSON serialization of retask by using the raw parameter when initializing a queue


Installation
------------

::

    $ sudo apt install redis-server
    $ pip install --upgrade https://github.com/fabgeyer/retask/archive/master.tar.gz


