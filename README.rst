========
pygccxml
========

pygccxml is a specialized XML reader that reads the output from GCCXML. It provides a simple framework to navigate C++ declarations, using Python classes.

-------
Install
-------

The package uses the Python distutils so you can do the usual procedure:

  python setup.py install

For more information about using the distutils see the Python manual
"Installing Python Modules".

-------------
Documentation
-------------

For examples and tutorials see the pygccxml web site. An API reference
is available in the directory docs/apidocs in the source archive.

If you obtained the source code from the subversion repository you
have to build the API reference yourself. This can be done using the
setup script:

  python setup.py doc

In order for this to work you need epydoc (http://epydoc.sourceforge.net).

-------
Testing
-------

pygccxml has more than 200 unit tests. They are run after each code commit to ensure
that the code stays functional and stable. You can find the builds here:
https://travis-ci.org/gccxml/pygccxml/builds