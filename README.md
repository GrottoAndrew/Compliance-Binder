# Ontology Engine

A foundational ontology engine for law firms and legal practices whose data
needs to be better structured, related, and queryable.

The service generates and maintains full data **ontology maps**, **DDLs**, and
the **frameworks** that connect a legal practice's language to a governed data
model — so that the way practitioners actually think about their terms drives
how the data is stored, versioned, and referenced.

## What it does

- **Ontology maps** — canonical terms, their relationships, and synonym
  resolution, decomposed only as far as practitioners actually reference the
  data (leaf-level where useful, clause-level where further decomposition adds
  no value).
- **DDL generation** — schema-first modeling where validated JSON Schemas are
  the contract from which the DDL is derived.
- **Tiered taxonomy** — terms tranched by how a practice actually needs to
  call and reference the data, not by abstract type.
- **Medallion architecture** — a layered data platform (raw → conformed →
  serving) with a schema-driven modeling layer feeding analytics-ready marts.
- **Foundational engine** — the shared core that other legal-data tooling can
  build on.

## Status

Early foundation. Structure, schemas, and framework decisions are being
established before implementation.

## License

Proprietary. See `LICENSE`.
