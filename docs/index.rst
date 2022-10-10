.. CASSIS Autolink documentation master file, created by
   sphinx-quickstart on Mon Oct 10 18:29:49 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to CASSIS Autolink's documentation!
===========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Add HTML links to URLs in text
------------------------------

The `auto_link()` function automatically adds HTML links to URLs that appear in text.

For example, given the following text:

.. code-block:: python

   text = "This is a link to https://indieweb.org"

This library would return:

.. code-block:: python

   'This is a link to <a class="auto-link" href="https://indieweb.org">https://indieweb.org</a>'

.. autofunction:: cassis.auto_link