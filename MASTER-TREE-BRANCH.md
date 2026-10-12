# ROD Framework — Master Tree and Branch Document

## 1. Purpose
This document is the canonical structural authority for `Franklin-Research-Hub/ROD_Framework`. It defines the current working navigation baseline, not an exhaustive physical inventory or permanently final architecture.

“Tree” means documentation structure; “branch” means an owning documentation folder, not a Git branch. Local section numbers express document order only, not framework node identity.

## 2. Structural Principles
1. The repository root is the top-level container, not a numbered layer.
2. Each layer has an owning branch folder.
3. Entry, index, tree, application, and record documents have distinct responsibilities.
4. Index nodes stay inside their owning branch and register its records.
5. Records remain branch-owned and are reached through their index.
6. Other navigation and tree documents follow this authority within their stated scope.

## 3. Repository Root
Root documents provide repository entry, structure, navigation, contribution rules, definitions, notice, and licensing. They are not creator records or numbered layers.

Older files outside the current master structure are outside this navigation baseline. Their physical presence does not establish current structural authority.

## 4. Master Structure Overview
| Level | Name | Location | Role |
|---|---|---|---|
| Root | Repository Root | `/` | Repository-wide container and supporting documents |
| Layer 1 | Foundation | `Foundation/` | Structural, governance, metadata, and validation rules |
| Layer 2 | Creator | `Creator/` | Creator records, indexing, attribution, and application |

## 5. Master Table of Contents
### Repository Root
- [README.md](README.md)
- [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)
- [TABLE-OF-CONTENTS.md](TABLE-OF-CONTENTS.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [INDEX-METADATA-DEFINITIONS.md](INDEX-METADATA-DEFINITIONS.md)
- [NOTICE.md](NOTICE.md)
- [LICENSE.md](LICENSE.md)

### Foundation
- [Foundation/README.md](Foundation/README.md)
- [Foundation/architecture.md](Foundation/architecture.md)
- [Foundation/governance.md](Foundation/governance.md)
- [Foundation/metadata-model.md](Foundation/metadata-model.md)
- [Foundation/validation-references.md](Foundation/validation-references.md)
- [Foundation/tree-branch.md](Foundation/tree-branch.md)

### Creator — 0.00 Anchor
- [Creator/README.md](Creator/README.md)
- [Creator/INDEX.md](Creator/INDEX.md)
- [Creator/website-application.md](Creator/website-application.md)
- [Creator/tree-branch.md](Creator/tree-branch.md)

## 6. Master Tree
This raw tree shows current repository-wide structural navigation. Branch-owned records are registered locally, not enumerated here.

```text
ROD_Framework/
├── README.md
├── MASTER-TREE-BRANCH.md
├── TABLE-OF-CONTENTS.md
├── CONTRIBUTING.md
├── INDEX-METADATA-DEFINITIONS.md
├── NOTICE.md
├── LICENSE.md
├── Foundation/
│   ├── README.md
│   ├── architecture.md
│   ├── governance.md
│   ├── metadata-model.md
│   ├── validation-references.md
│   └── tree-branch.md
└── Creator/
    ├── README.md
    ├── INDEX.md
    ├── website-application.md
    └── tree-branch.md
```

## 7. Branch Register
| Branch | Layer | Entry | Index | Local Tree |
|---|---|---|---|---|
| Foundation | 1 | [README](Foundation/README.md) | No record index in the current baseline | [Tree](Foundation/tree-branch.md) |
| Creator | 2 | [README](Creator/README.md) | [INDEX](Creator/INDEX.md) | [Tree](Creator/tree-branch.md) |

## 8. Index Node Rule
An index node is the authoritative register for records within its branch. It identifies registered records and preserves branch-to-record links without duplicating record content.

Update the owning index when records are added, renamed, moved, or removed. Additional index nodes require documented scope and branch ownership.

## 9. Creator Branch Reference Rule
Creator record navigation follows:

`Creator/` → `Creator/README.md` → `Creator/INDEX.md` → creator record(s)

Repository-wide references to creator records resolve through [Creator/INDEX.md](Creator/INDEX.md). The `0.00` anchor remains a branch-owned record identifier; displaying it in a branch heading does not add a record to the master tree.

## 10. Dependency Direction
`Creator/` → `Foundation/`

Foundation defines structural rules; Creator applies them. Foundation does not depend on Creator for structural validity.

## 11. Canonical Navigation Path
1. [README.md](README.md)
2. [TABLE-OF-CONTENTS.md](TABLE-OF-CONTENTS.md)
3. [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)
4. [Foundation/README.md](Foundation/README.md)
5. [Creator/README.md](Creator/README.md)
6. [Creator/INDEX.md](Creator/INDEX.md)

## 12. Maintenance Rules
- Add files to the correct branch; update its entry, local tree, and index as applicable.
- For renames, moves, and deletions, update affected links and registers; preserve unique content before removal.
- Update this document and the TOC together when repository-wide navigation changes.
- Record-only changes remain local unless they change the master structure.
- Proposals for new layers must document layer number, folder, role, dependency direction, entry node, and index strategy.
- Obtain approval under [Foundation governance](Foundation/governance.md) before adopting structural changes.

## 13. Canonical Record Handling
Canonical records remain branch-owned. A local branch tree may enumerate its records even when this repository-wide navigation tree does not. This is an intentional scope difference, not permission to invent a competing master structure.

## 14. Non-Duplication Rule
- Root README provides entry, not a competing structural definition.
- TOC reproduces the current master navigation list and order.
- Branch READMEs and trees describe local scope only.
- Indexes register records; record files contain authoritative record content.
- Foundation rules do not duplicate creator identity metadata.

## 15. Document Status
Active-working structural baseline: Repository Root, Foundation (Layer 1), and Creator (Layer 2), with the Creator index at `Creator/INDEX.md`.

Revise through controlled change whenever branch structure, index strategy, or canonical navigation changes.
