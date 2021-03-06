Important
=========

This app has been discontinued and is no longer maintained.

cmsplugin-blog Authors
======================

An extension for `cmsplugin-blog <https://github.com/fivethreeo/cmsplugin-blog/>`_
which allows to add multiple authors to a blog entry. This is based on 
`django-people <https://github.com/bitmazk/django-people>`_.

Installation
------------

You need to install the following prerequisites in order to use this app:

* Django
* django-cms
* cmsplugin-blog
* django-people

If you want to install the latest stable release from PyPi::

    $ pip install cmsplugin-blog-authors

If you feel adventurous and want to install the latest commit from GitHub::

    $ pip install -e git://github.com/bitmazk/cmsplugin-blog-authors.git#egg=cmsplugin_blog_authors

Add ``cmsplugin_blog_authors`` to your ``INSTALLED_APPS``::

    INSTALLED_APPS = (
        ...,
        'cmsplugin_blog_authors',
    )


Usage
-----

Just write a blog Entry and you will see a new inline for authors in the
Entry admin.


Roadmap
-------

Check the issue tracker on github for milestones and features to come.
