# ADR-000

# Governance

Status: Accepted

---

## Context

OnDoTut is intended to become a long-term engineering platform.

Architecture must remain independent from implementation.

---

## Decision

The architecture team is responsible for:

- Product architecture
- Technical specifications
- Module specifications
- API specifications
- Security specifications
- Architecture Decision Records
- Architecture Review

The architecture team does not implement production code.

Implementation is performed according to the specifications contained in this repository.

---

## Consequences

Architecture becomes the primary source of truth.

Every implementation must comply with the architecture.

Any architectural change requires a new ADR.
