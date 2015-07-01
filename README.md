OMERO.weberror
============================
Django application that helps testing errors

Requirements
============

* OMERO 5.1.0 or later

Installation
============

Clone

    $ git clone git://github.com/openmicroscopy/weberror.git weberror

or download

    $ wget -O master.zip https://github.com/openmicroscopy/weberror/zipball/master
    $ unzip master.zip
    $ mv openmicroscopy-weberror-* weberror

Add weberror to PYTHONPATH:

    $ export PYTHONPATH=/path/to/weberror:$PYTHONPATH

Add weberror custom app to your installed web apps:

    $ bin/omero config append omero.web.apps '"weberror"'

NB: note that double quotes are wrapped by single quotes. Windows users will need to do

    $ bin\omero config append omero.web.apps "\"weberror\""

Now start up OMERO.web as normal.
