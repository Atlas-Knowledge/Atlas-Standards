---
id: STD-000
title: Atlas Standards Framework
version: 1.0.0
status: Draft
category: Standards
---

# STD-000 — Atlas Standards Framework

> **This document is Normative.**

---

# 1. Purpose

This specification defines the normative framework governing all Atlas
standards and specification artifacts.

---

# 2. Artifact Categories

Atlas defines the following artifact categories:

- Canon (CAN)
- Core Model (ACM)
- Type Model (ATM)
- Information Model (AIM)
- Execution Model (AEM)
- Standard (STD)
- Policy (POL)
- Conformance Test Suite (CTS)
- Reference Implementation (REF)

Each category has a distinct responsibility.

---

# 3. Artifact Hierarchy

The dependency hierarchy SHALL be:

CAN

↓

ACM

↓

ATM

↓

AIM

↓

AEM

↓

STD

↓

POL

↓

CTS

↓

Reference Implementation

Higher layers SHALL NOT depend on lower layers.

---

# 4. Normative Language

Atlas adopts RFC 2119 terminology.

Normative keywords include:

- SHALL
- SHALL NOT
- SHOULD
- SHOULD NOT
- MAY

---

# 5. Lifecycle

Every Atlas artifact SHALL progress through:

Draft

↓

Review

↓

Candidate

↓

Stable

↓

Deprecated

↓

Archived

---

# 6. Governance

Normative artifacts SHALL be approved by the Atlas Standards Council.

---

# 7. Dependencies

Every artifact SHALL declare its dependencies explicitly.

Circular dependencies are prohibited.

---

# 8. Versioning

Every artifact SHALL define:

- Identifier
- Version
- Status
- Revision History

Concrete version representations are defined separately.

---

# 9. Conformance

Only Stable artifacts MAY be used for official Atlas compatibility claims.

---

# References

CAN-001 Constitution

CAN-002 Charter

CAN-003 Principles

RFC 2119

---

# Revision History

Version 1.0.0

Initial Draft.
