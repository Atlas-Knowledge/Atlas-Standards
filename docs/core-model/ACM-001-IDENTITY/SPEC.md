---
id: ACM-001
title: Identity
version: 1.0.0
status: Draft
category: Core Model
---

# ACM-001 — Identity

> **This document is Normative.**

---

# 1. Abstract

Identity is the canonical mechanism for distinguishing one Atlas object from another.

Identity is a concept.

It is **not** an implementation.

---

# 2. Purpose

Identity provides:

- uniqueness
- persistence
- traceability
- interoperability

Every Atlas object SHALL possess one and only one Identity.

---

# 3. Non-Goals

This specification does NOT define:

- UUID
- ULID
- KSUID
- Snowflake IDs
- Database primary keys

Concrete representations belong to Atlas Standards.

---

# 4. Identity Requirements

Every Identity SHALL be:

- Unique
- Immutable
- Stable
- Opaque
- Verifiable

---

# 5. Identity Lifetime

Once assigned,

an Identity SHALL NEVER change.

An Identity SHALL NEVER be reassigned to another object.

---

# 6. Identity Independence

Identity SHALL remain independent of:

- storage engines
- databases
- programming languages
- transport protocols
- deployment topology

---

# 7. Identity Relationships

Identity MAY be referenced.

Identity SHALL NOT contain references to other objects.

Relationships are defined separately by the Information Model.

---

# 8. Validation

A valid Identity SHALL satisfy all normative requirements defined by this specification.

Concrete validation algorithms are defined by implementation standards.

---

# 9. Security

Identity SHALL NOT expose confidential information.

Identity SHOULD resist enumeration whenever practical.

---

# 10. Privacy

Identity SHALL NOT encode personally identifiable information.

---

# 11. Conformance

An implementation conforms if:

- every object possesses one Identity
- Identity remains immutable
- Identity is globally unique within its declared scope
- Identity is implementation-independent

---

# References

CAN-001 Constitution

CAN-003 Principles

RFC 2119

---

# Revision History

## Version 1.0.0

Initial Draft.
