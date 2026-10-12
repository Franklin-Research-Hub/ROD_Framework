# Architecture

Retained legacy reference. The current architectural model is defined in [Foundation/architecture.md](../Foundation/architecture.md).

## Purpose

This document summarizes the current layered model of the `ROD_Framework` repository and the ROD Framework it contains.

## Repository Layers

### Repository root (not a layer)

The top-level repository contains legal, operational, and navigational files:

- `LICENSE.md`
- `README.md`
- `CONTRIBUTING.md`
- `NOTICE.md`

These are support documents and are not framework nodes.

### Layer 1 — Foundation

The `Foundation/` directory defines architecture, governance, metadata rules, validation criteria, and tree/branch structure.

### Layer 2 — Creator

The `Creator/` directory contains creator records and supporting documents. The current creator anchor is [Creator/0.00-creator.md](../Creator/0.00-creator.md).

### Retained legacy material

The `docs/` and `framework/` directories retain earlier reference material, validation records, and forms. They are not active documentation layers.

## Design Principles

- root authority is explicit
- metadata is machine-readable
- the node structure is hierarchical
- support materials remain distinct from framework nodes
- legal and operational guidance remain outside the node system

## Current Model

The active model is `Foundation/` (Layer 1) and `Creator/` (Layer 2), with Creator following the rules defined in Foundation.
