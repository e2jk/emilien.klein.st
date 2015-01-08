.. title: Nginx and PHP-FPM: solving blank page (zero-size response)
.. slug: blank-page-nginx-phpfpm
.. date: 2015-01-07 20:12:47 UTC-05:00
.. tags: nginx,php-fpm,php5-fpm,debian,webserver
.. link: 
.. description: Solution to an issue I faced today, where my Shaarli instance stopped working after installing updates on my web server.
.. type: text

I had the unpleasant suprise today to realize my `Shaarli <https://links.klein.st/>`_ instance (a simple PHP application) stopped working after installing updates on my Debian web server. I was getting a 200 valid response from the web server, but with a zero-byte response length.

.. TEASER_END: Read on if you're interested in fixing it.

When installing the available updates on my Debian testing server, both the nginx and php5-fpm packages were updated (to versions 1.6.2-5 and 5.6.4+dfsg-1 respectively). After spending quite some time trying to figure out if this was due to a change in Nginx or PHP-FPM, reviewing the different log and config files, I finally found the `following Nginx bug report <http://trac.nginx.org/nginx/ticket/630>`_ which itself linked to an `Ubuntu bug report <https://bugs.launchpad.net/nginx/+bug/1366651>`_ which contained the solution to this issue::

    However after upgrading to 1.6.1, you need to update the include line to this:

        include fastcgi.conf;

Adding this line in the appropriate nginx config file in ``/etc/nginx/sites-available`` did the trick. A quick ``sudo /etc/init.d/nginx restart`` later and Shaarli was up and running again.

