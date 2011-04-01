puppetlast
==========

.. contents::

Overview
--------

This is a simple python script that shows the last connect time of puppet
nodes. It currently displays them in red / green depending on if they've
connected in the past 30 minutes.

Warning: This code needs a lot of work, but it is in working condition.


Installing
----------

The simplest way to install this would be to go to your puppetmaster, and run
this::

   $ wget -O /usr/bin/puppetlast https://github.com/gregarmer/puppetlast/raw/master/puppetlast
   $ chmod 755 /usr/bin/puppetlast


Output
------

The output looks something like this:

.. image:: https://github.com/gregarmer/puppetlast/raw/master/misc/screenshot.png

