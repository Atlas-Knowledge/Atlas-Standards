---
id: AIM-002
title: Entity
version: 1.0.0
status: Draft
category: Information Model
---

# AIM-002 — Entity

> This document is **Normative**.

---

# 1. Abstract

An Entity is a Resource representing an independently identifiable thing.

Every Entity SHALL inherit all Resource semantics.

---

# 2. Purpose

Entities provide stable information objects that participate in Atlas knowledge.

---

# 3. Characteristics

Every Entity SHALL:

- possess one Identity
- possess Metadata
- possess a State
- possess a Version
- participate in a Lifecycle

---

# 4. Independence

Entities exist independently.

Deleting another Entity SHALL NOT invalidate this Entity.

---

# 5. Relationships

Entities MAY participate in Relationships.

Relationship semantics are defined by AIM-003.

---

# 6. Composition

Entity is composed of:

- Resource
- Identity
- Version
- Time
- Metadata
- State
- Classification
- Extension

---

# 7. Validation

Every Entity SHALL satisfy Resource validation.

Additional validation MAY be defined by specialized Entity types.

---

# 8. Conformance

Implementations conform if:

- every Entity is also a Resource
- Resource semantics remain preserved
- Entity validation succeeds

---

# References

AIM-001 Resource

ACM-001 through ACM-010

RFC 2119

---

# Revision History

Version 1.0.0

Initial Draft.
