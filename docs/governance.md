# Governance

Retained legacy reference. Current layer governance is defined in [Foundation/governance.md](../Foundation/governance.md).

## Governance Model

The governance model of the ROD Framework is centered on authority, provenance, and structured metadata.

## Root Authority

The root creator is the sole source of truth for the framework. All framework records, metadata definitions, and downstream governance decisions derive from this authority.

## Node Classification

Creator records belong in `Creator/` (Layer 2), following the structural and metadata rules in `Foundation/` (Layer 1). Supporting layer documents are not creator records.

Support files are classified as follows:

- `README.md` = portal
- `LICENSE.md` = legal notice
- `NOTICE.md` = ownership/legal notice
- `CONTRIBUTING.md` = operational guidance
- `Foundation/` = Layer 1 rules and references
- `Creator/` = Layer 2 creator records and supporting documents
- `docs/` and `framework/` = retained legacy references, records, and forms, not active layers

## Governance Rules

1. The root node remains authoritative.
2. Creator records are defined in `Creator/`, governed by `Foundation/`.
3. Root files and supporting layer documents must not be misclassified as creator records.
4. Metadata changes require review against the root framework definition.
5. Legal and documentation structure remains separate from node structure.

## Operational Guidance

The framework is designed for controlled governance and internal use. Expansion should remain disciplined and maintain the distinction between node definitions and support documents.
