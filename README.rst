GEOMETOR • huntley
==================

**Visit the Online Archive:** https://geometor.github.io/huntley/

**H. E. Huntley • The Divine Proportion • semantic digital archive**

Mission
-------

``geometor/huntley`` is part of the interconnected `GEOMETOR <https://geometor.com>`_ semantic digital archive. It provides an exact symbolic mathematical catalog and cross-corpus concordance inspired by H. E. Huntley's classic treatise *The Divine Proportion: A Study in Mathematical Beauty* (1970). By formulating Huntley's aesthetic principles, golden rectangles, logarithmic spirals, and Fibonacci relationships into certified algebraic models and calibrated vector graphics, the archive establishes a rigorous computational bridge connecting classical golden-ratio geometry across the GEOMETOR corpus.

Catalogs in This Archive
------------------------

- `The Divine Proportion — Mathematical Catalog & Concordance <https://geometor.github.io/huntley/catalog/>`_ — Exact symbolic catalog and cross-corpus concordance of H. E. Huntley's geometric and aesthetic theorems.

Python Package & Modules
------------------------

The ``geometor-huntley`` Python package (``import geometor.huntley``) provides the executable symbolic geometry, construction, and compilation modules powering this archive:

- ``catalog.py`` — Catalog manifest loader and exact-symbolic validation helpers.
- ``app.py`` — Command-line interface for ``geometor.huntley``.

See the `API Reference <https://geometor.github.io/huntley/modules/>`_ for full module documentation.

Repository Contents
-------------------

- ``docsrc/`` — RST catalog tracks, guides, and concordances compiled by `PHOTON publish <https://github.com/photon-platform/publish>`_.
- ``resources/`` — Curated mathematical manifests and cross-corpus concordance registries.
- ``src/geometor/huntley/`` — Symbolic modeling modules, CLI tools, and catalog validators.

Local Build & Verification
--------------------------

.. code-block:: bash

   publish build
   uv run --no-sync pytest

Part of the GEOMETOR Knowledge Archive
--------------------------------------

Explore all **74 Book Codices** and **11 Mathematical Catalogs** at https://geometor.com/books/.
