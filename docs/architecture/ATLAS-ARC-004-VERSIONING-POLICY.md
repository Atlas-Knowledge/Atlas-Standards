---
id: ATLAS-ARC-004
title: Versioning Policy
version: 1.0.0
status: Draft
category: Architecture
owner: Atlas Architecture Group
created: 2026-07-31
last_updated: 2026-07-31
reviewers: []
depends_on:
  - ATLAS-ARC-001
  - ATLAS-ARC-002
referenced_by: []
tags:
  - architecture
  - versioning
  - governance
---

# Versioning Policy

## Purpose

This document defines the official versioning strategy for all Atlas repositories, specifications, and releases.

Atlas adopts Semantic Versioning (SemVer 2.0.0) to ensure predictable evolution, compatibility, and traceability across the ecosystem.

---

# Semantic Versioning

Atlas uses the following format:

MAJOR.MINOR.PATCH

Example:

1.0.0

Where:

- MAJOR introduces incompatible changes.
- MINOR introduces backward-compatible functionality.
- PATCH introduces backward-compatible fixes.

---

# Repository Versioning

Each Atlas repository maintains its own version.

Examples:

- atlas-kernel v1.2.0
- atlas-runtime v1.1.3
- atlas-sdk v2.0.0

Repositories evolve independently but declare compatibility with Atlas specifications.

---

# Specification Versioning

Every specification includes its own version metadata.

Example:

version: 1.0.0

Specification versions evolve independently from implementation versions.

---

# Release Compatibility

Repositories should declare which Atlas specification release they implement.

Example:

Compatible with:

- ATLAS Specifications v1.0.0

---

# Breaking Changes

Breaking changes require:

- Major version increment.
- Updated documentation.
- Migration guidance.
- Changelog entry.
- Review and approval.

---

# Deprecation Policy

Deprecated features should:

- Be clearly documented.
- Include replacement guidance.
- Remain supported for at least one stable release whenever practical.

---

# Release Types

Development

Draft versions under active development.

Stable

Fully reviewed and approved releases.

Maintenance

Bug fixes and security updates.

Archived

No longer maintained.

---

# Changelog

Every release must update CHANGELOG.md.

---

# References

- Semantic Versioning 2.0.0
- ATLAS-ARC-001 Architecture Constitution
- ATLAS-ARC-002 Governance

---

# Revision History

## Version 1.0.0

Initial release.
