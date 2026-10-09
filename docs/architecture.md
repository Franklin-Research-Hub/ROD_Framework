# Architecture

## Purpose

This document defines the architectural model of the repository and the framework it contains.

## Repository Layers

### 1. Root support layer

The top-level repository contains legal, operational, and navigational files:

- `LICENSE`
- `README.md`
- `CONTRIBUTING.md`
- `NOTICE.md`

These are support documents and are not framework nodes.

### 2. Framework node layer

The `framework/` directory contains the canonical metadata-driven node system. Each file in this folder represents a formal framework node and follows a structured metadata schema.

Current root node:

- `framework/0.00-creator.md`

### 3. Documentation layer

The `docs/` directory contains reference material for implementation and operational understanding. These files support the framework but are not node records.

## Design Principles

- root authority is explicit
- metadata is machine-readable
- the node structure is hierarchical
- support materials remain distinct from framework nodes
- legal and operational guidance remain outside the node system

## Current Model

The repository is intentionally minimal and structured around a root creator node and supporting documentation only.
