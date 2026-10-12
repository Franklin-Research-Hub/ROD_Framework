# Metadata Model

## 1. Purpose
This document applies the [working index and metadata definitions](../INDEX-METADATA-DEFINITIONS.md) to branch documents and records. It is guidance, not a mandated executable schema.

## 2. Foundation-Level Metadata
Foundation documents communicate name, purpose, role, Layer 1 ownership, relationships, and working status through titles, sections, and links. A separate metadata block is not required.

## 3. Record Labels
Use the label pattern `identifier :: name — role` for registered records. The identifier names the record; a separately declared version tracks revisions if needed.

Creator labels and canonical links are maintained in [Creator/INDEX.md](../Creator/INDEX.md). `0.00` is an anchor identifier, not a version or section number.

## 4. Creator Metadata Rule
Creator records describe identifier, name, role, purpose, authority, branch/layer, repository context, relationships, and status. Optional metadata may include approved biography, portfolio references, extended profile material, revision version, and documented dates.

Do not invent missing values or duplicate creator metadata in Foundation documents. Application documents derive from the canonical record through its branch index.

## 5. Structural Rule
Parent, child, and related links must preserve branch ownership. A related link does not grant authority. Local section numbering begins at 1 independently in each document and does not encode record identity.

New fields or formats require controlled review and updates to affected definitions and consumers.

## 6. Status
Active-working metadata baseline, subject to [governed revision](governance.md).
