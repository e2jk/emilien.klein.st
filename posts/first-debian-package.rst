.. description: Submittted my first Debian package
.. tags: debian,nautilus-image-manipulator,linux
.. date: 2011-02-09 07:30:00 GMT
.. title: Submittted my first Debian package
.. slug: first-debian-package
.. type: text

Yesterday I submitted my first Debian package. The packaged software is `Nautilus Image Manipulator <https://launchpad.net/nautilus-image-manipulator>`_, a program I started writing as a Christmas present for my father 3 months ago. It seemed as a good fit for learning how to do Debian packaging.

.. TEASER_END

The package has been submitted to http://mentors.debian.net/ and can be found `there <http://mentors.debian.net/cgi-bin/sponsor-pkglist?action=details;package=nautilus-image-manipulator>`_. I hope I haven't messed it up too much ;)

EDIT: Here are some links that were pretty useful to me to understand the packaging process:

Since it's a Python program, I first created the Distutils package following the `Distributing Python Modules <http://docs.python.org/distutils/>`_.

I then read the `Debian New Maintainers' Guide <http://www.debian.org/doc/manuals/maint-guide/index.en.html>`_ from A to Z. This document is really full of information, it explains each step very thoroughly. It can seem as if it is a long and complicated process, but that's because the guide goes really into each detail you need to know.

Also pretty useful to learn about the Debian packaging process from another angle is the `Ubuntu PackagingGuide <https://wiki.ubuntu.com/PackagingGuide/Basic>`_.

I have started compiling the different steps into a document that's in my project's version control repository, so that I can build packages in the future without having to read all this information again. It is a work in progress (for example the part about rebuilding a package for a new version using the older package's ``./debian`` files is not yet written), but it will definitely help me in the future. `Here <http://bazaar.launchpad.net/~emilien-klein/nautilus-image-manipulator/trunk/view/head:/README.PACKAGING>`_ is a link to the latest version of that file!

Hope this can be useful to others that want to get involved with Debian packaging!

