.. image:: https://travis-ci.org/nlsdfnbch/hermes.svg?branch=master
    :target: https://travis-ci.org/nlsdfnbch/hermes
.. image:: https://coveralls.io/repos/github/nlsdfnbch/hermes/badge.svg?branch=master
    :target: https://coveralls.io/github/nlsdfnbch/hermes?branch=master
.. image:: https://readthedocs.org/projects/hermes-framework/badge/?version=latest
    :target: http://hermes-framework.readthedocs.io/en/latest/?badge=latest


Hermes
======
ZMQ-based framework for building simple Pub-Sub Systems, written in Python 3.

It offers thread-based wrappers for zmq's SUB and PUB sockets, a pre-configured proxy device
and a Node class to pull it all together.

Hermes allows you to quickly build a cluster of publishers which can support arbitrary numbers
of subscribers via single address.

Motivation
==========
Hermes is the base for our Crypto trading system, and allows us to set up new node clusters in a
convenient and maintainable way, without our contributors having to worry too much about the inner
workings of ZMQ.

We liked it, so we decided to publish it!


Usage
=====

install via ``pip install hermes-zmq`` and import with ``import hermes``.