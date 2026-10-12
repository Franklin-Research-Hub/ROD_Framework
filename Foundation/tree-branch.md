# Foundation — Tree and Branch

## 1. Purpose
This document defines the tree and branch structure specifically for the Foundation layer (Layer 1).

For the canonical repository-wide master tree, full table of contents, and cross-layer definitions, see [MASTER-TREE-BRANCH.md](../MASTER-TREE-BRANCH.md).

## 2. Layer Tree: Foundation (Layer 1)
```text
Foundation/
├── README.md
├── architecture.md
├── governance.md
├── metadata-model.md
├── validation-references.md
└── tree-branch.md
```

## 3. Document Register
| Document | Responsibility |
|---|---|
| [README.md](README.md) | Layer overview and document register |
| [architecture.md](architecture.md) | Structural design and dependency model of the framework |
| [governance.md](governance.md) | Rules for change control and stewardship |
| [metadata-model.md](metadata-model.md) | Definitions for metadata and labeling |
| [validation-references.md](validation-references.md) | Criteria for checking consistency |
| [tree-branch.md](tree-branch.md) | Layer-specific tree and branch definition |

## 4. Layer Rules
- Foundation changes stay within `Foundation/`.
- Foundation defines the structural and metadata rules on which higher layers depend.
- Creator records belong to Layer 2 (`Creator/`) and are kept out of Foundation.

## 5. Maintenance
- Update this file whenever files in `Foundation/` are added, renamed, or deleted.
- When the Foundation structure changes, also update the master tree and table of contents in [MASTER-TREE-BRANCH.md](../MASTER-TREE-BRANCH.md).
