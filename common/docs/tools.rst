Requirements
------------

This section details the tools needed by this packaging framework.

.. note::

    Each package requires its own build dependencies (gcc, cmake, etc.).
    Either install these dependencies or use chroot builds (`make rpm_chroot` or `make deb_chroot`).

Debian/Ubuntu
=============

.. sourcecode:: bash

    # For DEB packaging
    $ apt-get install make debhelper reprepro cowbuilder wget


RHEL/CentOS/Fedora
==================

.. sourcecode:: bash

    $ dnf install rpm-sign expect rpm-build createrepo make mock wget