---
id: ACM-006
title: Reference
version: 1.0.0
status: Draft
category: Core Model
---

# ACM-006 — Reference

> **This document is Normative.**

---

# 1. Abstract

A Reference is a canonical mechanism for identifying another Atlas object.

A Reference never owns the referenced object.

---

# 2. Purpose

Reference enables:

- linking
- interoperability
- dependency declaration
- traceability

---

# 3. Non-Goals

This specification does NOT define:

- URLs
- URIs
- Database foreign keys
- API endpoints

Concrete representations belong to Atlas Standards.

---

# 4. Requirements

Every Reference SHALL be:

- explicit
- immutable
- resolvable
- verifiable

---

# 5. Ownership

A Reference SHALL NOT imply ownership.

Deleting a Reference SHALL NOT delete the referenced object.

---

# 6. Resolution

Reference resolution MAY occur:

- locally
- remotely
- through a registry
- through an implementation-defined mechanism

---

# 7. Validation

A valid Reference SHALL:

- identify exactly one target
- remain syntactically valid
- preserve referential integrity

---

# 8. Security

Reference resolution SHALL follow Atlas authorization policies.

References SHALL NOT bypass access control.

---

# 9. Conformance

An implementation conforms if:

- references are explicit
- references remain immutable
- references preserve referential integrity

---

# References

CAN-001 Constitution

ACM-001 Identity

RFC 2119

---

# Revision History

## Version 1.0.0

Initial Draft.
