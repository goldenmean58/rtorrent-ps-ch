AUR Install From Source
=======================

.. contents:: **Contents**


Introduction
------------

Although the build script can create binaries and packages for Arch Linux as well, it can be also installed through the “Arch User Repository” (AUR) PKGBUILDs maintained by @QDesjardin. These use a standard Arch build process, but include all the patches.

There is one package for `libtorrent-ps-ch <https://aur.archlinux.org/packages/libtorrent-ps-ch/>`_, and one for `rtorrent-ps-ch <https://aur.archlinux.org/packages/rtorrent-ps-ch/>`_, and both take their dependencies from the normal OS packages.


Installing build dependencies
-----------------------------

Before building binaries or packages, install these packages on top of the ``base`` and ``base-devel`` groups (list is user-provided, report any problems to @QDesjardin):

.. code-block:: shell

   pacman -S lsb-release subversion git time lsof tmux wget python2-setuptools \
       python2-virtualenv python2 python2-cffi cppunit libxml2 libxslt


Notes
-----

The following features are not included in this way:

-  `CPU optimized build <https://github.com/chros73/rtorrent-ps/issues/109>`_
-  `relative rpath linking <https://github.com/chros73/rtorrent-ps/issues/93>`_
-  `git version support <https://github.com/chros73/rtorrent-ps/issues/78>`_
-  using specific version of external libraries (libcurl, c-ares, libxmlrpc)

