# ATM-002 — Value Type

> This document is **Normative**.

## Abstract

A Value Type represents a value rather than an object.

Two Value Types with identical contents SHALL be considered equal.

Value Types SHALL NOT possess independent identity.

---

## Requirements

Every Value Type SHALL be:

- immutable
- comparable
- deterministic
- implementation-independent

---

## Examples

- Duration
- Coordinate
- Currency Amount
- Percentage
- Temperature

---

## Conformance

Implementations SHALL preserve value semantics.

Identity-based comparison is prohibited.
