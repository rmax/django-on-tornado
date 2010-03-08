Requirements
============
* Django_
* Tornado_

.. _Django: http://www.djangoproject.com/
.. _Tornado: http://www.tornadoweb.org/

Instructions
============

 1. ``cd myproject``
 2. ``python manage.py syncdb``
 2. ``python manage.py runtornado --reload --admin``
 3. Go to: http://localhost:8000/admin/

ToDo
====

* Integrate Tornado's handlers

Acknowledgements
================

Idea and code snippets borrowed from http://geekscrap.com/2010/02/integrate-tornado-in-django/

