# Governance

## Governance Model

The governance model of the ROD Framework is centered on authority, provenance, and structured metadata.

## Root Authority

The root creator is the sole source of truth for the framework. All framework records, metadata definitions, and downstream governance decisions derive from this authority.

## Node Classification

Only files in the `framework/` directory are recognized as framework nodes.

Support files are classified as follows:

- `README.md` = portal
- `LICENSE` = legal notice
- `NOTICE.md` = ownership/legal notice
- `CONTRIBUTING.md` = operational guidance
- `docs/*.md` = supporting reference material

## Governance Rules

1. The root node remains authoritative.
2. Framework nodes are defined only in `framework/`.
3. Support docs are not part of the node system.
4. Metadata changes require review against the root framework definition.
5. Legal and documentation structure remains separate from node structure.

## Operational Guidance

The framework is designed for controlled governance and internal use. Expansion should remain disciplined and maintain the distinction between node definitions and support documents.
