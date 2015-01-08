emilien.klein.st
================

`Emilien Klein's personal website <http://emilien.klein.st/>`_, built using `Nikola <http://getnikola.com/>`_.

Building, testing and deploying
===============================
::

    nikola build
    nikola serve

See the site: http://127.0.0.1:8000

Deploying: Just call ``nikola deploy``. That will ``rsync`` the ``output`` folder, and keep a backup in the ``../emilien.klein.st-backup`` folder using ``rdiff-backup``.

Useful links
============

* `The Nikola Handbook <http://getnikola.com/handbook.html>`_
* `reStructuredText <http://getnikola.com/quickstart.html>`_ [`Cheatsheet <https://github.com/ralsina/rst-cheatsheet/blob/dfaf3e283ee5df9d4c4b50ff9be2fa7db93c0427/rst-cheatsheet.pdf?raw=true>`_]
