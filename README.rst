.. image:: https://travis-ci.org/openmicroscopy/omero-weberror.svg?branch=master
    :target: https://travis-ci.org/openmicroscopy/omero-weberror

.. image:: https://badge.fury.io/py/omero-weberror.svg
    :target: https://badge.fury.io/py/omero-weberror


OMERO.weberror
==============
OMERO.web app that helps testing errors, notification logic etc.

Requirements
============

* OMERO 5.2.6 or newer.

Installation
============

This section assumes that an OMERO.server is already installed.

Install the app:

::

    $ pip install omero-weberror

Add weberror custom app to your installed web apps:

::

    $ bin/omero config append omero.web.apps '"omero_weberror"'

Now restart OMERO.web as normal.

**Warning**:

OMERO.weberror version 0.2.x requires OMERO.web **5.2.6 or newer**.
This is due to Django Framework compatibility and to a required package reorganization in OMERO.weberror in version 0.2.0 so the application can be distributed using Python Package Manager PyPi.


License
-------

OMERO.weberror is released under the AGPL.

Copyright
---------

2016, The Open Microscopy Environment
