# Index and Metadata Definitions

Created by: Victoria Love Franklin  
Source: `Creator/0.00-creator.md`  
Version: 1.0.0

## 1. Purpose
This document defines the current working structural, index, and metadata terminology used across the `ROD_Framework` repository.

It serves as the active terminology reference for consistency while the framework architecture is still being developed and refined.

This document is a working definitions document. It establishes the current baseline vocabulary for the repository and may expand as new branches, records, metadata fields, governance structures, and implementation patterns are introduced.

For repository-wide structure, see:
- [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)

For metadata rules and implementation logic, see:
- [Foundation/metadata-model.md](Foundation/metadata-model.md)

## 2. Structural Definitions

### Repository Root
The top-level container of the repository.

It contains repository-wide documents, legal files, navigation files, and documentation branches.

### Tree
The structural layout of the repository and its organized files, branches, records, and supporting documents.

### Branch
A defined documentation layer or structural branch within the repository.

Current branches:
- `Foundation/`
- `Creator/`

Additional branches may be introduced later as the framework expands.

### Layer
A numbered structural level represented by an owning branch.

Current examples:
- Layer 1 = `Foundation/`
- Layer 2 = `Creator/`

### Entry Document
A branch-level entry file used to introduce and summarize a branch.

Current examples:
- `Foundation/README.md`
- `Creator/README.md`

### Tree Document
A file that defines the branch-local tree for a branch.

Current examples:
- `Foundation/tree-branch.md`
- `Creator/tree-branch.md`

### Index Node
An authoritative register that identifies records within an owning branch.

Current example:
- `Creator/INDEX.md`

Additional index nodes may be introduced later if needed.

### Record Node
A file containing the canonical content of a structural record or branch-owned item.

Current example:
- `Creator/0.00-creator.md`

### Canonical Record
The authoritative version of a record within a branch or structural context.

## 3. Branch Relationship Definitions

### Branch Ownership
The rule that records, index nodes, and branch-local documents remain attached to their owning branch.

### Branch Context
The structural meaning created by keeping a file within its correct branch relationship.

### Reference Chain
The ordered path that preserves branch context and record ownership.

Current creator reference chain:
`Creator/` → `Creator/README.md` → `Creator/INDEX.md` → `Creator/0.00-creator.md`

### Dependency Direction
The directional relationship showing that one branch relies on another for structural authority.

Current example:
`Creator/` → `Foundation/`

## 4. Metadata Definitions

### Metadata
Structured descriptive information used to define identity, role, ownership, status, relationship, and meaning.

### Metadata Model
The rule system that defines how metadata should be structured and interpreted.

### Metadata Field
A named descriptive property attached to a record, branch, or framework item.

### Metadata Value
The assigned content of a metadata field.

### Metadata Consistency
The condition in which metadata terms, field meanings, and usage remain aligned across repository documents.

## 5. Metadata Field Definitions

### `name`
The human-readable name of the item being described.

### `role`
The functional identity or responsibility assigned to the item.

### `layer`
The numbered structural level to which the branch or item belongs.

### `branch`
The owning branch associated with a record or document.

### `authority`
The level or source of decision-making control attached to the item.

### `owner`
The person or entity that controls the item or repository.

### `source`
The originating record, document, or authority from which the item derives.

### `status`
The current lifecycle condition of the item.

### `version`
The declared version of the item or document.

### `created`
The original creation date of the item.

### `modified`
The most recent update date of the item.

### `index`
A field or concept used to identify ordered registration within a branch or record system.

### `record`
A structural content item documented within the repository.

### `type`
The classification assigned to an item, such as branch document, index node, or record node.

### `scope`
The structural boundary that defines what a document or record is responsible for covering.

### `relationship`
A defined connection between items, branches, documents, or records.

### `parent`
A structurally higher item to which another item belongs or reports.

### `child`
A structurally subordinate item attached to a parent item.

### `reference`
A document, record, or structural pointer used to preserve context and traceability.

Additional metadata fields may be introduced as the framework evolves.

## 6. Governance and Control Definitions

### Governance
The rules and authority model that control structure, stewardship, updates, and change.

### Structural Authority
The document or branch that defines repository-wide structure.

Current structural authority:
- `MASTER-TREE-BRANCH.md`

### Root Authority
The highest ownership or creator authority associated with the repository and framework.

### Creator Authority
The creator-linked authority recognized through the Creator branch and canonical creator record.

### Change Control
The rules governing how repository documents, branch structures, and records may be updated.

### Validation
The process of checking that files, metadata, references, and branch logic remain consistent.

## 7. Classification Definitions

### Root Document
A repository-wide file located at the repository root.

Current examples:
- `README.md`
- `MASTER-TREE-BRANCH.md`
- `TABLE-OF-CONTENTS.md`
- `CONTRIBUTING.md`
- `INDEX-METADATA-DEFINITIONS.md`
- `NOTICE.md`
- `LICENSE.md`

### Branch Document
A file that belongs to and describes a specific branch.

### Supporting Document
A document that assists interpretation, application, governance, or navigation without serving as the canonical record node.

### Application Document
A branch-owned document that explains how branch content is applied in a specific use context.

Current example:
- `Creator/website-application.md`

Additional document classes may be introduced later if needed.

## 8. Lifecycle Definitions

### Active
Currently in effect and part of the working repository structure.

### Draft
Present but not yet treated as finalized authority.

### Canonical
Recognized as the authoritative version within its defined scope.

### Deprecated
Retained for historical reference but no longer used as the active authority.

## 9. Usage Rules

### Non-Duplication Rule
Repository-wide structure should not be duplicated across branch-local files.

### Branch Attachment Rule
Records should remain attached to their owning branch and index structure.

### Index Rule
An index node must remain inside its owning branch.

### Canonical Reference Rule
Canonical records should be referenced through their branch and index relationships wherever possible.

## 10. Structural Boundary
This file defines current terminology and metadata meanings.

It does not replace:
- repository-wide structure documentation
- branch tree documents
- branch-local overview documents
- canonical creator record content

Those responsibilities belong to:
- [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)
- [Foundation/tree-branch.md](Foundation/tree-branch.md)
- [Creator/tree-branch.md](Creator/tree-branch.md)
- [Foundation/README.md](Foundation/README.md)
- [Creator/README.md](Creator/README.md)
- [Creator/INDEX.md](Creator/INDEX.md)
- [Creator/0.00-creator.md](Creator/0.00-creator.md)

## 11. Document Status
Active working definitions document.

This file establishes the current baseline vocabulary for the framework and may expand as new branches, records, metadata fields, and governance structures are introduced.