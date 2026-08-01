---
id: STD-001
title: Specification Package Standard
version: 1.0.0
status: Draft
category: Standards
---

# STD-001 — Specification Package Standard

> This document is **Normative**.

---

# 1. Purpose

Every Atlas Specification SHALL be organized as a Specification Package.

A Specification Package is the smallest independently versioned documentation unit within Atlas.

---

# 2. Required Files

Every Specification Package SHALL contain:

- README.md
- SPEC.md
- MANIFEST.yaml
- RATIONALE.md
- DECISIONS.md
- DEPENDENCIES.md
- CHANGELOG.md

---

# 3. Recommended Files

The following files SHOULD exist when applicable:

- EXAMPLES.md
- COMPATIBILITY.md
- TYPE-MAPPING.md
- TESTS.yaml
- SCHEMA.json

---

# 4. Assets

Non-text resources SHALL be stored inside:

assets/

Examples include:

- diagrams
- images
- reference figures

---

# 5. Metadata

Every package SHALL define:

- Identifier
- Title
- Version
- Status
- Category
- Owner

Metadata SHALL remain synchronized with MANIFEST.yaml.

---

# 6. Naming

Directories SHALL follow:

XXX-NNN-NAME

Example:

ACM-001-IDENTITY

STD-001-SPECIFICATION-PACKAGE-STANDARD

---

# 7. Versioning

Each package SHALL maintain its own version history.

Package versions SHALL be immutable after publication.

---

# 8. Validation

A Specification Package is valid only if:

- all required files exist
- metadata is complete
- dependencies resolve successfully
- identifiers are unique

---

# 9. Conformance

Atlas tooling SHALL validate Specification Packages according to this standard.

---

# References

STD-000 Standards Framework

CAN-001 Constitution

RFC 2119
