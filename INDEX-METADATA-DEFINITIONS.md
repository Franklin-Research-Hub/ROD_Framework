# Working Index and Metadata Definitions

## 1. Purpose and Status
This document defines current terminology for `Franklin-Research-Hub/ROD_Framework`, a proprietary framework archive under active development. These are working definitions, not a closed or permanently final vocabulary.

The [master tree](MASTER-TREE-BRANCH.md) governs structure. [Foundation metadata guidance](Foundation/metadata-model.md) applies these definitions; this document does not create additional layers or records.

## 2. Structural Terms
| Term | Working Definition |
|---|---|
| Repository root | Top-level container for repository-wide documents and branch folders; not a numbered layer |
| Tree | Declared documentation structure within a stated scope |
| Master tree | Canonical repository-wide structural navigation baseline, not an exhaustive physical inventory |
| Branch | Owning documentation folder with a defined role; not a Git branch |
| Layer | Architectural position assigned to a branch by the master tree |
| Dependency | Direction in which one branch applies another's rules; currently Creator → Foundation |
| Section number | Local document-order label beginning at 1; never a framework node identifier |

## 3. Branch and Node Terms
| Term | Working Definition |
|---|---|
| Entry document | Branch or repository overview, normally a README |
| Index node | Branch-owned authoritative register linking its records, currently `Creator/INDEX.md` |
| Tree node | Local structural description subordinate to the master tree |
| Record node | Branch-owned file containing the authoritative content of a registered record |
| Canonical record | Designated source record for its subject, reached through the owning index |
| Application document | Guidance for applying record content without replacing its authority |
| Anchor identifier | Stable reference label for a record; `0.00` is the current Creator anchor |

An identifier is not an index file, layer number, decimal calculation, or version. No general hierarchy or `.00` suffix rule is implied by the current anchor.

## 4. Classification Terms
Root documents serve entry, structural authority, navigation, contribution, definitions, notice, or licensing roles. Foundation documents define Layer 1 rules. Creator documents serve Layer 2 entry, indexing, record, application, and local-tree roles.

Classify by declared responsibility and ownership, not by numbering or filename alone. A record is not a repository-wide structural authority. Older materials outside the master baseline do not define the current classification model.

## 5. Metadata Terms
Metadata describes a document or record and its relationships. Current fields may be expressed in Markdown prose, lists, or tables; no executable or machine-readable schema is mandated.

| Field | Meaning |
|---|---|
| Identifier | Record anchor, distinct from version and section numbering |
| Name | Human-readable document or record name |
| Definition / purpose | What the item represents |
| Role | Declared responsibility or classification |
| Branch / layer | Owning folder and architectural position |
| Parent / children | Explicit ownership or registered record relationships, when applicable |
| Linked to | Related references; a link alone does not establish ownership or authority |
| Authority | Documented source or approval responsibility |
| Status | Lifecycle state of the item |
| Version | Separately declared revision label, if tracked; never inferred from `0.00` |
| Created / modified | Documented dates, when known; do not invent them |
| Repository | Repository context: `Franklin-Research-Hub/ROD_Framework` |

Creator metadata may include approved biography, portfolio references, extended profile material, and attribution. Such content remains in the Creator branch rather than being copied into Foundation rules.

## 6. Governance Terms
- **Owner / creator authority:** Victoria Love Franklin's control of the proprietary framework and approval of governed changes.
- **Structural authority:** The master tree's role in defining current repository structure, distinct from personal approval authority.
- **Stewardship:** Maintaining documents within their scope; it does not transfer ownership.
- **Controlled change:** A reviewed, authorized revision that updates affected dependencies and navigation.
- **Approval:** Explicit authorization by the owner or documented delegate; neither a metadata label nor a proposed change grants it.

## 7. Lifecycle Terms
| Term | Meaning |
|---|---|
| Proposed / draft | Under review; not yet adopted as an approved baseline |
| Active-working | In current use while subject to development and controlled revision |
| Baseline | Current documented reference point, not a promise of finality |
| Deprecated | Retained for context but no longer recommended for current use |
| Archived | Retained historical material outside active use |

Canonical authority and lifecycle are separate: a canonical record can remain active-working. Status does not confer licensing rights.

## 8. Usage Rules
- Follow the master tree for repo-wide navigation and local trees for branch detail.
- Reach creator records through [Creator/INDEX.md](Creator/INDEX.md); do not add branch-only records to the repo-wide TOC.
- Preserve canonical links instead of duplicating authoritative record content.
- Use local, consecutive section numbers independently in every structured document.
- Keep identifiers, layers, versions, and section numbers distinct.
- Apply [governance](Foundation/governance.md), [contribution rules](CONTRIBUTING.md), and [licensing restrictions](LICENSE.md).

## 9. Controlled Expansion
New terms, fields, classifications, indexes, or layers may be proposed as the framework develops. Document their purpose, owner, relationships, and compatibility with existing definitions; obtain approval before adopting them.

Update affected definitions, Foundation guidance, branch indexes and trees, and master navigation as applicable. Do not treat speculative future structures, optional metadata formats, or skills cards as established requirements.
