# AEM-005 — Messaging Service

> This document is **Normative**.

## Responsibilities

Messaging Services SHALL:

- deliver messages
- preserve message integrity
- support asynchronous communication
- support synchronous communication where applicable

Concrete protocols (HTTP, gRPC, AMQP, MQTT, etc.) are outside the scope of this specification.

---

## Conformance

Messages SHALL preserve ordering semantics whenever explicitly required.
