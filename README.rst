Nikola, a Static Site and Blog Generator
========================================

In goes content, out comes a website, ready to deploy.

.. image:: https://travis-ci.org/getnikola/nikola.png
   :target: https://travis-ci.org/getnikola/nikola

Why Static Websites?
--------------------

Static websites are safer, use fewer resources, and avoid vendor and platform lock-in.
You can read more about this in the `Nikola Handbook`_


What Can Nikola Do?
-------------------

It has many features, but here are some of the nicer ones:

* `Blogs, with tags, feeds, archives, comments, etc.`__
* `Themable`_
* Fast builds, thanks to `doit`_
* Flexible, extensible via plugins
* Small codebase (programmers can understand all of Nikola core in a day)
* `reStructuredText`_ or Markdown as input language (also Wiki, BBCode, Textile, and HTML)
* Easy `image galleries`_ (just drop files in a folder!)
* Syntax highlighting for almost any programming language or markup
* Multilingual sites, `translated to 13 languages.`__
* Doesn't reinvent wheels, leverages existing tools.
* Python 2 and 3 compatible.

.. _Nikola Handbook: http://getnikola.com/handbook.html#why-static
__ http://getnikola.com/some-sites-using-nikola.html
.. _Themable: http://themes.getnikola.com
.. _doit: http://python-doit.sf.net
.. _reStructuredText: http://getnikola.com/quickstart.html
.. _image galleries: http://getnikola.com/galleries/demo/
__ https://www.transifex.com/projects/p/nikola/

Installation Instructions
-------------------------

Assuming you have pip installed::

    git clone git://github.com/getnikola/nikola.git
    cd nikola
    pip install .

Optionally (for markdown and lots of other features)::

    pip install -r requirements.txt

For even more stuff, like tests and very optional features::

    pip install -r requirements-full.txt


.. note:: For Python 3.0 through 3.2, you need to replace ``Jinja2==2.7``
          with ``Jinja2==2.6`` or installation will fail.  (note that
          upgrading Python is a better solution, although it is not always
          possible)

          You may also have problems with the Jinja themes included.  In this
          case, you should use Mako themes instead.

For more information, see http://getnikola.com/
