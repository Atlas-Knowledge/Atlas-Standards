# AIM-003 — Relationship

> This document is **Normative**.

---

## Abstract

A Relationship is a Resource describing semantic connections between Resources.

Relationships SHALL NOT duplicate the information contained by the connected Resources.

---

## Requirements

Every Relationship SHALL:

- possess an Identity
- reference at least two Resources
- define relationship semantics
- support Metadata
- support Versioning

---

## Relationship Types

Examples include:

- contains
- depends_on
- references
- owns
- extends
- implements
- derived_from

Atlas does not prescribe a closed vocabulary.

---

## Directionality

Relationships MAY be:

- directed
- undirected

Direction SHALL be explicitly declared.

---

## Conformance

Implementations SHALL preserve relationship integrity.

Broken references invalidate the Relationship.
