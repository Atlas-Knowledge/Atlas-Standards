# Engineering Decisions

## Decision 001

Atlas separates conceptual models from implementation standards.

Reason:

Long-term architectural stability.

---

## Decision 002

Every normative artifact SHALL belong to exactly one category.

Reason:

Clear ownership and responsibility.

---

## Decision 003

Artifact dependencies SHALL always point upward in the architectural hierarchy.

Reason:

Prevent cyclic architecture.
