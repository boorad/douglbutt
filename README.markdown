FREDERICK DOUGLBUTT
===================

This is an ultra-simple (sorta) IRC bot that uses irclib. A little messy,
but I'm ok with it. You can write new plugins pretty simply.

REQUIREMENTS
============

  * python-irclib

Twitter support requires:

  * python-oauth2
  * python-simplejson

Tumblr support requires:

  * [pymblr](http://github.com/lysol/pymblr "pymblr")

  * [marko](http://github.com/rupa/marko "marko")

INSTALLATION AND USE
====================
    git clone git@github.com:lysol/douglbutt.git
    cd douglbutt
    python setup.py install
    cp src/douglbutt.conf-dist ~/douglbutt.conf
    vim ~/douglbutt.conf
    python -m douglbutt.__init__ ~/douglbutt.conf
