# ROD Framework - Index & Metadata Definitions
Created by: Victoria Love Franklin
Source: 0.00
Date: 2026-10-05
Version: 1.0.0

═══════════════════════════════════════════════════════════════

REPOSITORY STRUCTURE & NODE CLASSIFICATION

Foundation/ (Layer 1) defines structural and metadata rules. Creator/ (Layer 2) contains indexed creator records and their applied approval and validation materials.

Top-level repo files are support documents, not framework nodes:
- README.md = portal and navigation, not a node
- LICENSE.md = legal text, not a node
- NOTICE.md = legal/ownership text, not a node
- CONTRIBUTING.md = operational guidance, not a node

Foundation documents are rules and supporting references, not creator records:
- architecture.md = layered architectural model
- governance.md = change control and authority rules
- metadata-model.md = metadata and label rules
- validation-references.md = structural validation criteria

Best practice:
- root of repo = navigation and legal files
- Foundation/ = foundational rules and non-node reference material
- Creator/ = indexed creator records and supporting application material

Only explicitly indexed metadata records are nodes; location alone does not make a README, form source, or other support document a node.

═══════════════════════════════════════════════════════════════

CORE CONCEPTS

Index Node
  - A unique identifier in decimal notation (0.00, 0.1.00, 0.2.00, etc.)
  - Represents a category, concept, or structural element
  - The .00 suffix denotes a master definition node
  - Creator and applied validation records live in Creator/

Metadata Record
  - Data about an index node
  - Defines what the node is, what it means, and what it owns
  - Machine-readable attributes using @ prefix
  - Tells the system and AI what the node represents

Skills Card
  - A metadata record attached to an index node
  - Contains definitions, links, and properties
  - Makes the architecture machine-readable and AI-traceable

═══════════════════════════════════════════════════════════════

NODE HIERARCHY STRUCTURE

Node levels below are identifier relationships, not documentation layer numbers. This is a planned hierarchy; an identifier does not imply an existing file. Current records are listed in the Creator index.

Level 0: Creator / Root
  0.00 = Victoria Love Franklin (Creator)

Level 1: Documentation Index
  0.1.00 = Documentation Index
  0.1.1.00 = README
  0.1.2.00 = Index & Metadata Definitions
  0.1.3.00 = Licensing

Level 2: Framework Definition
  0.2.00 = Identity & Role
  0.3.00 = Mission
  0.4.00 = Vision
  0.5.00 = Values & Principles
  0.6.00 = Governance & Authority
  0.7.00 = Goals & Roadmap
  0.8.00 = Technical Architecture
  0.9.00 = Standards & Compliance

═══════════════════════════════════════════════════════════════

METADATA RECORD STRUCTURE

Every node should include these core metadata fields:

@definition
  Purpose: Explains what the node is and what it represents

@name
  Purpose: Human-readable name of the node

@role
  Purpose: Classifies the node

@parent
  Purpose: Identifies the parent node

@children
  Purpose: Lists sub-nodes

@linked_to
  Purpose: Connects related nodes or external resources

@authority
  Purpose: Defines decision-making level

@status
  Purpose: Current lifecycle state

@version
  Purpose: Semantic versioning

@created
  Purpose: Creation date

@modified
  Purpose: Last modified date

═══════════════════════════════════════════════════════════════

RECORD PLACEMENT

The creator example's identity, authority, biography, ownership, and machine-readable fields are maintained in the canonical Layer 2 creator anchor record rather than duplicated in Foundation.

═══════════════════════════════════════════════════════════════

NEXT STEPS

The repository will continue to expand with framework definitions, policy nodes, approval nodes, and implementation documentation.

This file defines node classification and fields alongside [Metadata Model](metadata-model.md). Foundation defines the rules; Creator records implement them.
