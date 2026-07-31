---
id: ACM-004
title: State
version: 1.0.0
status: Draft
category: Core Model
---

# ACM-004 — State

> **This document is Normative.**

---

# 1. Abstract

State represents the condition of an Atlas object at a specific point in its lifecycle.

State enables lifecycle management, validation, interoperability, and conformance.

---

# 2. Purpose

State provides:

- lifecycle tracking
- transition validation
- operational consistency
- historical traceability

---

# 3. Non-Goals

This specification does NOT define:

- Workflow engines
- Business processes
- Approval procedures
- State machine implementations

Those belong to higher-level specifications.

---

# 4. Requirements

Every State SHALL be:

- identifiable
- deterministic
- observable
- comparable

---

# 5. State Lifecycle

A State MAY change over time.

Each transition SHALL create a new lifecycle event.

Previous states SHOULD remain observable for audit purposes.

---

# 6. State Transitions

Transitions SHALL:

- be explicit
- be validated
- preserve consistency

Invalid transitions SHALL be rejected.

---

# 7. Independence

State SHALL remain independent of:

- storage technology
- programming language
- workflow engine
- transport protocol

---

# 8. Validation

A valid State SHALL:

- belong to exactly one lifecycle
- support deterministic transitions
- be uniquely identifiable within that lifecycle

---

# 9. Security

Unauthorized state transitions SHALL be rejected.

State changes SHOULD be auditable.

---

# 10. Conformance

An implementation conforms if:

- states are deterministic
- transitions are validated
- lifecycle integrity is preserved

---

# References

CAN-001 Constitution

CAN-003 Principles

ACM-003 Time

RFC 2119

---

# Revision History

## Version 1.0.0

Initial Draft.
