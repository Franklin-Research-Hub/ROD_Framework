ROD FRAMEWORK - INDEX & METADATA DEFINITIONS
Created by: Victoria Love Franklin
Source: 0.00
Date: 2026-10-05
Version: 1.0.0

═══════════════════════════════════════════════════════════════

REPOSITORY STRUCTURE & NODE CLASSIFICATION

Only files in the framework/ folder should be actual nodes.

Top-level repo files are support documents, not framework nodes:
- README.md = portal and navigation, not a node
- LICENSE = legal text, not a node
- NOTICE.md = legal/ownership text, not a node
- CONTRIBUTING.md = operational guidance, not a node

docs/ files are supporting documentation, not metadata nodes:
- docs/architecture.md = implementation reference, not a node
- docs/governance.md = operational guidance, not a node
- docs/replication.md = implementation playbook, not a node
- docs/metadata-model.md = supporting documentation, not a node

Best practice:
- root of repo = navigation and legal files
- framework/ = actual metadata-driven node system
- docs/ = non-node reference material linked from nodes

Only framework/ files are true nodes in the system.

═══════════════════════════════════════════════════════════════

CORE CONCEPTS

Index Node
  - A unique identifier in decimal notation (0.00, 0.1.00, 0.2.00, etc.)
  - Represents a category, concept, or structural element
  - The .00 suffix denotes a master definition node
  - Lives exclusively in framework/ folder

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

EXAMPLE RECORD

0.00 :: VICTORIA LOVE FRANKLIN - CREATOR
@definition = "Root creator identity and origin of the framework"
@name = "Victoria Love Franklin"
@role = ["Creator", "Architect", "Designer", "Developer"]
@authority = "FULL"
@framework_owner = true
@created = "2026-10-05"
@bio_url = "https://victorialovefranklin.github.io/victoria-franklin-site/"
@bio_title = "Victoria Love Franklin | Portfolio"
@bio_source = "GitHub Pages Portfolio"
@bio_linked = true
@entity_type = "PERSON"
@status = "ACTIVE"
@version = "1.0.0"
@repository = "Franklin-Research-Hub/rod-framework-docs"
@source_of_truth = true
@governance_level = "ROOT"
@responsibility = [
  "Framework design",
  "System architecture",
  "Content strategy",
  "Metadata structure",
  "Governance model",
  "AI/LLM knowledge architecture"
]
@copyright = "Copyright (c) 2026 Victoria Love Franklin. All rights reserved."
@license_type = "Proprietary - Licensed by Contract"

═══════════════════════════════════════════════════════════════

NEXT STEPS

The repository will continue to expand with framework definitions, policy nodes, approval nodes, and implementation documentation.

This file is the governing definition for how the node system is structured and how to classify repository files.
