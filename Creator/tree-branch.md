# Creator — Tree and Branch

## 1. Purpose
This document defines the tree and branch structure specifically for the Creator layer (Layer 2).

For the canonical repository-wide master tree, full table of contents, and cross-layer definitions, see [MASTER-TREE-BRANCH.md](../MASTER-TREE-BRANCH.md).

## 2. Layer Tree: Creator (Layer 2)
```text
Creator/
├── README.md
├── INDEX.md
├── 0.00-creator.md
├── website-application.md
└── tree-branch.md
```

## 3. Document Register
| Document | Responsibility |
|---|---|
| [README.md](README.md) | Layer overview and document register |
| [INDEX.md](INDEX.md) | Register of creator-layer records |
| [0.00-creator.md](0.00-creator.md) | Foundational creator anchor record |
| [website-application.md](website-application.md) | Application of creator metadata to websites |
| [tree-branch.md](tree-branch.md) | Layer-specific tree and branch definition |

## 4. Creator Branch Scope
The Creator branch encompasses:
- Indexed creator records and canonical anchors (starting with [0.00-creator.md](0.00-creator.md))
- Creator attribution, biography, portfolio references, and profile material
- Website application guidance for presenting creator metadata

## 5. Relationship to Foundation
The Creator layer follows the architectural, governance, metadata, and validation rules defined in [Foundation/](../Foundation/README.md).
- Dependency direction: `Creator/` → `Foundation/`.

## 6. Maintenance
- Update this file whenever files in `Creator/` are added, renamed, or deleted.
- When the Creator structure changes, also update the master tree and table of contents in [MASTER-TREE-BRANCH.md](../MASTER-TREE-BRANCH.md).
