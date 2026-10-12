# Architecture

## 1. Purpose
This document defines the architecture of the framework at the Foundation layer.

## 2. Architectural Model
The repository follows a layered model:

| Layer | Folder | Role |
|---|---|---|
| 1 | `Foundation/` | System rules, structure, governance, metadata, validation |
| 2 | `Creator/` | Indexed creator records and anchor `0.00`, including creator metadata |

## 3. Design Principles
1. Each layer has a single, clearly stated responsibility.
2. Higher layers depend on lower layers, never the reverse.
3. Creator records are kept out of the Foundation layer, but the rules that govern them are defined here.
4. Structure is documented before it is extended.

## 4. Dependency Direction
`Creator/` -> `Foundation/`

Foundation defines the structure that the Creator layer follows.

## 5. Metadata Inclusion Rule
Creator metadata may include:
- creator identity
- biography
- portfolio references
- extended profile material

## 6. Summary
Foundation architecture is the stable structural base of the repository.
