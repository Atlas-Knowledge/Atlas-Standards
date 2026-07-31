# Atlas Specification Manifest

> **Version:** 1.0.0
>
> **Status:** Active
>
> **Repository:** atlas-specs
>
> **Category:** Manifest

---

# Purpose

The Atlas Specification Manifest is the canonical index of all official
Atlas documents.

It provides a single entry point for navigating the Atlas specification
ecosystem.

Every official document published by Atlas must appear in this manifest.

---

# Document Status

Atlas documents may exist in one of the following states.

| Status | Meaning |
|----------|---------|
| Draft | Initial work in progress |
| Review | Under technical review |
| Approved | Accepted by maintainers |
| Stable | Official specification |
| Deprecated | Scheduled for removal |
| Archived | Historical reference only |

---

# Document Categories

Atlas defines six official document categories.

| Prefix | Description |
|----------|-------------|
| ARC | Architecture Documents |
| SPEC | Technical Specifications |
| STD | Standards |
| POL | Policies |
| ADR | Architecture Decision Records |
| RFC | Requests for Comments |

---

# Foundation Documents

| File | Status |
|------|--------|
| README.md | Stable |
| VISION.md | Draft |
| MANIFEST.md | Stable |
| CHANGELOG.md | Draft |
| SECURITY.md | Draft |
| CONTRIBUTING.md | Draft |
| CODE_OF_CONDUCT.md | Draft |
| SUPPORT.md | Draft |
| ROADMAP.md | Draft |

---

# Architecture Documents

| ID | Title | Status |
|----|--------|--------|
| ARC-001 | Architecture Constitution | Draft |
| ARC-002 | Governance | Draft |
| ARC-003 | Repository Model | Draft |
| ARC-004 | Versioning Policy | Planned |
| ARC-005 | Terminology | Planned |
| ARC-006 | Security Model | Planned |
| ARC-007 | Federation | Planned |
| ARC-008 | Runtime Architecture | Planned |
| ARC-009 | Deployment Model | Planned |
| ARC-010 | Scalability | Planned |

---

# Technical Specifications

| ID | Title | Status |
|----|--------|--------|
| SPEC-001 | Entity | Planned |
| SPEC-002 | Relationship | Planned |
| SPEC-003 | Evidence | Planned |
| SPEC-004 | Knowledge Graph | Planned |
| SPEC-005 | Node | Planned |
| SPEC-006 | Registry | Planned |
| SPEC-007 | Runtime | Planned |
| SPEC-008 | Identity | Planned |
| SPEC-009 | Capability | Planned |
| SPEC-010 | Contract | Planned |
| SPEC-011 | Event | Planned |
| SPEC-012 | Metadata | Planned |
| SPEC-013 | Schema | Planned |
| SPEC-014 | Query | Planned |
| SPEC-015 | Graph API | Planned |

---

# Standards

| ID | Title | Status |
|----|--------|--------|
| STD-001 | Repository Naming | Planned |
| STD-002 | Folder Structure | Planned |
| STD-003 | API Design | Planned |
| STD-004 | Error Codes | Planned |
| STD-005 | Event Naming | Planned |
| STD-006 | Logging | Planned |
| STD-007 | Metadata | Planned |
| STD-008 | Serialization | Planned |
| STD-009 | Configuration | Planned |
| STD-010 | Documentation | Planned |

---

# Policies

| ID | Title | Status |
|----|--------|--------|
| POL-001 | Security | Planned |
| POL-002 | Compatibility | Planned |
| POL-003 | Release Policy | Planned |
| POL-004 | Dependency Policy | Planned |
| POL-005 | Review Policy | Planned |
| POL-006 | Deprecation Policy | Planned |
| POL-007 | Branch Strategy | Planned |
| POL-008 | CI/CD Policy | Planned |

---

# Architecture Decision Records

| ID | Title | Status |
|----|--------|--------|
| ADR-0001 | Kernel First | Planned |
| ADR-0002 | Federation First | Planned |
| ADR-0003 | Repository Independence | Planned |
| ADR-0004 | Contract First | Planned |
| ADR-0005 | Event Driven | Planned |
| ADR-0006 | Documentation First | Planned |

---

# RFC Documents

| ID | Title | Status |
|----|--------|--------|
| RFC-0000 | RFC Process | Planned |
| RFC-TEMPLATE | RFC Template | Planned |

---

# Dependency Rules

Documents follow the hierarchy below.

```
VISION

↓

ARC

↓

SPEC

↓

STD

↓

POL

↓

ADR

↓

RFC

↓

Implementation
```

Higher-level documents define the constraints for lower-level documents.

---

# Versioning

Every document has an independent version.

Major changes require review.

Breaking architectural changes require approval.

---

# Canonical Source

This repository is the canonical source for all Atlas specifications.

No implementation repository may redefine the contents of this manifest.

---

# End of Document
