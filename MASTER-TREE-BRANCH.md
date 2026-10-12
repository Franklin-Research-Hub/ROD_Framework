# ROD Framework — Master Tree and Branch Document

## 1. Purpose
This document defines the master tree and branch structure for the `ROD_Framework` repository.

In this framework, **tree** refers to the repository's structural layout and **branch** refers to a defined documentation branch or layer within that layout.

This document does **not** refer to Git branches. It refers to the framework's internal documentation structure and serves as the single canonical structural authority.

---

## 2. Structural Distinction (Root vs. Layer)
The repository root is the top-level container for all files and folders.

The root is **not** a numbered documentation layer. Repository-wide files at the root support the repository as a whole and provide entry points, legal terms, and repository-level guidance:
- `README.md`
- `CONTRIBUTING.md`
- `LICENSE.md`
- `NOTICE.md`
- `MASTER-TREE-BRANCH.md`

Documentation layers are structured directories within the repository that carry defined architectural roles:
- `Foundation/` — Layer 1
- `Creator/` — Layer 2

---

## 3. Master Structure Overview

| Level | Name | Location | Role |
|---|---|---|---|
| Root | Repository Root | `/` | Top-level container, entry point, legal, and repository-wide guidance |
| Layer 1 | Foundation | `Foundation/` | Structural rules, architecture, governance, metadata model, validation, and layer definitions |
| Layer 2 | Creator | `Creator/` | Creator identity, attribution, canonical creator records, and website application |

---

## 4. Master Table of Contents

### Repository Root
- [README.md](README.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [LICENSE.md](LICENSE.md)
- [NOTICE.md](NOTICE.md)
- [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)

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

---

## 5. Master Tree

```text
ROD_Framework/
├── README.md
├── CONTRIBUTING.md
├── LICENSE.md
├── NOTICE.md
├── MASTER-TREE-BRANCH.md
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
    ├── 0.00-creator.md
    ├── website-application.md
    └── tree-branch.md
```

---

## 6. Layer and Branch Register

### 6.1 Foundation Branch
- **Location:** `Foundation/`
- **Layer:** 1
- **Role:** Defines structural rules, system architecture, governance, metadata model, validation references, and layer definitions. Foundation establishes the rules that higher layers follow.

### 6.2 Creator Branch
- **Location:** `Creator/`
- **Layer:** 2
- **Role:** Defines creator identity, attribution structure, creator-facing records, and website application.
- **Canonical Creator Anchor:** [Creator/0.00-creator.md](Creator/0.00-creator.md)

---

## 7. Dependency Direction

The dependency direction is strictly:

`Creator/` → `Foundation/`

- The Creator layer depends on the Foundation layer.
- The Foundation layer defines structural and metadata rules.
- The Creator layer applies and implements those rules.
- Foundation never depends on Creator for structural validity.

---

## 8. Canonical Navigation Flow
To maintain consistency and eliminate duplication, navigation flows through designated entry points:

1. [README.md](README.md) — Repository front door and orientation
2. [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md) — Canonical structural authority, full master tree, and repository-wide table of contents
3. [Foundation/README.md](Foundation/README.md) — Layer 1 entry point and document register
4. [Creator/README.md](Creator/README.md) — Layer 2 entry point and document register
5. [Creator/INDEX.md](Creator/INDEX.md) — Register of creator records

---

## 9. Layer Responsibility & Governance Rule
Each layer must remain within its defined architectural scope:
- Root files provide repository-wide guidance and structural mapping.
- `Foundation/` defines structural rules, governance, and validation criteria.
- `Creator/` holds creator records, attribution, and implementation guidance.

No layer document should duplicate the full repository tree or table of contents; cross-layer structural mappings belong exclusively in this document.

---

## 10. Maintenance and Extension Rules
As the framework expands, follow these rules to keep documentation clean and avoid duplication:

### Adding New Files
- Place the file in the appropriate layer directory.
- Register the file in the layer's local `README.md` (or `INDEX.md` for creator records).
- Add the file entry to Section 4 (Master Table of Contents) and Section 5 (Master Tree) of this document.
- Update the layer's local `tree-branch.md`.

### Renaming or Moving Files
- Update all relative links within the affected documents.
- Update the entry in this document's Master Table of Contents and Master Tree.
- Update the relevant layer's `tree-branch.md` and document register.

### Deleting Files
- Remove links to deleted files across all documents.
- Remove entries from this document and the relevant layer's `tree-branch.md`.
- Preserve any unique content or historical context before removal.

### Adding New Layers
- Document the new layer in this document before adding files:
  - Layer number and name
  - Folder location
  - Architectural role and boundaries
  - Dependency direction relative to existing layers
  - Entry-point document

---

## 11. Relationship to Creator Record
This master document defines framework structure and does not duplicate creator metadata.

The canonical creator anchor record remains:
- [Creator/0.00-creator.md](Creator/0.00-creator.md)

---

## 12. Ownership and Status
- **Ownership:** Proprietary and controlled by Victoria Love Franklin.
- **Status:** Active
- **Version:** 1.0.0
