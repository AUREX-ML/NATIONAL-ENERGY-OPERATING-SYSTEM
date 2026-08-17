# Domain 17 — Research, Innovation & Intellectual Capital

Domain 17 defines how the institution converts uncertainty into trustworthy knowledge and then converts trustworthy knowledge into architecture, standards, products, operations and scalable infrastructure.

It governs scientific research, experimentation, interoperability, conformance, open-source collaboration, intellectual property, institutional knowledge and the evidence gates that separate prototypes from production claims.

> **Research creates knowledge. Governance determines which knowledge is trustworthy enough to become infrastructure.**

## Domain Architecture

```text
Strategic Unknown
      ↓
Research Question
      ↓
Hypothesis
      ↓
Experiment
      ↓
Evidence
      ↓
Validation
      ↓
┌──────────────┬──────────────┬──────────────┬──────────────┐
│ Architecture │ Standard     │ Product      │ Operations   │
│ / ADR        │ / Conformance│ / Capability │ / Runbook    │
└──────────────┴──────────────┴──────────────┴──────────────┘
      ↓
Deployment
      ↓
Field Evidence
      ↓
Institutional Learning
      ↓
New Research
```

## Sessions

### 1. [Research & Innovation Architecture](./01-RESEARCH-AND-INNOVATION-ARCHITECTURE.md)

Defines the research agenda, research classes, programs, portfolio, technology readiness, prioritization, research debt and transfer paths.

### 2. [Scientific Research & Experimental Governance](./02-SCIENTIFIC-RESEARCH-AND-EXPERIMENTAL-GOVERNANCE.md)

Defines research protocols, experimental environments, variables, baselines, reproducibility, data lineage, measurement quality, pilot governance, site selection, safety and evidence boundaries.

### 3. [Interoperability, Standards & Conformance](./03-INTEROPERABILITY-STANDARDS-AND-CONFORMANCE.md)

Defines multi-vendor interoperability, protocol and integration catalogues, canonical data and capability models, specification versioning, conformance testing, certification and vendor-neutral ecosystem rules.

### 4. [Open Source, IP & Intellectual Capital](./04-OPEN-SOURCE-IP-AND-INTELLECTUAL-CAPITAL.md)

Defines open-source strategy, repository and contribution governance, licensing, dependencies, upstream contributions, fork management, intellectual assets, documentation, security disclosure and knowledge continuity.

### 5. [Integrated R&D Governance & Control](./05-INTEGRATED-RD-GOVERNANCE-AND-CONTROL.md)

Integrates the domain into one evidence-driven operating model with R&D gates, claim-to-evidence discipline, transfer governance, research debt, revalidation and stage-integrity controls.

## Core R&D Gate Model

```text
G0 — Question
G1 — Research Approved
G2 — Experiment Valid
G3 — Concept Proven
G4 — Laboratory Validated
G5 — Field Validated
G6 — Production Qualified
G7 — Scale Qualified
```

Technology Readiness Levels describe maturity. These gates determine whether the institution has sufficient evidence and governance to progress.

## Interoperability Principle

```text
OEM Device
   ↓
Native Protocol
   ↓
Adapter
   ↓
Canonical Data Model
   ↓
Capability Interface
   ↓
DERMS Applications
```

Vendor-specific complexity should remain below canonical interfaces wherever practical. Compatibility claims must include the versions and conditions actually tested.

## Open Infrastructure Principle

> **Open standards over proprietary dependence.**

Open interfaces, specifications and conformance mechanisms are strategic tools for enabling OEMs, developers, utilities, researchers and integrators to participate in a shared energy infrastructure ecosystem without forcing the institution to own every implementation.

## Evidence Discipline

The organization distinguishes:

```text
CONCEPT
HYPOTHESIS
SIMULATED
LAB-VALIDATED
FIELD-VALIDATED
PRODUCTION-PROVEN
```

A capability may only be described according to the evidence actually demonstrated.

## Key Supporting Artifacts

Domain 17 establishes requirements for later controlled artifacts including:

- Architecture Decision Records (ADRs)
- research questions, experiments, datasets and reports
- protocol catalogue
- integration catalogue
- site-selection criteria
- conformance and certification specifications
- RFCs
- data governance and data dictionary
- research/evidence/decision registers
- intellectual-asset, dependency and fork registers
- current-stage status
- glossary
- open-source contribution guide
- security disclosure policy
- maintainer and governance documentation

These are artifacts of the institutional architecture, not additional organizational domains.

## Master Domain Law

> **The organization shall maintain an integrated research, innovation and intellectual-capital system that converts strategically important uncertainty into governed questions, reproducible experiments, traceable evidence and explicit decisions; progressively validates technologies from simulation through laboratory, field and production environments; standardizes multi-vendor interoperability through canonical models, open specifications and reproducible conformance testing; governs open-source contributions, dependencies, licensing, forks and intellectual assets as strategic infrastructure; preserves negative results, uncertainty and institutional knowledge; transfers validated findings deliberately into architecture, products, standards and operations; continuously revalidates assumptions as technology and operating conditions change; and requires increasingly strong evidence as the consequence and scale of organizational responsibility increase.**

## Status

```text
Session 1  Research & Innovation Architecture              COMPLETE
Session 2  Scientific Research & Experimental Governance   COMPLETE
Session 3  Interoperability, Standards & Conformance       COMPLETE
Session 4  Open Source, IP & Intellectual Capital           COMPLETE
Session 5  Integrated R&D Governance & Control              COMPLETE

DOMAIN 17 STATUS: COMPLETE
```

## Next Domain

**Domain 18 — Market Development & Energy-Economy Architecture**

Domain 18 begins only after the Domain 17 documentation has been committed and the organizational master index updated.
