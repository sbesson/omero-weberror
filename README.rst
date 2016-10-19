.. image:: https://travis-ci.org/openmicroscopy/omero-weberror.svg?branch=master
    :target: https://travis-ci.org/openmicroscopy/omero-weberror

.. image:: https://badge.fury.io/py/omero-weberror.svg
    :target: https://badge.fury.io/py/omero-weberror


OMERO.weberror
==============
OMERO.web app that helps testing errors.

Requirements
============

* OMERO 5.1.0 or later.

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

if OMERO.weberror is installed with OMERO version prior to **5.2.6**
the url will be https://your-web-server/omero_weberror instead of https://your-web-server/weberror as previously. This is due to a package re-organization required to distribute the application using a package manager.
If installed with OMERO **5.2.6 and older**, the url will be back to https://your-web-server/webtest.


License
-------

OMERO.weberror is released under the AGPL.

Copyright
---------

2016, The Open Microscopy Environment
