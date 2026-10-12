# Tree and Branch

## 1. Purpose
This document is the authoritative tree and branch definition for the Foundation layer.

## 2. Raw Tree: Foundation (Layer 1)
```text
Foundation/
├── README.md
├── architecture.md
├── governance.md
├── metadata-model.md
├── index-metadata-definitions.md
├── validation-references.md
└── tree-branch.md
```

## 3. Raw Tree: Full Repository
```text
ROD_Framework/
├── LICENSE.md
├── README.md
├── CONTRIBUTING.md
├── NOTICE.md
├── Foundation/                      <- Layer 1
│   ├── README.md
│   ├── architecture.md
│   ├── governance.md
│   ├── metadata-model.md
│   ├── index-metadata-definitions.md
│   ├── validation-references.md
│   └── tree-branch.md
└── Creator/                         <- Layer 2
    ├── README.md
    ├── INDEX.md
    ├── 0.00-creator.md
    ├── 0.1.00-documentation-index.md
    ├── website-application.md
    ├── tree-branch.md
    ├── approvals/
    ├── forms/
    │   └── WORD-READY-CONTENT/
    └── validation/
```

Creator subdirectory filenames are collapsed here. Their inventories are maintained in the Creator layer's tree, index, and form source guide. Foundation has no content dependency on those applied records.

## 4. Branch Definitions
| Branch | Location | Contents |
|---|---|---|
| Foundation | `Foundation/` | Layer 1 documents |
| Creator | `Creator/` | Layer 2 creator records, biography and portfolio metadata, and applied approval/validation materials |

## 5. Branch Rules
- Foundation changes stay in `Foundation/`.
- Creator record changes stay in `Creator/`.
- Creator metadata may include biography and portfolio references.

## 6. Maintenance
Update this file whenever the Foundation tree changes.
