# Architecture

## 1. Purpose
This document explains the working layer boundaries under the [canonical master structure](../MASTER-TREE-BRANCH.md). It does not define a competing repository tree.

## 2. Architectural Model
| Layer | Folder | Role |
|---|---|---|
| 1 | `Foundation/` | Structural, governance, metadata, and validation rules |
| 2 | `Creator/` | Indexed creator records, attribution, and application |

The repository root contains cross-repository support documents and is not a numbered layer.

## 3. Design Principles
1. Preserve each branch's declared responsibility and ownership.
2. Separate entry, index, tree, application, and record roles.
3. Keep creator metadata in Creator records; Foundation defines the rules that govern it.
4. Document and approve structural extensions before adoption.
5. Treat local section numbers as document order, not architectural identity.

## 4. Dependency Direction
`Creator/` → `Foundation/`

Creator applies Foundation rules. Foundation does not depend on Creator for structural validity.

## 5. Reference Boundaries
The master tree governs repo-wide navigation. Local trees describe only their owning branch. [Creator/INDEX.md](../Creator/INDEX.md) registers creator records omitted from repo-wide navigation.

The Creator anchor `0.00` is a record identifier, not a layer, section number, or version. Use the [metadata model](metadata-model.md) for labeling.

## 6. Status
Active-working architectural baseline. New branches or layers require [controlled governance](governance.md) and synchronized master navigation.
