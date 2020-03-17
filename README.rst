Introduction
============

Provides alternative to 'bin/plone debug'.

Install
-------

To install, do this::

    $ wget http://github.com/aclark4life/Plone-Debug-Assistant/raw/master/debug.py
    $ bin/plone run debug.py

Run
---

You should get an interactive prompt where you can do things like this::

    >>> site.invokeFactory('Folder','foo')
    >>> commit()


Caveats
-------

Currently ``debug.py`` assumes your Plone site object is called "Plone".
