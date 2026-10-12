# ROD Framework

This repository defines the ROD Framework as a proprietary metadata-driven architecture rooted in the creator's authority and codified through a structured layered documentation model.

## Purpose

The repository exists to document, govern, and preserve a framework architecture that is:

- rooted in a named creator and source of truth
- designed to be machine-readable and AI-traceable
- structured as layered documentation with defined roles
- intended for controlled internal governance and implementation

## Repository Structure

This repository is organized in two distinct ways:

### 1. Repository Root
The repository root contains repository-wide files and top-level folders.

Examples:
- `LICENSE.md`
- `README.md`
- `CONTRIBUTING.md`
- `NOTICE.md`

These files support the repository as a whole and are not documentation layers.

### 2. Documentation Layers
Documentation layers are structured folders within the repository that carry defined architectural roles.

Current layers:
- `Foundation/` — Layer 1
- `Creator/` — Layer 2

### Structural Distinction
The repository root is the top-level container for all files and folders.  
A layer is a defined documentation folder within that container.

In this repository:
- the root is not a layer
- root files are not layers
- `Foundation/` and `Creator/` are layers

### Layer Summary
- `Foundation/` defines the structural, governance, metadata, validation, and tree rules of the framework.
- `Creator/` defines creator-layer records, creator metadata, biography and portfolio inclusion, website application, and applied approval and validation materials.

## Repository Tree

```text
ROD_Framework/
├── LICENSE.md
├── README.md
├── CONTRIBUTING.md
├── NOTICE.md
├── Foundation/                      # Layer 1: rules and definitions
└── Creator/                         # Layer 2: records and application materials
    ├── approvals/
    ├── forms/
    │   └── WORD-READY-CONTENT/
    └── validation/
```

This overview collapses document filenames within the layers. Use the [Foundation tree](Foundation/tree-branch.md), [Creator tree](Creator/tree-branch.md), [Creator index](Creator/INDEX.md), and [form source guide](Creator/forms/README.md) for their inventories.

## Documentation Layers

### Layer 1 — Foundation
- [Foundation/README.md](Foundation/README.md)
- [Foundation/architecture.md](Foundation/architecture.md)
- [Foundation/governance.md](Foundation/governance.md)
- [Foundation/metadata-model.md](Foundation/metadata-model.md)
- [Foundation/index-metadata-definitions.md](Foundation/index-metadata-definitions.md)
- [Foundation/validation-references.md](Foundation/validation-references.md)
- [Foundation/tree-branch.md](Foundation/tree-branch.md)

### Layer 2 — Creator
- [Creator/README.md](Creator/README.md)
- [Creator/INDEX.md](Creator/INDEX.md)
- [Creator/0.00-creator.md](Creator/0.00-creator.md)
- [Creator/0.1.00-documentation-index.md](Creator/0.1.00-documentation-index.md)
- [Creator/website-application.md](Creator/website-application.md)
- [Creator/tree-branch.md](Creator/tree-branch.md)
- [Creator/approvals/approval-form-template.md](Creator/approvals/approval-form-template.md)
- [Creator/forms/README.md](Creator/forms/README.md)

## Preserved Application Materials

The Creator index includes institution-specific approval and public-records validation records. These are preserved application materials, not new Foundation rules or independently verified policy claims.

Website application guidance and the creator portfolio reference remain because they describe attribution and provenance. No website source, deployment scripts, generated site artifacts, configuration, or tracked workflows are present. Form downloads are text sources; Word/PDF files must be created locally.

## Governance

The creator is the root authority of the framework. All downstream governance, metadata, documentation, and implementation structure derive from the defined layered model.

## Ownership

This repository and the framework it describes are proprietary and controlled by Victoria Love Franklin.

## Status

Status: Active  
Version: 1.0.0
