OMERO.weberror
============================
Django application that helps testing errors

Requirements
============

* OMERO 5.1.0 or later

Installation
============

    $ pip install git+git://github.com/openmicroscopy/weberror.git

Add weberror custom app to your installed web apps:

    $ bin/omero config append omero.web.apps '"weberror"'

Now start up OMERO.web as normal.
