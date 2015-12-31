.. title: Moving to HTTPS with Let's Encrypt
.. slug: moving-to-https-with-lets-encrypt
.. date: 2015-12-31 02:30:10 UTC+01:00
.. tags: https,let's encrypt
.. category:
.. link:
.. description:
.. type: text

I've moved most of my websites over to HTTPS today using `Let's Encrypt <https://letsencrypt.org/>`_. The process took me a bit more time than I had hoped, since I encountered a `segfault bug <https://github.com/letsencrypt/letsencrypt/issues/1976#issuecomment-168001259>`_ while installing the software directly from the Git repo, but after installing the Debian `letsencrypt` package all worked fine.

I've followed the instructions given by `John Maguire <https://johnmaguire.me/2015/12/configuring-nginx-lets-encrypt-automatic-renewal/>`_, and I must say I'm really pleased to be able to ditch the self-signed certificate I had created for https://links.klein.st and provide my other sites behind HTTPS. Thanks a lot, `Let's Encrypt <https://letsencrypt.org/>`_!

Now most of my web properties get an A on `SSL Labs <https://www.ssllabs.com/ssltest/analyze.html?d=emilien.klein.st>`_!
