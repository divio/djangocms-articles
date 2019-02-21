===================
django CMS Articles
===================

|pypi| |build| |coverage|

**django CMS Articles** adds article function to `django CMS <http://django-cms.org>`_.
It is aimed to display common article information like news, blog entries, events
and further types. It is extendable to add your own custom structure.

This addon is compatible with `Divio Cloud <http://divio.com>`_ and is also available on the
`django CMS Marketplace <https://marketplace.django-cms.org/en/addons/browse/djangocms-articles/>`_
for easy installation.


Contributing
============

This is a an open-source project. We'll be delighted to receive your
feedback in the form of issues and pull requests. Before submitting your
pull request, please review our `contribution guidelines
<http://docs.django-cms.org/en/latest/contributing/index.html>`_.

We're grateful to all contributors who have helped create and maintain this package.
Contributors are listed at the `contributors <https://github.com/divio/djangocms-articles/graphs/contributors>`_
section.

One of the easiest contributions you can make is helping to translate this addon on
`Transifex <https://www.transifex.com/projects/p/djangocms-articles/>`_.


Documentation
=============

See ``REQUIREMENTS`` in the `setup.py <https://github.com/divio/djangocms-articles/blob/master/setup.py>`_
file for additional dependencies:

|python| |django| |djangocms|

* Django Filer 1.2.4 or higher

Make sure `django Filer <http://django-filer.readthedocs.io/en/latest/installation.html>`_
is installed and configured appropriately.


Installation
------------

For a manual install:

* run ``pip install djangocms-articles``
* add ``djangocms_articles`` to your ``INSTALLED_APPS``
* run ``python manage.py migrate djangocms_articles``


Configuration
-------------

TBA


Running Tests
-------------

You can run tests by executing::

    virtualenv env
    source env/bin/activate
    pip install -r tests/requirements.txt
    python setup.py test


.. |pypi| image:: https://badge.fury.io/py/djangocms-articles.svg
    :target: http://badge.fury.io/py/djangocms-articles
.. |build| image:: https://travis-ci.org/divio/djangocms-articles.svg?branch=master
    :target: https://travis-ci.org/divio/djangocms-articles
.. |coverage| image:: https://codecov.io/gh/divio/djangocms-articles/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/divio/djangocms-articles

.. |python| image:: https://img.shields.io/badge/python-2.7%20%7C%203.4+-blue.svg
    :target: https://pypi.org/project/djangocms-articles/
.. |django| image:: https://img.shields.io/badge/django-1.11%20%7C%202.0%20%7C%202.1-blue.svg
    :target: https://www.djangoproject.com/
.. |djangocms| image:: https://img.shields.io/badge/django%20CMS-3.4%2B-blue.svg
    :target: https://www.django-cms.org/
