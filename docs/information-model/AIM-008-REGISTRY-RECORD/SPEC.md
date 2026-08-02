# AIM-008 — Registry Record

> This document is **Normative**.

## Abstract

A Registry Record represents the authoritative registration metadata of a Resource.

A Registry Record SHALL reference exactly one Resource.

---

## Requirements

Every Registry Record SHALL:

- possess an Identity
- reference one Resource
- record registration metadata
- support Versioning
- support auditing

---

## Conformance

Registry integrity SHALL be preserved.

Duplicate registrations SHALL be rejected.
