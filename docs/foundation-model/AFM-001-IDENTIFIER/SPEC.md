---
id: AFM-001
title: Identifier Specification
version: 1.0.0
status: Draft
category: Foundation Model
---

# AFM-001 — Identifier Specification

> This document is Normative.

---

# 1. Abstract

This specification defines the canonical Identifier used throughout Atlas.

Every Atlas object SHALL have exactly one Identifier.

---

# 2. Scope

This specification defines:

- Identifier structure
- Identifier uniqueness
- Identifier lifecycle
- Validation
- Serialization
- Conformance

---

# 3. Definition

An Identifier is a globally unique value assigned to exactly one object.

Identifiers SHALL be immutable.

Identifiers SHALL NOT encode business meaning.

---

# 4. Requirements

Every Identifier MUST be:

- globally unique
- immutable
- opaque
- stable
- machine-readable

Identifiers SHOULD be URL-safe.

---

# 5. Lifetime

Identifiers never expire.

Deletion of an object SHALL NOT permit reuse of its Identifier.

---

# 6. Format

Atlas does not mandate a specific algorithm.

Acceptable implementations include:

- UUIDv7
- ULID
- KSUID
- Future Atlas Identifier formats

Implementations MUST document the chosen format.

---

# 7. Reserved Prefixes

Reserved prefixes include:

AFM

ATS

SYS

TMP

Future specifications may reserve additional prefixes.

---

# 8. Validation

An Identifier is valid if:

- non-empty
- syntactically valid
- unique
- immutable

Otherwise validation SHALL fail.

---

# 9. Serialization

Canonical JSON representation

{
"id":"01K1ABCDE123456789XYZ"
}

---

# 10. Security Considerations

Identifiers MUST NOT reveal:

- passwords
- secrets
- access tokens
- private information

Identifiers SHOULD be difficult to predict.

---

# 11. Privacy Considerations

Identifiers SHOULD NOT contain personally identifiable information.

---

# 12. Conformance

An implementation conforms if:

- identifiers are unique
- identifiers are immutable
- identifiers validate successfully
- identifiers serialize correctly

---

# References

RFC 4122

RFC 9562

---

# Revision History

Version 1.0.0

Initial Draft
