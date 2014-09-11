.. reference: configuration information for a package
   expected by the component overview

******************
Deployment options
******************

.. .....................................................................
   This file's structure is IN PROGRESS
   .....................................................................

.. _betty-layout_compilation:

=======================
Compilation
=======================

.. .....................................................................
   Change this line depending on your auto conf system.
   .....................................................................

To see all the compilation options, go to the source code and call `configure --help` from the command line.

.. .....................................................................
   Only document special or tricky options here, not the whole set.
   Use the object directive:

   .. object:: --stuff

      Compiles stuff.
   .....................................................................



.. _betty-layout_integration:

=======================
Integration
=======================

.. .....................................................................
   In the future, you can change the following directive to include gen-chunk-useflags.rst instead (when the ebuild format is updated).
   .....................................................................

.. include:: chunk-useflags.rst



.. _betty-layout_execution:

===============================
Execution
===============================

.. .....................................................................
   Contents:
   If n/a, "Not an executable."
   Otherwise, use the program, envvar, option directives as in the example:

   .. program:: betty-layout (ususally)

   .. envvar:: BLAH

      Description of the environment variable

   .. option:: -v <value>, --velociraptor <value>

      Description of the command line option
   .....................................................................

