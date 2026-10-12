# ROD Framework — Master Tree and Branch Document

## 1. Purpose
This document is the canonical structural map for the `ROD_Framework` repository.

In this framework:
- **tree** means the repository’s structural layout
- **branch** means a defined documentation branch or layer within that layout
- **index node** means the authoritative register or navigation node for records within a branch

This document does **not** refer to Git branches. It refers to the framework’s internal documentation structure.

## 2. Structural Principles
1. The repository root is the top-level container for all files and folders.
2. The root is **not** a numbered documentation layer.
3. Each layer is represented by an owning branch folder.
4. Each branch may contain entry documents, index nodes, tree documents, and record nodes.
5. Index nodes remain inside their owning branch.
6. Records remain attached to their owning branch through that branch’s index node.
7. Creator-related references must always follow the `Creator/` branch and resolve through `Creator/INDEX.md`.

## 3. Repository Root
The repository root contains repository-wide materials such as:
- navigation documents
- legal and notice files
- contribution files
- documentation branches

Root files support the repository as a whole and are not themselves layers unless explicitly defined as such.

## 4. Master Structure Overview

| Level | Name | Location | Role |
|---|---|---|---|
| Root | Repository Root | `/` | Top-level container for all repository materials |
| Layer 1 | Foundation | `Foundation/` | Structural rules, governance, metadata model, validation, and tree definition |
| Layer 2 | Creator | `Creator/` | Creator identity, attribution, creator record, and website application |

## 5. Master Table of Contents

### Repository Root
- [README.md](README.md)
- [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [NOTICE.md](NOTICE.md)
- [LICENSE](LICENSE)

### Layer 1 — Foundation
- [Foundation/README.md](Foundation/README.md)
- [Foundation/architecture.md](Foundation/architecture.md)
- [Foundation/governance.md](Foundation/governance.md)
- [Foundation/metadata-model.md](Foundation/metadata-model.md)
- [Foundation/validation-references.md](Foundation/validation-references.md)
- [Foundation/tree-branch.md](Foundation/tree-branch.md)

### Layer 2 — Creator
- [Creator/README.md](Creator/README.md)
- [Creator/INDEX.md](Creator/INDEX.md)
- [Creator/0.00-creator.md](Creator/0.00-creator.md)
- [Creator/website-application.md](Creator/website-application.md)
- [Creator/tree-branch.md](Creator/tree-branch.md)

## 6. Master Tree

```text
ROD_Framework/
├── README.md
├── MASTER-TREE-BRANCH.md
├── CONTRIBUTING.md
├── NOTICE.md
├── LICENSE
├── Foundation/                              <- Layer 1 branch
│   ├── README.md                            <- branch entry
│   ├── architecture.md
│   ├── governance.md
│   ├── metadata-model.md
│   ├── validation-references.md
│   └── tree-branch.md                       <- local branch tree node
└── Creator/                                 <- Layer 2 branch, anchor 0.00
    ├── README.md                            <- branch entry
    ├── INDEX.md                             <- branch index node
    ├── 0.00-creator.md                      <- canonical creator record node
    ├── website-application.md
    └── tree-branch.md                       <- local branch tree node
```

## 7. Branch Register

### Foundation Branch
- **Layer:** 1
- **Location:** `Foundation/`
- **Role:** Defines structural and governance rules for the framework
- **Entry Node:** [Foundation/README.md](Foundation/README.md)
- **Tree Node:** [Foundation/tree-branch.md](Foundation/tree-branch.md)

### Creator Branch
- **Layer:** 2
- **Location:** `Creator/`
- **Role:** Defines creator-layer records and application
- **Entry Node:** [Creator/README.md](Creator/README.md)
- **Index Node:** [Creator/INDEX.md](Creator/INDEX.md)
- **Canonical Record Node:** [Creator/0.00-creator.md](Creator/0.00-creator.md)
- **Tree Node:** [Creator/tree-branch.md](Creator/tree-branch.md)

## 8. Index Node Rule
An index node is the authoritative register for records within a branch.

Index nodes must:
- remain inside their owning branch
- identify the records they govern
- preserve branch-to-record relationships
- be updated when records are added, renamed, moved, or removed

A branch may have one or more index nodes if needed, but each index node must remain structurally attached to its branch.

## 9. Creator Branch Reference Rule
All creator-related records, references, and navigation paths must remain attached to the `Creator/` branch.

Wherever creator records are referenced in repository documentation, the documentation should preserve the relationship to the Creator branch index node:

- [Creator/INDEX.md](Creator/INDEX.md)

This means creator references should not appear as isolated record references without branch context unless the branch relationship is already explicitly established nearby.

The canonical creator branch reference chain is:

`Creator/` → `Creator/README.md` → `Creator/INDEX.md` → `Creator/0.00-creator.md`

## 10. Dependency Direction

`Creator/` → `Foundation/`

This means:
- the Creator branch depends on the Foundation branch
- the Foundation branch defines structural rules
- the Creator branch applies those rules

Foundation does not depend on Creator for structural validity.

## 11. Canonical Navigation Path
Repository navigation should follow this order:

1. [README.md](README.md)
2. [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)
3. [Foundation/README.md](Foundation/README.md)
4. [Creator/README.md](Creator/README.md)
5. [Creator/INDEX.md](Creator/INDEX.md)
6. [Creator/0.00-creator.md](Creator/0.00-creator.md)

This preserves branch ownership, index-node logic, and clean navigation across layers.

## 12. Maintenance Rules

### Additions
- add new files to the correct branch
- update the branch entry or index node as appropriate
- update this master document when branch structure changes
- do not add creator records without updating `Creator/INDEX.md`

### Renames
- update links
- update branch tree documents
- update affected index nodes
- update this master document

### Moves
- preserve branch ownership rules
- if a record changes branch, update both the old and new branch structures
- ensure the receiving branch has the correct index-node registration

### Deletions
- remove obsolete links
- preserve unique content before removal
- update affected branch tree documents
- remove deleted records from their branch index nodes

### New Layers or Branches
Do not introduce a new layer or branch without documenting:
- layer number
- branch folder name
- role
- dependency direction
- canonical entry node
- index node strategy, if records are tracked within the branch

## 13. Canonical Record Note
The canonical creator record is:
- [Creator/0.00-creator.md](Creator/0.00-creator.md)

That record should be referenced through the Creator branch and its index node rather than treated as a detached standalone file.

## 14. Non-Duplication Rule
This document is the canonical repository-wide structural authority.

Therefore:
- `README.md` should remain a repository entry document only
- layer-specific README and tree documents should describe only their local branch scope
- record files should contain record content, not repository-wide structure definitions
- index nodes should register records rather than duplicate their content

## 15. Status
Current documented structure:
- Repository Root
- Foundation Branch (Layer 1)
- Creator Branch (Layer 2)

Current documented index-node structure:
- Creator Index Node at `Creator/INDEX.md`

This document should be updated whenever branch structure, index-node structure, or canonical navigation changes.
