[![Build Status](https://travis-ci.org/whoosh-community/whoosh.svg?branch=master)](https://travis-ci.org/whoosh-community/whoosh)

About Whoosh
============

Whoosh is a fast, featureful full-text indexing and searching library
implemented in pure Python. Programmers can use it to easily add search
functionality to their applications and websites. Every part of how Whoosh
works can be extended or replaced to meet your needs exactly.

Some of Whoosh's features include:

* Pythonic API.
* Pure-Python. No compilation or binary packages needed, no mysterious crashes.
* Fielded indexing and search.
* Fast indexing and retrieval -- faster than any other pure-Python, scoring,
  full-text search solution I know of.
* Pluggable scoring algorithm (including BM25F), text analysis, storage,
  posting format, etc.
* Powerful query language.
* Pure Python spell-checker (as far as I know, the only one). 

Whoosh might be useful in the following circumstances:

* Anywhere a pure-Python solution is desirable to avoid having to build/compile
  native libraries (or force users to build/compile them).
* As a research platform (at least for programmers that find Python easier to
  read and work with than Java ;)
* When an easy-to-use Pythonic interface is more important to you than raw
  speed. 

Whoosh was created by Matt Chaput and is maintained currently by the Sygil-Dev Organization. It was originally created for use in the online help system of Side Effects Software's 3D animation software Houdini. Side Effects Software Inc. graciously agreed to open-source the code.

This software is licensed under the terms of the simplified BSD (A.K.A. "two
clause" or "FreeBSD") license. See LICENSE.txt for information.

Installing Whoosh
=================

If you have ``setuptools`` or ``pip`` installed, you can use ``easy_install``
or ``pip`` to download and install Whoosh automatically::

    # install the old version from Pypi
    $ easy_install Whoosh
    
    or
    
    $ pip install Whoosh
    
    
    # Install the development version from Github.
    $ pip install git+https://github.com/Sygil-Dev/whoosh.git

Learning more
=============

* Read the online documentation at https://docs.red-dove.com/whoosh/ (Search DOES work).

* Read the old online documentation at https://whoosh.readthedocs.org/en/latest/ (Search DOES NOT work).

* File bug reports and issues at https://github.com/Sygil-Dev/whoosh/issues

Getting the source.
==================

You can check out the latest version of the source code on GitHub using git:

    $ git clone https://github.com/Sygil-Dev/whoosh.git
