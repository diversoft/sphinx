test-toctree-glob
=================

normal order
------------

.. toctree::
   :glob:

   foo
   bar/index
   bar/*
   baz
   qux/index
   hyperref <https://sphinx-doc.org/?q=sphinx>

reversed order
--------------

.. toctree::
   :glob:
   :reversed:

   foo
   bar/index
   bar/*
   baz
   qux/index
