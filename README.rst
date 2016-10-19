.. image:: https://travis-ci.org/openmicroscopy/omero-weberror.svg?branch=master
    :target: https://travis-ci.org/openmicroscopy/omero-weberror

.. image:: https://badge.fury.io/py/omero-weberror.svg
    :target: https://badge.fury.io/py/omero-weberror


OMERO.weberror
==============
OMERO.web app that helps testing errors.

Requirements
============

* OMERO 5.2.6 or newer.

Installation
============

Install OMERO.web.

This app installs into the OMERO.web framework.

::

    $ pip install omero-weberror

Add weberror custom app to your installed web apps:

::

    $ bin/omero config append omero.web.apps '"omero_weberror"'

Now restart OMERO.web as normal.

**Warning**:

OMERO.weberror version 0.2.x or newer is meant to be installed into OMERO.web **5.2.6 or newer**. This is due to Django Framework compatibility and a package re-organization required to distribute the application using Python Package Manager PyPi.


License
-------

OMERO.weberror is released under the AGPL.

Copyright
---------

2016, The Open Microscopy Environment
