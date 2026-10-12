ROD Framework - Index & Metadata Definitions
Created by: Victoria Love Franklin
Source: 0.00
Date: 2026-10-05
Version: 1.0.0

═══════════════════════════════════════════════════════════════

REPOSITORY STRUCTURE & NODE CLASSIFICATION

The active documentation layers are Foundation/ (Layer 1) and Creator/ (Layer 2).
Creator records belong in Creator/ and follow the rules defined in Foundation/.

Top-level repo files are support documents, not framework nodes:
- README.md = portal and navigation, not a node
- LICENSE.md = legal text, not a node
- NOTICE.md = legal/ownership text, not a node
- CONTRIBUTING.md = operational guidance, not a node

Foundation/ files define the rules and supporting references, not creator records:
- Foundation/architecture.md = architectural model
- Foundation/governance.md = governance rules
- Foundation/metadata-model.md = metadata rules
- Foundation/validation-references.md = validation criteria

Best practice:
- root of repo = navigation and legal files
- Foundation/ = Layer 1 structural and governance rules
- Creator/ = Layer 2 creator records and supporting documents

Not every layer file is a record: README, index, and supporting documents provide navigation and guidance.
The docs/ and framework/ directories are retained legacy material, including validation records and forms without layered equivalents; they are not the primary active structure.

═══════════════════════════════════════════════════════════════

CORE CONCEPTS

Index Node
  - A unique identifier in decimal notation (0.00, 0.1.00, 0.2.00, etc.)
  - Represents a category, concept, or structural element
  - The .00 suffix denotes a master definition node
  - Creator records live in Creator/ (Layer 2); other node types remain in retained legacy material until a layer is defined for them

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

@repository = "Franklin-Research-Hub/ROD_Framework"

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

This file provides supplemental index and record definitions. The active structure and metadata rules are defined in Foundation/, with the creator anchor in Creator/0.00-creator.md.
