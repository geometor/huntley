:navigation: header
:order: 20
:nav_title: About

=====
About
=====

``geometor.huntley`` is developed and maintained by **phiarchitect** as part of the **GEOMETOR** organization.

Exact symbolic mathematical catalog and concordance inspired by The Divine Proportion: A Study in Mathematical Beauty (H. E. Huntley)

Repository Architecture
-----------------------

- **Python Package**: ``src/geometor/huntley/`` (Python 3.13)
- **Mathematical Catalog**: ``docsrc/catalog/`` (``:layout: book``)
- **Manifest & Concordance**: ``resources/catalog_manifest.json``, ``resources/concordance.json``
- **Automated Verification**: ``tests/`` (``pytest`` + ``ruff``) and ``docsrc/`` (``publish build``)
