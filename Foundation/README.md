# Foundation (Layer 1)

## 1. Purpose
The Foundation layer is the base documentation layer of the `ROD_Framework` repository. It defines the structure, governance, metadata rules, validation references, and architectural principles on which all other layers depend.

For the repository-wide master tree and table of contents, see [MASTER-TREE-BRANCH.md](../MASTER-TREE-BRANCH.md).

## 2. Document Set
| Document | Responsibility |
|---|---|
| [README.md](README.md) | Layer overview and document register |
| [architecture.md](architecture.md) | Structural design and dependency model of the framework |
| [governance.md](governance.md) | Rules for change control and stewardship |
| [metadata-model.md](metadata-model.md) | Definitions for metadata and labeling |
| [validation-references.md](validation-references.md) | Criteria for checking consistency |
| [tree-branch.md](tree-branch.md) | Layer-specific tree and branch definition |

## 3. Layer Position & Dependency
- Layer 1: `Foundation/` (base layer)
- Higher layers (such as Layer 2 `Creator/`) depend on Foundation; Foundation does not depend on higher layers.
- See [MASTER-TREE-BRANCH.md](../MASTER-TREE-BRANCH.md) for the full repository layer hierarchy and navigation flow.

## 4. Boundary Statement
Foundation defines structure, governance, metadata rules, and validation logic. Creator records belong to Layer 2 (`Creator/`) and are governed by the rules defined here.

## 5. Status
Baseline established.
