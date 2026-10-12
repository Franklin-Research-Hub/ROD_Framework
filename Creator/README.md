# Creator (Layer 2)

## 1. Purpose
The Creator layer is Layer 2 of the `ROD_Framework` repository. It contains creator-specific records and supporting documents that define creator identity, attribution, metadata inclusion, and website application.

## 2. Document Set
| Document | Responsibility |
|---|---|
| `README.md` | Layer overview and document register |
| `INDEX.md` | Index of creator-layer records |
| `0.00-creator.md` | Foundational creator anchor record |
| `0.1.00-documentation-index.md` | Metadata record for repository navigation |
| `website-application.md` | Website application of creator metadata |
| `tree-branch.md` | Raw tree and branch definition |
| `validation/` | Applied approval, routing, and external-validation records |
| `approvals/` | General proposal approval template |
| `forms/` | Preserved text sources and form usage guide |

## 3. Layer Role
The Creator layer provides:
- creator identity structure
- attribution structure
- creator metadata
- biography and portfolio inclusion
- website-facing creator application
- applied validation and approval materials for creator proposals

Institution-specific approval records are preserved as Creator application materials under Foundation rules, not as universal Foundation policy or a new documentation layer. Their recorded approvals and external policy assertions have not been independently revalidated by this cleanup.

For all records and templates, use the [Creator index](INDEX.md) and [form source guide](forms/README.md).

## 4. Metadata Inclusion
Creator metadata may include:
- version
- creator name
- creator role
- biography
- portfolio reference
- extended profile material
- attribution statement
- creator-layer label

## 5. Relationship to Foundation
The Creator layer follows the architecture, governance, metadata, validation, and tree rules defined in `Foundation/`.

## 6. Status
Baseline creator layer established.

## 7. Canonical Records & Artifact Relationships

To eliminate duplicate sources of truth and maintain strict architectural boundaries:

1. **Canonical Creator Anchor**: `Creator/0.00-creator.md` is the sole canonical source of truth for creator identity, authority, and root metadata.
2. **Foundation / Creator Separation**: `Foundation/` (Layer 1) defines the rules, schemas, and governance model. Foundation files illustrate metadata fields with generic schemas without duplicating creator personal or biographical metadata.
3. **Canonical Policy & Form Nodes**: Documents in `Creator/validation/` (e.g., [0.V.6.00 Creator-Only Approval](validation/0.V.6.00-creator-only-terrell-approval.md), [0.V.9.00 Low-Risk Creator Approval Form](validation/0.V.9.00-low-risk-creator-approval-form.md)) are the canonical policy definitions and form specifications.
4. **General Approval Template**: [Approval Form Template](approvals/approval-form-template.md) provides a generalized structural schema for designing approval forms across tiers, distinct from specific form instances.
5. **Derivative Export Artifacts**: Files in `Creator/forms/WORD-READY-CONTENT/` and legacy text sources are derivative export artifacts provided for word-processing convenience. They defer to their canonical validation nodes for governance and policy criteria.
