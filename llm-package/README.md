---
id:
title: "Framework Package — LLM Ingestion Format"
author: Anton
created: 2026-02-12
modified: 2026-02-13
version: 1.1
format: prose
---

# Framework Package — LLM Ingestion Format

This package is designed for loading the constraint framework into an LLM context window. It contains the same content as the full texts in `texts/`, rendered in a compact notation-optimized format.

For the human-readable source texts, see [`texts/`](../texts/).

## Documents

Read in order:

1. **01-foundation.md** — Constraints (C1–C7), symbol table, two-level architecture, key definitions. **Read first, refer back often.**

2. **02-derivation.md** — Full derivation: boundary from minimal conditions (Part A), embedded consequences (Part B), epistemic-ontological convergence proof (Part C). Hybrid IR-1/prose.

3. **03-applications.md** — Hallucination analysis, semantic fracture detection protocol, entity evaluation methodology.

## Notes

- Symbol definitions in 01-foundation.md are canonical. All other documents use them.
- IR-1 format: English for structure/guidance, symbols for precision. See `reference/IR-1-Protocol.md` for the rendering protocol.
- For the derivation process itself, see [`core/`](../core/).
