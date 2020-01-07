.. image:: https://travis-ci.org/ome/omero-weberror.svg?branch=master
    :target: https://travis-ci.org/ome/omero-weberror

.. image:: https://badge.fury.io/py/omero-weberror.svg
    :target: https://badge.fury.io/py/omero-weberror


OMERO.weberror
==============
OMERO.web app that helps testing errors, notification logic etc.

Requirements
============

* OMERO.web 5.6 or newer.

Installing from PyPI
====================

This section assumes that an OMERO.web is already installed.

Install the app using `pip <https://pip.pypa.io/en/stable/>`_:

::

    $ pip install omero-weberror

Add weberror custom app to your installed web apps:

::

    $ omero config append omero.web.apps '"omero_weberror"'

Now restart OMERO.web as normal.


License
-------

OMERO.weberror is released under the AGPL.

Copyright
---------

2016-2020, The Open Microscopy Environment
