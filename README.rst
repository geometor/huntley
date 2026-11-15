=======
huntley
=======

Exact symbolic mathematical catalog and concordance inspired by The Divine Proportion: A Study in Mathematical Beauty (H. E. Huntley)

Catalog Overview
----------------

- **Reference Work**: *The Divine Proportion: A Study in Mathematical Beauty* (H. E. Huntley)
- **Catalog Track**: ``docsrc/catalog/`` (``:layout: book``)
- **Symbolic Manifest & Concordance**: ``resources/catalog_manifest.json``, ``resources/concordance.json``
Installation & Verification
---------------------------

Managed with ``uv`` on Python 3.13:

.. code-block:: bash

   uv run --no-sync pytest
   ruff check src tests demos
   publish build

Usage
-----

.. code-block:: bash

   huntley --help

Links
-----

- **Documentation**: https://geometor.github.io/huntley
- **Repository**: https://github.com/geometor/huntley
- **Issues**: https://github.com/geometor/huntley/issues

License
-------

Licensed under the MIT License. See ``LICENSE`` for details.
