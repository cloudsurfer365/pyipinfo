========
pyipinfo
========

.. image:: https://travis-ci.org/juanpabloaj/pyipinfo.svg?branch=master
    :target: https://travis-ci.org/juanpabloaj/pyipinfo

Use `ipinfo.io <https://ipinfo.io/>`_ from the command line.

Usage
=====

Information of local ip

.. code-block:: bash

    pyipinfo

Information of one ip

.. code-block:: bash

    echo "ip" | pyipinfo

Information of each ip in a file or output pipe

.. code-block:: bash

    cat requests.log | pyipinfo

Installation
============

.. code-block:: bash

    pip install pyipinfo
