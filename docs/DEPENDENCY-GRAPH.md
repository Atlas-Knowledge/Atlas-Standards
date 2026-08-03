# Atlas Standards Dependency Graph

## Layered Architecture

```text
Atlas-Core
        │
        ▼
Atlas-Specifications
        │
        ▼
Canon (CAN)
        │
        ▼
Foundation Model (AFM)
        │
        ▼
Core Model (ACM)
        │
        ▼
Information Model (AIM)
        │
        ▼
Type Model (ATM)
        │
        ▼
Execution Model (AEM)
        │
        ▼
Standards (STD)
        │
        ▼
Conformance (CTS)
        │
        ▼
Reference Implementation
```

---

## Dependency Rules

- Lower layers MUST NOT depend on higher layers.
- Every layer SHOULD depend only on the immediately preceding layer.
- Cyclic dependencies MUST NOT exist.

---

## Guiding Principle

> Dependencies flow downward through the Atlas architecture and never upward.
