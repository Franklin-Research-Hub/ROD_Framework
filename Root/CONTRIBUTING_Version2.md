# Contributing

Thank you for contributing to `ROD_Framework`.

This repository is a governed documentation framework under active development. Contributions should preserve structure, terminology consistency, and branch ownership rules.

## 1. Purpose
This document defines the current contribution expectations for the repository.

## 2. Current Repository Structure
The repository currently uses the following branch folders:
- `Foundation/`
- `Creator/`

Repository-wide structure is defined by:
- [MASTER-TREE-BRANCH.md](MASTER-TREE-BRANCH.md)

Repository-wide terminology is defined by:
- [INDEX-METADATA-DEFINITIONS.md](INDEX-METADATA-DEFINITIONS.md)

## 3. Contribution Principles
Contributions should:
- preserve branch ownership
- preserve metadata consistency
- preserve internal links
- avoid duplicating repository-wide structure across local branch documents
- remain aligned with the current working framework baseline

## 4. Branch Rules

### Foundation
Use `Foundation/` for:
- structural rules
- governance guidance
- metadata model guidance
- validation references
- branch tree definition

### Creator
Use `Creator/` for:
- creator branch overview
- creator branch indexing
- creator application context
- creator-owned records

## 5. File Placement Rules
Before adding or editing files:
1. confirm the correct branch
2. update branch-local navigation where required
3. update the master tree if repository structure changes
4. update an index node if a tracked record is added or changed

## 6. Numbering Rule
Section numbering is local to each document.

Each structured document should begin at Section 1 and continue sequentially to its own final section. Section numbers indicate document order only and do not represent framework layer identity, node identity, or metadata class.

## 7. Record and Index Rule
Creator records should remain attached to the `Creator/` branch and should be managed through:
- [Creator/INDEX.md](Creator/INDEX.md)

Index nodes must remain in their owning branch and should be kept current when branch-owned records change.

## 8. Review Guidance
Before submitting changes, verify:
- links resolve correctly
- branch placement is correct
- terminology is consistent
- tree/list updates match `MASTER-TREE-BRANCH.md`
- updates do not conflict with branch ownership rules

## 9. Contribution Status
These contribution rules reflect the repository’s current working structure and may be refined as the framework matures.