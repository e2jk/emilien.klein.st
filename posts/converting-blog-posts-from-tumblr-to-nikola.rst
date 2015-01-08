.. title: Converting blog posts from Tumblr to Nikola
.. slug: converting-from-tumblr-to-nikola
.. date: 2015-01-08 01:44:15 UTC-05:00
.. tags: tumblr,nikola,edison
.. link: 
.. description: 
.. type: text

When relaunching my personal site, I wanted to `import <https://github.com/e2jk/emilien.klein.st/issues/1>`_ the few posts that I had made on http://e2jk.tumblr.com/. As all programmer/computer geek will tell you, we are lazy people: copy/pasting content from the web browser to text files was just not an option!

I found a project called `Edison <https://github.com/DoctorMalboro/Edison>`_ that does the bulk of what I was looking for: create one ``.rst`` files for each Tumblr blog post. The project had a couple of issues with encoding and non-Youtube videos, so after a bit of `hacking <https://github.com/e2jk/Edison/commits/master>`_ I got the project working for my use case (note: you will need to `generate <https://www.tumblr.com/oauth/apps>`_ an API key from Tumblr).

A bit of manual processing was needed (namely to get the hyperlinks and lists working), but it was overall a very useful project.

