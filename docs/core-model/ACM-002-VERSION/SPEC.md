---
id: ACM-002
title: Version
version: 1.0.0
status: Draft
category: Core Model
---

# ACM-002 — Version

> **This document is Normative.**

---

# 1. Abstract

Version represents the evolution of an Atlas artifact.

A Version identifies a specific state of an artifact within its lifecycle.

---

# 2. Purpose

Version enables:

- evolution
- compatibility
- traceability
- reproducibility

---

# 3. Non-Goals

This specification does NOT define:

- Semantic Versioning
- Calendar Versioning
- Monotonic Versioning
- Git hashes
- Build numbers

Concrete version representations are defined by Atlas Standards.

---

# 4. Requirements

Every Version SHALL be:

- Immutable
- Comparable
- Traceable
- Verifiable

---

# 5. Version Scope

A Version applies to exactly one artifact.

Different artifacts SHALL maintain independent version histories.

---

# 6. Compatibility

A Version MAY declare compatibility with other versions.

Compatibility semantics are defined by implementation standards.

---

# 7. Evolution

Every change resulting in a new published artifact SHALL create a new Version.

Published Versions SHALL remain immutable.

---

# 8. Validation

A valid Version SHALL:

- identify one revision
- remain immutable
- support comparison

---

# 9. Security

Versions SHALL NOT expose confidential implementation details.

---

# 10. Conformance

An implementation conforms if:

- Versions are immutable.
- Versions identify a single artifact revision.
- Version comparison is deterministic.

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
