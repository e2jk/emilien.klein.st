.. title: Using the data-hook attribute for JavaScript event binding
.. slug: using-data-hook-attribute
.. date: 2015-02-06 13:28:13 UTC+01:00
.. tags: webdev,spa,ampersand.js,javascript
.. category:
.. link:
.. description:
.. type: text

While reading through the Ampersand.js documentation, I came upon `this page <http://ampersandjs.com/learn/data-hook-attribute>`_ which just clicked with me.

The problem is that when different people (e.g. a developer and a designer) collaborate on a CSS + JavaScript application, if one of them changes the selector (``id`` or ``class``) the other person's side of the application may break (missing style, or broken js).

By using the "data-hook" attribute instead to providing selectors to JavaScript code, an HTML/CSS dev can go change whatever else they want in the template without fear of breaking the JavaScript.

Brilliant!
