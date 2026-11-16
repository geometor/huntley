:navigation: header
:order: 90

=======
Modules
=======

API summary for ``geometor.huntley``:

- :mod:`geometor.huntley` — Public package interface exporting ``__version__`` and :func:`~geometor.huntley.app.run`.
- :mod:`geometor.huntley.app` — Command-line parser (:func:`~geometor.huntley.app.build_parser`) and entry point (:func:`~geometor.huntley.app.main`).
- :mod:`geometor.huntley.catalog` — Typed catalog manifest descriptor (:class:`~geometor.huntley.catalog.CatalogEntrySpec`), loader (:func:`~geometor.huntley.catalog.load_catalog_manifest`), and exact-algebra guard (:func:`~geometor.huntley.catalog.assert_no_floats`).
