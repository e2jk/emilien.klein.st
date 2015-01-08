.. description: Install Citrix ICA Client on Ubuntu 11.04
.. tags: citrix,ubuntu,linux
.. date: 2011-06-27 17:00:06 GMT
.. title: Install Citrix ICA Client on Ubuntu 11.04
.. slug: install-citrix-ica-client-on-ubuntu-11.04
.. type: text

These are the steps I used to install the Citrix ICA Client (also called "Citrix Receiver for Linux") on my freshly installed Ubuntu 11.04 box.

.. TEASER_END

* First of all, install the following package: ``sudo aptitude install libmotif4``
* Download the latest ``.tar.gz`` from `Citrix's website <http://www.citrix.com/English/ss/downloads/details.asp?downloadId=3323&productId=186>`_.
* Unpack the archive and run the installer: ``sudo ./setupwfc``

  Just use the defaults when responding to the prompts.
* Try to run the executable from the command line: ``/usr/lib/ICAClient``

  There should be no error (because we installed libmotif in the first step)

When I tried to open a secured .ica files (behind https) I got this error:

  "SSL Error 61: You have not chosen to trust "YYYY", the issuer of the server's security certificate."


In order to fix that, execute the following command: ``cp /usr/share/ca-certificates/mozilla/* /usr/lib/ICAClient/keystore/cacerts/``

Resources:

* https://help.ubuntu.com/community/CitrixICAClientHowTo
* http://blog.torh.net/2008/02/29/problems-with-citrix-client-on-linux/

