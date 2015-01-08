.. title: Compiling FlightGear 2.6.0 for Ubuntu Linux 11.10 (Oneiric Ocelot)
.. slug: flightgear-2.6.0-ubuntu-11.10
.. date: 2012-03-08 13:05:04 GMT
.. tags: flightgear,ubuntu,linux
.. link: 
.. description: 
.. type: text

**Note:** This post was not published originally on my Tumblr blog, but stayed for almost 3 years there as a draft. The information is most likely not accurate anymore.

These instructions will let you use the recently released `FlightGear 2.6.0 <http://www.flightgear.org/>`_ on Ubuntu Linux 11.10 by compiling it from source. I've based my instructions on `those <http://www.andrewferrier.com/blog/2011/08/17/compiling-flightgear-2-4-0-for-ubuntu-10-04/>`_ linked from the `official site <http://www.flightgear.org/download/main-program/>`_ and updated them for the new 2.6.0 release (apparenlty they started using CMake instead of just ``./configure``)

.. TEASER_END

Install the following packages::

    sudo apt-get install libboost-graph-dev libopenal-dev libalut-dev libopenscenegraph-dev libjpeg62-dev libplib-dev zlib1g-dev libxmu-dev

* Get the following files
    - `SimGear 2.6.0 source code <http://mirrors.ibiblio.org/pub/mirrors/simgear/ftp/Source/simgear-2.6.0.tar.bz2>`_
    - `FlightGear 2.6.0 source code <ftp://flightgear.wo0t.de/Source/flightgear-2.6.0.tar.bz2>`_
    - `Base package <http://mirrors.ibiblio.org/pub/mirrors/flightgear/ftp/Shared/FlightGear-data-2.6.0.tar.bz2>`_ (tip: you can start compiling while the base package is still downloading)

* Decompress the 3 downloaded tarballs.

* Compile

  Make 2 new directories to compile SimGear and FlightGear in::

    mkdir sg; mkdir fg

  Compile SimGear::

    cd sg; cmake ../simgear-2.6.0; make; sudo checkinstall

  Checkinstall will ask you a few questions. Make sure to set the Name and Version appropriately. It might also complain about files located inside the ``/home directory``: I chose to exclude them from the package.

  Compile FlightGear::

    cd ../fg; cmake ../flightgear-2.6.0; make; sudo checkinstall
    sudo mkdir /usr/local/lib/FlightGear
    sudo mv data/* /usr/local/lib/FlightGear

And that's it! Run ``fgfs`` to launch Flightgear (there’s no GUI so you’ll have to become familiar with the command-line switches).

Based on http://www.andrewferrier.com/blog/2011/08/17/compiling-flightgear-2-4-0-for-ubuntu-10-04/

