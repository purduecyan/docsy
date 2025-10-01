Getting Started
===============

.. seealso::

   Part of the following information is reproduced from *Read the Docs* `Getting Started with Sphinx`_

   .. _Getting Started with Sphinx: https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html

.. meta::
   :description lang=en: Get started writing technical documentation with Sphinx.

Sphinx is a powerful documentation generator that
has many great features for writing technical documentation including:

* Generate web pages, printable PDFs, documents for e-readers (ePub),
  and more all from the same sources
* You can use reStructuredText or Markdown to write documentation
* An extensive system of cross-referencing code and documentation
* Syntax highlighted code samples
* A vibrant ecosystem of first and third-party extensions

If you want to learn more about how to create your first Sphinx project, read on.

Building Docsy
--------------

Assuming you have Python, pip and virtual environment support installed, clone this repository:

.. prompt:: console

    $ git clone https://github.com/purduecyan/docsy
    $ cd docsy


Create a python virtual environment and install the package:
    
.. prompt:: console

    $ python3 -m venv .venv
    $ source .venv/bin/activate
    $ pip install .


This will install Sphinx and some other useful packages. You can now build the documentation
for this project by running:

.. prompt:: console

    $ cd docs
    $ make html


The documentation will be built into your ``build/html/`` directory.
Open the ``index.html`` file in your web browser to see your docs.


Updating Git Submodules
-----------------------

To update all git submodule repositories in the source folder:

.. prompt:: console

    $ cd source
    $ git submodule update --remote


Next, add, commit and push the files to remote for changes to take effect.


External resources
------------------

Here are some external resources to help you learn more about Sphinx.

* `Sphinx Cheat Sheet`_
* `Sphinx reStructuredText Primer`_
* `Sphinx documentation`_
* `An introduction to Sphinx and Read the Docs for technical writers`_


.. _Sphinx Cheat Sheet: https://sphinx-tutorial.readthedocs.io/cheatsheet/

.. _Sphinx reStructuredText Primer: https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html

.. _Sphinx documentation: https://www.sphinx-doc.org/

.. _An introduction to Sphinx and Read the Docs for technical writers: https://www.ericholscher.com/blog/2016/jul/1/sphinx-and-rtd-for-writers/
