.. description: Bug: your site does not accept some valid email addresses
.. tags: email
.. date: 2011-02-11 17:27:00 GMT
.. title: Bug: your site does not accept some valid email addresses
.. slug: character-plus-is-valid-in-email-addresses
.. type: text

**Summary:** *The character "+" is valid in email addresses!*

This is the content of an email message I sent to United (the airline) about 2 years ago, since I couldn't create an account using a perfectly valid email address containing a + in it. This has been happening with other sites, so I'm posting it here so that I don't need to copy/paste it all the time. And if others want to link to it, feel free!

Edit 11/10/2011: Look at this `good link <http://haacked.com/archive/2007/08/21/i-knew-how-to-validate-an-email-address-until-i.aspx>`_ resuming the issue around email regexes, with links to the RFC and some nice examples of "weird" email addresses.

================================================================

PLEASE FORWARD TO YOUR TECHNICAL SERVICES

Hi,

I wanted to point you to an error in your forms all over your site. It
is not possible to use email addresses that contain the symbol "+",
such as toto+united@gmail.com

Please forward this message to your web development team, as what
follows is a technical subject.

A plus is a totally valid symbol in an email address, and is used by
Gmail to provide email address alias:
http://mail.google.com/support/bin/answer.py?hl=en&amp;answer=12096

Please update your regular expressions so that it accepts email
addresses that contain the symbol "+".
This should be done (at least) in your regex on
http://www.united.com/ual/asset/err_myprof.js line 937:
var emailRe = /^[a-zA-Z0-9._-]+@([a-zA-Z0-9.-]+.)+[a-zA-Z0-9.-]{2,4}$/.test(chkVal.value);

include a plus in "[a-zA-Z0-9._-]"

It might not seem very important to you, but once you get the habit of
using aliases to filter your mails to different labels (I have just
created a special "United" label to store your emails), having sites
that say "your address is not valid" when it is is really frustrating.

Let me say it once again: "a plus sign in an email address is valid,
so don't say it's not!"
