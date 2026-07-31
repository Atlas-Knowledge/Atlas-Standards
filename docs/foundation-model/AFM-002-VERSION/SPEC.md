---
id: AFM-002
title: Version Specification
version: 1.0.0
status: Draft
category: Foundation Model
---

# AFM-002 — Version Specification

> This document is Normative.

---

# 1. Abstract

This specification defines the canonical Version model used throughout Atlas.

Every versioned Atlas artifact SHALL expose a Version object.

---

# 2. Scope

This specification defines:

- Version format
- Version compatibility
- Version comparison
- Version validation
- Serialization
- Conformance

---

# 3. Definition

A Version identifies a specific revision of an artifact.

Versions SHALL be immutable.

---

# 4. Requirements

Every Version MUST contain:

- major
- minor
- patch

Optional fields MAY include:

- prerelease
- build

---

# 5. Semantic Versioning

Atlas adopts Semantic Versioning 2.0.0.

Format:

MAJOR.MINOR.PATCH

Example:

1.0.0

---

# 6. Compatibility Rules

PATCH versions MUST remain backward compatible.

MINOR versions SHOULD remain backward compatible.

MAJOR versions MAY introduce breaking changes.

---

# 7. Comparison

Versions SHALL compare using:

Major

↓

Minor

↓

Patch

↓

Prerelease

---

# 8. Serialization

Canonical JSON

{
  "major":1,
  "minor":0,
  "patch":0
}

---

# 9. Validation

A Version is valid if:

- major >= 0
- minor >= 0
- patch >= 0

---

# 10. Conformance

An implementation conforms if:

- versions serialize correctly
- versions compare correctly
- compatibility rules are enforced

---

# References

Semantic Versioning 2.0.0

RFC 2119

---

# Revision History

Version 1.0.0

Initial Draft
