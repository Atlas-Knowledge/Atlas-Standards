# AEM-001 — Execution Kernel

> This document is **Normative**.

---

## Abstract

The Execution Kernel coordinates execution across Atlas components.

The Kernel is responsible for orchestration rather than implementation.

---

## Responsibilities

The Kernel SHALL:

- discover services
- coordinate execution
- manage lifecycle
- expose capabilities
- enforce execution boundaries

---

## Non-Responsibilities

The Kernel SHALL NOT:

- store application data
- implement business logic
- define network protocols
- define persistence mechanisms

---

## Conformance

Every Atlas implementation SHALL expose an Execution Kernel or an equivalent execution coordination mechanism.
