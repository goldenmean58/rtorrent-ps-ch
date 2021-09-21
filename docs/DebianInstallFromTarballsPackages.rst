Debian Install From Tarballs, Packages
======================================

.. contents:: **Contents**


Important!
------------

Due to shutdown of Bintray, none of the built packages are available anymore.


Introduction
------------

There are tarballs and packages available for Debian and Ubuntu LTS distributions that contain pre-compiled binaries.
You can download and install such a tarball/package from `Bintray <https://bintray.com/chros73/rtorrent-ps-ch/rtorrent-ps-ch>`_ — assuming one is available for your platform.

Notes: `Installing from Source <DebianInstallFromSourceTheEasyWay.rst>`_ is still the preferred way for the following reasons:

- tarballs and packages are **NOT** CPU optimized builds (for obvious reasons)
- tarballs and packages aren't freqently updated


Installing tarball, package dependencies
----------------------------------------

First, you need to install a few **required** packages if they are not available on your system — **and no, this is not optional in any way**.
These steps must be performed by the ``root`` user (i.e. in a root shell, or by writing ``sudo`` before the actual command):


Common packages amongst distros
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You have to install the following packages:

.. code-block:: shell

   apt-get update
   apt-get install libc6 libgcc1 libstdc++6 zlib1g


Distro specific packages
^^^^^^^^^^^^^^^^^^^^^^^^

You also have to install the following distro specific packages (Debian 10 means ``testing`` currently):

- Debian  7: ``libncursesw5 libtinfo5 libssl1.0.0 libcppunit-1.12-1``
- Debian  8: ``libncursesw5 libtinfo5 libssl1.0.0 libcppunit-1.13-0``
- Debian  9: ``libncursesw5 libtinfo5 libssl1.1 libcppunit-1.13-0v5``
- Debian 10: ``libncursesw6 libtinfo6 libssl1.1 libcppunit-1.14-0``
- Ubuntu 14: ``libncursesw5 libtinfo5 libssl1.0.0``
- Ubuntu 16: ``libncursesw5 libtinfo5 libssl1.0.0``
- Ubuntu 18: ``libncursesw5 libtinfo5 libssl1.1``


Installing ``rTorrent-PS-CH`` packages
----------------------------------------

The packages install the ``rTorrent-PS-CH`` binary including some libraries into ``/opt/rtorrent-ps-ch*`` directory
and create symlinks to it in ``/usr/local/bin/``, ``/usr/local/lib/`` and ``/opt/`` directories. Example using Ubuntu 14.04:

.. code-block:: shell

   version="1.8.3-0.9.8-ubuntu-trusty_amd64"
   curl -Lko "/tmp/rtorrent-ps-ch_$version.deb" "https://bintray.com/chros73/rtorrent-ps-ch/download_file?file_path=rtorrent-ps-ch_$version.deb"
   dpkg -i "/tmp/rtorrent-ps-ch_$version.deb"


Extracting ``rTorrent-PS-CH`` tarballs
--------------------------------------

Note: tarballs also need the above mentioned package dependencies!

Tarballs can be extracted anywhere on the filesystem, e.g. into ``~/lib`` directory as a regular user using Ubuntu 14.04 (symlinks manually need to be created if necessary):

.. code-block:: shell

   version="1.8.3-0.9.8-ubuntu-trusty_amd64"
   curl -Lko "/tmp/rtorrent-ps-ch_$version.tar.gz" "https://bintray.com/chros73/rtorrent-ps-ch/download_file?file_path=rtorrent-ps-ch_$version.tar.gz"
   mkdir -p ~/lib
   tar -xzvf "/tmp/rtorrent-ps-ch_$version.tar.gz" -C ~/lib/


