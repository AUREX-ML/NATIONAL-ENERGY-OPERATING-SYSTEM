# National Energy Operating System Programme

## Official Repository Overview

This repository contains the working programme architecture for a proposed **National Energy Operating System**: an open, governed digital coordination layer for distributed energy resources, facilities, regional energy systems, utilities, regulators, market actors, and other authorized energy-sector stakeholders.

The initiative is currently at **concept, architecture, and validation-preparation stage**. The repository should be read as a controlled programme knowledge base, not as a claim that a national production system is already deployed or approved.

## What Is Being Built

The programme is building the foundations for digital energy coordination infrastructure that can evolve through four levels:

```text
Facility EMS
  ↓
Regional DERMS
  ↓
National DERMS
  ↓
National Energy Operating System
```

At facility scale, the system coordinates meters, solar PV, batteries, generators, EV charging, controllable loads, sensors, and other energy assets through a local operating layer.

At regional scale, multiple facilities and distributed energy resources can be aggregated and coordinated while preserving local autonomy.

At national scale, regional capabilities can be made visible, forecastable, auditable, and coordinatable for authorized system, market, utility, regulatory, and planning functions.

The long-term objective is not to replace utilities, regulators, control centres, asset owners, or market institutions. The objective is to provide the interoperable digital operating layer through which authorized institutions and assets can coordinate safely.

## Core Problem

Kenya's electricity sector is becoming more distributed, more digital, and more operationally complex. Growth in distributed solar, storage, net metering, open access, e-mobility, regional power trade, and electricity-market reform increases the number of assets, measurements, operating limits, contracts, permissions, and settlement records that must be coordinated.

The central problem is therefore:

> Kenya does not yet have a complete, nationally governed, interoperable, secure, and operationally accepted capability for coordinating eligible distributed energy resources across local control, system operation, network constraints, market participation, metering, data exchange, and settlement processes.

## Repository Structure

| Section | Purpose |
|---|---|
| [Programme Definition](./docs/01-programme-definition/) | Defines the problem, purpose, scope, stage, and validation needs of the programme. |
| [System Architecture](./docs/02-system-architecture/) | Explains the Facility EMS, Regional DERMS, National DERMS, data, interoperability, cybersecurity, and operational architecture. |
| [Institutional Architecture](./docs/03-institutional-architecture/) | Organizes the institution required to build, govern, finance, operate, and sustain the programme. |
| [Implementation Roadmap](./docs/04-implementation-roadmap/) | Presents the evidence-gated path from laboratory proof to facility deployment, regional coordination, and national readiness. |
| [Governance & Assurance](./docs/05-governance-assurance/) | Defines authority boundaries, risk controls, regulatory alignment, evidence, assurance, and readiness discipline. |
| [Organization Docs](./organization-docs/) | Detailed 20-domain organizational architecture baseline. |

## Recommended Reading for Government Visitors

1. [Executive Brief](./docs/01-programme-definition/executive-brief.md)
2. [Programme Charter](./docs/01-programme-definition/programme-charter.md)
3. [Stakeholder and Institutional Map](./docs/01-programme-definition/stakeholder-and-institutional-map.md)
4. [Pilot Readiness Brief](./docs/04-implementation-roadmap/pilot-readiness-brief.md)
5. [Problem Statement and Needs Assessment](./docs/01-programme-definition/problem-statement-and-needs-assessment.md)
6. [System Architecture Overview](./docs/02-system-architecture/)
7. [Governance & Assurance Overview](./docs/05-governance-assurance/)
8. [Validation Readiness Checklist](./docs/05-governance-assurance/validation-readiness-checklist.md)
9. [Decision Gate Framework](./docs/05-governance-assurance/decision-gate-framework.md)

## Current Status

| Area | Status |
|---|---|
| Problem framing | Working draft for validation |
| Organizational architecture | Baseline complete |
| Product architecture | Defined at concept / architecture level |
| Facility EMS pathway | Roadmap defined; implementation evidence required |
| Regional DERMS pathway | Architecture defined; dependent on facility proof |
| National DERMS / NEOS pathway | Strategic architecture defined; dependent on legal, institutional, technical, and operational validation |
| Government-facing readiness | Repository restructuring in progress |

## Important Boundaries

- Technical capability does not create regulatory authority.
- Remote monitoring, coordination, dispatch, aggregation, and market functions require explicit legal, contractual, grid-code, regulatory, or delegated authority.
- Local safety, protection systems, and asset-owner rights remain superior to higher-level optimization.
- National coordination should emerge from proven facility and regional capabilities, not from premature centralized control.
- All benefits, economics, and deployment claims require evidence through discovery, pilots, baselines, and stakeholder validation.

## Government Review Focus

Government and public-sector stakeholders should review:

1. Whether the problem statement accurately reflects Kenya's energy-sector coordination needs.
2. Which public institutions should own, authorize, regulate, operate, procure, audit, or benefit from each capability.
3. What legal, regulatory, grid-code, data-protection, cybersecurity, procurement, and institutional constraints apply.
4. Which pilot environments are appropriate for proving Facility EMS and Regional DERMS capability.
5. What evidence is required before any national-scale claim, deployment, or procurement decision.

## Next Programme Step

The next step is **Architecture Reconciliation and Government-Readiness Refinement**:

```text
Existing material
  ↓
Official repository structure
  ↓
Gap and duplication review
  ↓
Validation-ready documentation
  ↓
Stakeholder review
  ↓
Pilot / discovery decision
```

This repository is being refined so that it can support serious technical, institutional, and government review.
