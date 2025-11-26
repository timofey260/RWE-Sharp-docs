.. RWE-Sharp documentation master file, created by
   sphinx-quickstart on Fri Nov  7 23:19:27 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

RWE-Sharp documentation
=======================

Add your content using ``reStructuredText`` syntax. See the
`reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
documentation for details.

.. autosummary::
   :toctree: _autosummary
   :template: custom-module-template.rst
   :recursive:

   BaseMod
   RWESharp
   main
   RWS

.. autosummary
   :toctree: _autosummary
   :template: custom-module-template2.rst
   :recursive:

   RWESharp2

.. automodapi BaseMod
   :include-all-objects:

.. toctree::
   Guides/Guides
   Guides/Quickstart

.. toctree
   autoapi/BaseMod/index
   autoapi/RWESharp/index
   autoapi/ui/index
   autoapi/widgets/index
   autoapi/main/index
   autoapi/index

.. toctree
   :maxdepth: 4
   :caption: Contents:

   BaseModWidgets
   RWESharp
   RWESharpWidgets
   UpdateChecker
   main
