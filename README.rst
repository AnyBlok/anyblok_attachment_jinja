.. This file is a part of the AnyBlok / Attachment / Jinja project
..
..    Copyright (C) 2018 Jean-Sebastien SUZANNE <jssuzanne@anybox.fr>
..
.. This Source Code Form is subject to the terms of the Mozilla Public License,
.. v. 2.0. If a copy of the MPL was not distributed with this file,You can
.. obtain one at http://mozilla.org/MPL/2.0/.

.. image:: https://img.shields.io/pypi/v/anyblok_attachment_jinja.svg
   :target: https://pypi.python.org/pypi/anyblok_attachment_jinja/
   :alt: Version status

.. image:: https://travis-ci.org/AnyBlok/anyblok_attachment_jinja.svg?branch=master
    :target: https://travis-ci.org/AnyBlok/anyblok_attachment_jinja
    :alt: Build status

.. image:: https://coveralls.io/repos/github/AnyBlok/anyblok_attachment_jinja/badge.svg?branch=master
    :target: https://coveralls.io/github/AnyBlok/anyblok_attachment_jinja?branch=master
    :alt: Coverage

.. image:: https://readthedocs.org/projects/anyblok-attachment-jinja/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: https://doc.anyblok-attachment-jinja.anyblok.org/?badge=latest

.. image:: https://badges.gitter.im/AnyBlok/community.svg
    :alt: gitter
    :target: https://gitter.im/AnyBlok/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge

.. image:: https://img.shields.io/pypi/pyversions/anyblok_attachment_jinja.svg?longCache=True
    :alt: Python versions


AnyBlok attachment jinja
========================

Improve `AnyBlok <http://doc.anyblok.org>`_ and `Attachment <https://doc.anyblok-attachment.anyblok.org>`_
system.

+------------------+----------------+---------------------------------------------------------+
| Blok             | Dependancies   | Description                                             |
+==================+================+=========================================================+
| **report-jinja** | **attachment** | Use the `jinja2 <http://jinja.pocoo.org/docs/>`_        |
|                  | **report**     | templating engine to create the document.               |
|                  | **wkhtml2pdf** |                                                         |
+------------------+----------------+---------------------------------------------------------+

AnyBlok / Attachment jinja is released under the terms of the `Mozilla Public License`.

See the `latest documentation <http://doc.anyblok-attachment-jinja.anyblok.org/>`_

Running Tests
-------------

To run framework tests with ``pytest``::

    pip install pytest
    ANYBLOK_DATABASE_DRIVER=postgresql ANYBLOK_DATABASE_NAME=test_anyblok anyblok_createdb --install-bloks report-jinja
    ANYBLOK_DATABASE_DRIVER=postgresql ANYBLOK_DATABASE_NAME=test_anyblok py.test anyblok_attachment_jinja/bloks

AnyBlok is tested continuously using `Travis CI
<https://travis-ci.org/AnyBlok/anyblok_mixins>`_

Author
------

Jean-Sébastien Suzanne

Bugs
----

Bugs and features enhancements to AnyBlok should be reported on the `Issue
tracker <https://github.com/AnyBlok/anyblok_attachment_jinja/issues>`_.
