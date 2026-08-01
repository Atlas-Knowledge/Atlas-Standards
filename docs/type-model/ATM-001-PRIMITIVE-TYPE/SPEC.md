---
id: ATM-001
title: Primitive Type
version: 1.0.0
status: Draft
category: Type Model
---

# ATM-001 — Primitive Type

> **This document is Normative.**

---

# 1. Abstract

Primitive Types are the atomic value concepts of Atlas.

They cannot be decomposed into simpler Atlas Types.

---

# 2. Purpose

Primitive Types provide the building blocks for all Atlas data models.

Higher-level Types SHALL be composed from Primitive Types.

---

# 3. Non-Goals

This specification does NOT define:

- int
- float
- string
- bool
- Java types
- TypeScript types
- Rust types
- C++ types

Those belong to implementation bindings.

---

# 4. Requirements

Every Primitive Type SHALL be:

- atomic
- deterministic
- implementation-independent
- immutable by definition

---

# 5. Composition

Primitive Types SHALL NOT depend upon Composite Types.

Primitive Types MAY be combined to create higher-order Types.

---

# 6. Type Identity

Each Primitive Type SHALL possess a unique conceptual identity.

Primitive Types SHALL remain stable across Atlas versions.

---

# 7. Validation

Primitive Types SHALL define deterministic validation semantics.

Implementations MAY define concrete validation algorithms.

---

# 8. Compatibility

Primitive Types SHALL preserve backward compatibility whenever practical.

Breaking semantic changes REQUIRE a major version.

---

# 9. Conformance

An implementation conforms if:

- Primitive Types remain atomic.
- Primitive Types remain implementation-independent.
- Validation semantics remain deterministic.

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
