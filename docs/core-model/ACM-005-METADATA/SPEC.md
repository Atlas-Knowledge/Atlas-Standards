---
id: ACM-005
title: Metadata
version: 1.0.0
status: Draft
category: Core Model
---

# ACM-005 — Metadata

> This document is **Normative**.

---

# 1. Abstract

Metadata is structured information describing an Atlas object.

Metadata improves discoverability, traceability, interoperability, governance, and lifecycle management.

Metadata does not define the object itself.

It describes the object.

---

# 2. Purpose

Metadata provides:

- description
- ownership
- provenance
- discoverability
- classification
- governance

---

# 3. Non-Goals

This specification does NOT define:

- database schemas
- serialization formats
- search indexes
- storage layouts

Those belong to implementation standards.

---

# 4. Requirements

Metadata SHALL be:

- structured
- extensible
- machine-readable
- deterministic
- versionable

---

# 5. Ownership

Every Metadata object SHALL describe exactly one Atlas object.

Metadata SHALL NOT possess an independent lifecycle separate from the object it describes.

---

# 6. Evolution

Metadata MAY evolve.

Every published Metadata revision SHALL remain traceable.

---

# 7. Validation

Metadata SHALL satisfy:

- structural validation
- semantic validation
- compatibility validation

---

# 8. Extensibility

Implementations MAY extend Metadata.

Extensions SHALL NOT invalidate canonical metadata.

---

# 9. Security

Sensitive metadata SHOULD be protected.

Visibility MAY depend on authorization.

---

# 10. Privacy

Personally identifiable information SHOULD NOT appear unless explicitly permitted by higher-level specifications.

---

# 11. Conformance

An implementation conforms if:

- metadata remains structured
- metadata remains associated with one object
- metadata validates successfully
- metadata remains extensible

---

# References

CAN-001 Constitution

CAN-003 Principles

ACM-001 Identity

RFC 2119

---

# Revision History

## Version 1.0.0

Initial Draft.
