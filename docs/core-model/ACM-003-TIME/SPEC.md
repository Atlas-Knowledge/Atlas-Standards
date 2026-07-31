---
id: ACM-003
title: Time
version: 1.0.0
status: Draft
category: Core Model
---

# ACM-003 — Time

> **This document is Normative.**

---

# 1. Abstract

Time represents the temporal dimension of Atlas.

Time enables ordering, validity, scheduling, expiration, auditing, and historical reconstruction.

---

# 2. Purpose

Time provides:

- ordering
- chronology
- validity
- synchronization
- traceability

---

# 3. Non-Goals

This specification does NOT define:

- ISO 8601
- Unix Timestamp
- Epoch time
- Time zones
- Calendar systems

Concrete representations belong to Atlas Standards.

---

# 4. Requirements

Every temporal value SHALL be:

- comparable
- immutable
- deterministic
- unambiguous

---

# 5. Temporal Concepts

Time MAY represent:

- creation
- modification
- publication
- expiration
- execution
- observation

---

# 6. Ordering

Atlas SHALL support temporal ordering.

Earlier and later events SHALL be distinguishable.

Ordering semantics MUST remain deterministic.

---

# 7. Validity

Time MAY define:

- valid from
- valid until

Expired values SHALL remain historically observable unless removed by policy.

---

# 8. Synchronization

Atlas does not mandate a synchronization mechanism.

Implementations MAY use:

- NTP
- PTP
- Trusted external sources

---

# 9. Validation

A valid temporal value SHALL:

- identify one instant or interval
- support ordering
- remain immutable

---

# 10. Security

Temporal information SHALL NOT be modified without authorization.

Audit timestamps SHOULD remain tamper-evident.

---

# 11. Conformance

An implementation conforms if:

- temporal values are comparable
- temporal values are immutable
- ordering is deterministic

---

# References

CAN-001 Constitution

CAN-003 Principles

RFC 2119

---

# Revision History

## Version 1.0.0

Initial Draft.
