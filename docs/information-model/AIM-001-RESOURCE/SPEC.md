---
id: AIM-001
title: Resource
version: 1.0.0
status: Draft
category: Information Model
---

# AIM-001 — Resource

> **This document is Normative.**

---

# 1. Abstract

A Resource is the canonical information object within Atlas.

Every Atlas object SHALL be represented as a Resource or as a specialization of Resource.

---

# 2. Purpose

The Resource model establishes a common information abstraction for all Atlas models.

It enables interoperability, extensibility, governance, and conformance.

---

# 3. Non-Goals

This specification does NOT define:

- Entity semantics
- Relationship semantics
- Event processing
- Storage models
- APIs

These are defined by specialized specifications.

---

# 4. Requirements

Every Resource SHALL:

- possess one Identity
- expose Metadata
- have a State
- support Versioning
- support References
- satisfy applicable Constraints

---

# 5. Resource Composition

A Resource is composed of Core Model concepts.

Conceptually:

Resource

├── Identity

├── Version

├── Time

├── State

├── Metadata

├── Reference

├── Classification

├── Extension

├── Capability

└── Constraint

---

# 6. Resource Specialization

Resource MAY be specialized.

Examples include:

- Entity
- Relationship
- Event
- Contract
- Registry Record
- Node
- Collection
- Graph
- Knowledge Space

Every specialization SHALL preserve Resource semantics.

---

# 7. Lifecycle

Every Resource SHALL participate in a lifecycle.

Lifecycle definitions are provided by specialized specifications.

---

# 8. Extensibility

Resources MAY define extensions.

Extensions SHALL preserve compatibility with this specification.

---

# 9. Validation

A valid Resource SHALL satisfy every mandatory Core Model dependency.

Failure of any required dependency SHALL invalidate the Resource.

---

# 10. Security

Resources SHALL comply with Atlas Security Policies.

Sensitive metadata SHALL be protected.

---

# 11. Conformance

An implementation conforms if:

- every information object is modeled as a Resource
- Core Model dependencies are preserved
- Resource semantics remain unchanged

---

# References

CAN-001 Constitution

CAN-003 Principles

ACM-001 through ACM-010

RFC 2119

---

# Revision History

## Version 1.0.0

Initial Draft.
