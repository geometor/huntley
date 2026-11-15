# GEOMETOR • `huntley`

Exact symbolic mathematical catalog and concordance inspired by The Divine Proportion: A Study in Mathematical Beauty (H. E. Huntley)

---

## 1. Repository Identity & Archetype

- **Organization**: `geometor` (`GEOMETOR`)
- **Package**: `geometor.huntley` (`src/geometor/huntley/`)
- **Archetype**: `catalog`
- **Work**: *The Divine Proportion: A Study in Mathematical Beauty* — H. E. Huntley

---

## 2. Architectural & Editorial Mandates

1. **Python 3.13 & Exact Symbolic Standards**:
   - Every Python module begins with a module docstring followed immediately by `from __future__ import annotations`, built-in generic types (`list`, `dict`, `tuple`, `X | Y`), Google-style docstrings, and an explicit `__all__`.
   - Zero `float` or `sympy.Float` approximations in symbolic geometry constructions.
2. **Mathematical Catalog & Copyright Discipline (`catalog`)**:
   - **Zero Copyrighted Prose or Source Diagrams**: Never copy verbatim prose, chapter text, or scanned figures from modern copyrighted works. Author concise, original mathematical enunciations paired with 100% exact `SymPy` / `geometor.model` constructions and `.euclid-graphic` SVGs.
   - **Atomic Concordance**: Record every extracted claim or construction in `resources/catalog_manifest.json` and cross-link equivalences to `geometor/divine`, `geometor/knott`, `geometor/elements`, and sister repositories in `resources/concordance.json`.
   - **Git Hygiene**: Local study PDFs in `resources/pdfs/` remain strictly git-ignored (`*.pdf`).

---

## 3. Verification Commands (Offline Sandbox Safe)

```bash
uv run --no-sync pytest
ruff check src tests demos
publish build
```
