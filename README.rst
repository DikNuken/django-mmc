Django-mmc
==========

What's that
-----------
App for monitoring management commands on Django.


Quick installation
------------------
1. Using pip:

.. code-block:: bash

    $  sudo pip install django-mmc


2. Add ``mmc`` application to ``INSTALLED_APPS`` in your settings file

3. Inject management classes before apps will be loaded

.. code-block:: python

    from mmc.mixins import inject_management

    inject_management()


4. Sync database (``./manage.py syncdb``)


Screenshots
-----------
.. image:: /screenshot.jpg


Compatibility:
-------------
* Python: 2.6, 2.7
* Django: 1.3.x, 1.4.x, 1.5.x, 1.6.x
