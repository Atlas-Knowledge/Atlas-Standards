---
id: AIM-001
title: Resource
version: 1.0.0
status: Draft
category: Information Model
owner: Atlas Standards Council
package: AIM-001-RESOURCE
---

# AIM-001 — Resource

## Overview

Resource is the fundamental information object of the Atlas Information Model.

Every Atlas object that can be identified, described, referenced, governed, or exchanged SHALL be modeled as a Resource.

Resource is the root abstraction of the Information Model.

---

## Purpose

The Resource model provides a common abstraction for representing information independently of implementation technologies.

---

## Scope

This specification applies to:

- Entity
- Relationship
- Event
- Contract
- Registry Record
- Node
- Collection
- Graph
- Knowledge Space

Future Atlas object types SHALL derive from Resource.

---

## Package Contents

| File | Description |
|------|-------------|
| SPEC.md | Normative Specification |
| schema.json | Concept Schema |
| examples.md | Usage Examples |
| compatibility.md | Compatibility Rules |
| tests.yaml | Conformance Tests |
| CHANGELOG.md | Revision History |

---

## Dependencies

- ACM-001 Identity
- ACM-002 Version
- ACM-003 Time
- ACM-004 State
- ACM-005 Metadata
- ACM-006 Reference
- ACM-007 Classification
- ACM-008 Extension
- ACM-009 Capability
- ACM-010 Constraint

---

## Status

Draft

Version 1.0.0
