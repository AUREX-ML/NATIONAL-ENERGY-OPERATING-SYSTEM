# Product Portfolio

## Status

Organizational doctrine — Product Portfolio v1.0

## 1. Purpose

The organization exists to build digital coordination infrastructure that enables heterogeneous energy resources, facilities, portfolios, utilities, system operators, and other authorized energy stakeholders to work together.

The portfolio translates that mission into repeatable products.

The organization does not define a product as a piece of software, a dashboard, a hardware device, or a collection of features. A product is a packaged, repeatable coordination capability that solves a recurring problem for a defined stakeholder and can be operated sustainably.

---

## 2. Portfolio Architecture

The product portfolio follows a hierarchy of increasing coordination responsibility:

```text
Facility EMS
Assets → Facility capability
        ↓
Regional DERMS
Facilities → Regional capability
        ↓
National DERMS
Regions → National DER capability
```

Each layer absorbs complexity below it and exposes a useful standardized capability upward.

This is not a hierarchy of centralized control. Authority remains as close as practical to the physical system.

```text
National DERMS → coordinates regions
Regional DERMS → coordinates facilities
Facility EMS → coordinates and controls local assets
Physical devices → retain equipment protection and safety functions
```

**Architectural principle:** Coordinate globally; control locally.

---

## 3. Shared Energy Operating Platform

Facility EMS, Regional DERMS, and National DERMS are not three unrelated software systems. They are products delivered from a common Energy Operating Platform.

```text
                 ENERGY OPERATING PLATFORM
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
 Facility EMS      Regional DERMS    National DERMS
```

The platform may include:

- southbound device and vendor integrations;
- protocol adapters;
- common energy-resource information models;
- edge control and automation;
- telemetry and historical data infrastructure;
- identity and authorization;
- forecasting and optimization;
- capability abstraction;
- secure Edge-to-Backend communications;
- portfolio services;
- regional coordination services;
- national federation services;
- APIs and developer tooling;
- cybersecurity and observability.

The Energy Operating Platform is therefore the shared technical foundation. It is not automatically a fourth customer product.

Open-source systems such as OpenEMS may provide important core capabilities, particularly at the Edge and Backend layers, but no single codebase defines the organization's identity. Technology may evolve while the mission remains constant.

---

# 4. Product 1 — Facility EMS

## Customer

Organizations responsible for operating energy-intensive facilities, initially commercial facilities where multiple energy assets must be managed together.

## Problem

Facility energy infrastructure is frequently fragmented across different vendors, protocols, interfaces, meters, generators, renewable systems, batteries, loads, sensors, and control systems.

The facility operator lacks one coherent operational picture and coordination layer.

## Product responsibility

Facility EMS enables heterogeneous resources to be observed, understood, coordinated, safely controlled, and verified as one facility energy system.

## Definition of Done

> Facility EMS is complete when the authorized facility operator can observe, understand, coordinate, and safely control the facility's energy resources as one system and verify the resulting response.

## Delivery model

Initial delivery may combine:

- an edge-computing appliance;
- Energy Operating Platform software;
- commissioning and integration;
- managed monitoring;
- security and updates;
- support;
- optimization services.

The edge hardware is a delivery mechanism, not the organization's permanent technological identity.

## Economic role

Facility EMS is intended to become the earliest repeatable commercial revenue engine while simultaneously creating standardized infrastructure that can later participate in higher-order coordination when explicitly authorized.

---

# 5. Portfolio Aggregation Capability

Multi-facility portfolio aggregation is an important capability, but it is not presently defined as a separate product.

A customer owning twenty hotels should be able to operate twenty Facility EMS deployments under one ownership hierarchy and portfolio view without requiring creation of a separate product category.

The Backend should support capabilities such as:

- multi-Edge connectivity;
- ownership hierarchy;
- multi-tenancy;
- centralized monitoring;
- portfolio analytics;
- remote operations;
- standardized facility capability interfaces.

**Decision:** Build portfolio aggregation as a platform capability unless evidence later demonstrates a distinct recurring coordination problem that passes the Product Creation Law.

---

# 6. Product 2 — Regional DERMS

## Initial customer

A bounded distribution or mini-grid operator is the preferred initial proving customer. Larger utility use follows after operational evidence is established.

## Problem

Multiple independently operated facilities and DER portfolios can each expose useful flexibility, generation, storage, demand, and operating constraints, but no individual Facility EMS can coordinate the distributed system as a whole.

## Product responsibility

Regional DERMS aggregates distributed capabilities across facilities and coordinates them toward regional or distribution-system objectives while preserving local operational autonomy.

## Operating loop

```text
Discover
   ↓
Observe
   ↓
Aggregate
   ↓
Evaluate Constraints
   ↓
Optimize
   ↓
Coordinate
   ↓
Verify
   ↺
```

## Definition of Done

> Regional DERMS is complete when an authorized operator can discover and observe distributed energy capabilities across its service area, aggregate them, evaluate relevant operational constraints, optimize their coordinated use, request appropriate responses, and verify delivery while preserving local operational autonomy.

## Economic role

Regional DERMS becomes an infrastructure business. Its sustainable economics may ultimately relate to managed capacity, participating nodes, service area, availability, optimization services, flexibility services, or system-performance outcomes. Exact pricing must be validated rather than assumed.

---

# 7. Product 3 — National DERMS

## Strategic user/customer

The national System Operator function and other authorized national energy-system actors, subject to Kenya's legal and institutional framework.

The product is designed around the institutional function rather than permanent dependence on one company's current organizational role.

## Problem

As distributed energy resources become numerous and operationally significant, the national power system requires a scalable mechanism for understanding and coordinating their aggregate capabilities without requiring the national System Operator to directly manage millions of individual DERs.

Regional DERMS can solve regional coordination problems but cannot independently determine the contribution of all regions to national system objectives.

## Product responsibility

National DERMS provides a federated coordination layer through which regional DER capabilities can become visible, forecastable, aggregatable, coordinatable, and verifiable at national scale.

It does not replace the National Control Centre, transmission SCADA/EMS, physical protection systems, utilities, regulators, or the System Operator.

## National abstraction

```text
Many assets
    ↓
Facility capability
    ↓
Many facilities
    ↓
Regional capability
    ↓
Many regions
    ↓
National DER capability
```

National DERMS should primarily interact with aggregated regional capabilities rather than treating every inverter or meter as a centrally controlled national resource.

## Operating loop

```text
Forecast
   ↓
Aggregate
   ↓
Assess
   ↓
Coordinate
   ↓
Verify
   ↓
Learn
   ↺
```

## Definition

> National DERMS is a federated distributed-energy coordination platform that aggregates standardized capabilities from regional DERMS domains and provides authorized national system actors with visibility, forecasting, coordination, and verification of distributed energy flexibility while preserving regional and local operational autonomy.

## Economic role

National DERMS is strategic infrastructure. Sustainable economics may involve long-term infrastructure contracts, managed services, utility or government procurement, public-private arrangements, or development-finance-supported deployment followed by durable operational funding.

Development funding may accelerate capability creation, but permanent operation must not depend indefinitely on grants.

---

# 8. Product Boundary

The organization owns the coordination layer and orchestrates the ecosystem around it.

It does not seek to vertically integrate every function in the energy value chain.

## Within the organization's core domain

- interoperability;
- energy visibility;
- infrastructure management;
- capability abstraction;
- aggregation;
- forecasting;
- optimization;
- coordination;
- automation;
- secure control interfaces;
- operational data infrastructure.

## Normally partner rather than vertically integrate

- solar-panel manufacturing;
- battery manufacturing;
- inverter manufacturing;
- general EPC work;
- telecommunications infrastructure;
- general-purpose cloud infrastructure;
- financing;
- electricity generation ownership;
- regulatory functions;
- utility functions.

The organization may integrate or package third-party edge hardware when necessary to deliver its coordination capability. This does not make hardware manufacturing its core business.

**Boundary rule:** Own what differentiates the coordination capability. Partner for what enables it.

---

# 9. Product Creation Law

> A new product may be created only when a recurring energy-coordination problem exists for a defined stakeholder, cannot be adequately solved by the existing product portfolio, and the organization can package a proven capability into a repeatable solution that advances the mission.

Every proposed product must pass seven gates:

1. **Recurring Problem** — Is the problem repeated across customers or operating environments?
2. **Coordination Problem** — Does it belong within the organization's energy-coordination mission?
3. **Defined Stakeholder** — Who experiences the problem and is responsible for solving it?
4. **Existing Product Insufficient** — Can the requirement instead be implemented as a feature or platform capability?
5. **Capability Proven** — Has the organization demonstrated that it can solve the problem?
6. **Repeatable** — Can the solution be delivered without rebuilding it from scratch for every customer?
7. **Mission Advancing** — Does the product materially advance the organization's mission?

A failed gate determines where the idea belongs:

```text
Not recurring → Experiment
Existing product sufficient → Feature / capability
Not proven → R&D / prototype
Not repeatable → Project / service
Outside coordination mission → Partner / ecosystem
Passes all gates → Product
```

**Short form:** Problem before product. Capability before scale. Mission before opportunity.

---

# 10. Portfolio Growth Law

> Every product must create value independently at its own coordination level while creating the technical possibility — but never automatic authority — for participation at the next level.

Facility EMS must be valuable even if Regional DERMS never exists.

Regional DERMS must be valuable even if National DERMS never exists.

Deployment at one level does not automatically grant permission to participate at another.

```text
Technical capability
        ≠
Operational authority
        ≠
Commercial permission
        ≠
Regulatory permission
```

Higher-level participation must be authorized, contractual, technically constrained, auditable, and regulatorily permitted where required.

---

# 11. Right-to-Scale Principle

> The organization earns the right to manage a larger energy system only by demonstrating that it can reliably coordinate the system immediately below it.

Funding, ambition, publicity, or institutional access do not independently unlock the next stage.

Evidence does.

```text
Solve
  ↓
Prove
  ↓
Earn Trust
  ↓
Accept Greater Responsibility
  ↓
Scale
```

---

# 12. Product Roadmap

```text
Facility EMS Laboratory Prototype
 │
 ├── G0 Technical Proof
 ▼
Facility EMS MVP — Real Facility
 │
 ├── G1 Operational Proof
 ▼
Facility EMS Production
 │
 ├── G2 Repeatability Proof
 ▼
Portfolio Aggregation
 │
 ├── G3 Aggregation Proof
 ▼
Regional DERMS Prototype
 │
 ├── G4 Coordination Proof
 ▼
Regional DERMS MVP — Mini-grid / bounded distribution system
 │
 ├── G5 Regional Operational Proof
 ▼
Utility Pilot
 │
 ├── G6 Institutional Proof
 ▼
National DERMS Prototype
 │
 ├── G7 Federation Proof
 ▼
National DERMS
 │
 ▼
Federated Energy Ecosystem
```

## G0 — Technical Proof

Demonstrate heterogeneous resources operating through one facility environment with reliable telemetry, coordination, safe control, and verification.

## G1 — Operational Proof

Demonstrate value in a real facility with real operators, assets, failures, communications conditions, and operating procedures.

## G2 — Repeatability Proof

Demonstrate that another trained engineer can deploy and commission the product through documented processes without rebuilding the system from scratch.

## G3 — Aggregation Proof

Demonstrate that multiple Facility EMS nodes can expose standardized capabilities upward without losing local autonomy.

## G4 — Coordination Proof

Demonstrate multi-facility aggregation, forecasting, constraint evaluation, optimization, coordination, and verification in a controlled Regional DERMS environment.

## G5 — Regional Operational Proof

Demonstrate Regional DERMS in a real mini-grid or bounded distribution environment with measurable operational value and operator trust.

## G6 — Institutional Proof

Demonstrate utility-grade governance, cybersecurity, integration, reliability, auditability, regulatory compatibility, and organizational continuity.

## G7 — Federation Proof

Demonstrate that independently operated regional coordination systems can expose standardized capabilities to a national layer while retaining regional and local authority.

---

# 13. Product Evidence Ladder

Products progress through five levels of evidence:

```text
Idea
 ↓
Problem Evidence
 ↓
Technical Evidence
 ↓
Operational Evidence
 ↓
Commercial Evidence
 ↓
Institutional Evidence
 ↓
Scale
```

Every major stage transition should be supported by an Evidence Pack containing the information appropriate to the responsibility being assumed. Evidence may include:

- problem validation;
- architecture documentation;
- test results;
- commissioning records;
- reliability and availability data;
- cybersecurity assessment;
- operator feedback;
- performance metrics;
- incident records and lessons learned;
- deployment economics;
- customer-value evidence;
- repeatability assessment;
- governance and regulatory evidence.

A stage review should result in one of three decisions:

```text
PASS → advance
HOLD → improve evidence/capability
STOP → discontinue or redesign
```

**Evidence-before-Expansion:** No product advances because the next stage is exciting; it advances because evidence demonstrates readiness for greater responsibility.

---

# 14. Portfolio Economics

The products have different economic roles.

## Facility EMS — Revenue Engine

Facility EMS should establish early repeatable revenue through deployment, commissioning, integration, infrastructure management, monitoring, support, security, updates, analytics, and optimization.

Each successful deployment should create both customer value and additional standardized infrastructure.

## Regional DERMS — Infrastructure Business

Regional DERMS expands the commercial unit from individual facilities toward coordinated distributed capacity and service areas. Its economics must eventually sustain the operational responsibility associated with regional coordination.

## National DERMS — Strategic Infrastructure

National DERMS requires durable institutional economics appropriate for nationally significant infrastructure. Development finance may assist deployment, but grants are not a substitute for a long-term operating model.

## Product Sustainability Law

> Every product must ultimately sustain the operational responsibility it creates.

Cross-subsidy may support research and early platform development, but one product should not permanently carry the operating costs of another.

## Open Source and Commercial Sustainability

Open standards and open-source software do not imply free infrastructure operations.

The organization may keep standards, interfaces, interoperability work, reference implementations, and appropriate software components open while charging for accountable delivery such as:

- deployment;
- integration;
- managed operations;
- security;
- service levels;
- optimization;
- support;
- infrastructure management.

Customers pay for trusted operational responsibility, not merely permission to access source code.

---

# 15. Portfolio Failure Analysis

The portfolio can fail even if its technology works.

## Adoption Risk

Technically capable systems may fail if operators do not trust, use, or economically value them.

**Control:** prove operational value before scaling.

## Integration Explosion

Vendor and protocol diversity can turn a product into perpetual custom integration work.

**Control:** reusable adapters, open standards, common information models, certified integrations, and ecosystem contribution.

## Open-Source Dependency

A single external codebase must not become a permanent organizational dependency.

**Control:** contribute upstream, maintain architectural understanding, use clear interfaces, preserve portability, and keep organization-specific capabilities separable.

## Cybersecurity Risk

The consequences of compromise increase dramatically when the platform gains control authority.

**Control:** security-by-design, least privilege, authenticated control, segmentation, encryption, auditability, secure updates, incident response, and progressively stronger assurance.

**Rule:** Cybersecurity must scale before control authority scales.

## Safety and Liability

Higher-level coordination requests may ultimately affect physical equipment.

**Control:** preserve local equipment constraints and safety authority, explicitly define decision rights, and maintain contractual and technical responsibility boundaries.

## Regulatory Risk

Technical capability does not create legal authority.

**Control:** integrate with authorized institutions and design regulatory compliance into products.

## Institutional Trust Risk

Critical infrastructure cannot depend on founder knowledge or informal operating processes.

**Control:** documentation, governance, SLAs, independent testing, disaster recovery, organizational continuity, and progressively earned institutional trust.

## Premature Scaling

Funding or attention can tempt the organization to jump directly to national-scale responsibility.

**Control:** enforce the Right-to-Scale Principle and Evidence-before-Expansion.

## Financial Risk

Long sales cycles, engineering costs, integration work, and institutional procurement can create severe cash-flow pressure.

**Control:** build commercially independent Facility EMS value, recurring managed-service economics, disciplined deployment, and sustainable economics at each product level.

## Accidental Vertical Integration

Customer requests can pull the organization into EPC, hardware manufacturing, financing, or other non-core functions.

**Control:** own the coordination layer and partner around it.

## Centralization Risk

Technical convenience may encourage excessive centralized control.

**Control:** preserve the federated hierarchy and local operational autonomy.

## Mission Drift

Commercial opportunities may eventually pull the portfolio toward unrelated products.

**Control:** enforce the Product Creation Law.

---

# 16. Master Risk Principle

The greatest portfolio risk is accepting responsibility faster than the organization develops the capability and trust required to carry it.

> **Never allow the organization's coordination authority to grow faster than its technical capability, operational evidence, governance, cybersecurity, and institutional trust.**

---

# 17. Portfolio Flywheel

The portfolio grows horizontally through adoption and vertically through proven coordination capability.

```text
Facility customers
       ↓
Deployments
       ↓
Managed infrastructure
       ↓
Operational experience
       ↓
Better platform
       ↓
More trust
       ↓
More deployments
       ↓
Aggregatable capability
       ↓
Regional DERMS opportunities
       ↓
Institutional evidence
       ↓
National federation capability
```

**Growth principle:** Expand horizontally through adoption; expand vertically through proven coordination capability.

---

# 18. Product Doctrine Summary

The organization's product doctrine is therefore:

1. **Facility EMS** turns heterogeneous assets into a coherent facility capability.
2. **Regional DERMS** turns multiple facility capabilities into a coordinated regional capability.
3. **National DERMS** federates regional capabilities into a nationally useful distributed-energy resource for authorized system actors.
4. All three products are delivered from a shared **Energy Operating Platform**.
5. The organization owns the coordination layer and collaborates with the surrounding energy ecosystem.
6. New products must pass the **Product Creation Law**.
7. Products create value independently while enabling, but never automatically authorizing, higher-level participation.
8. Greater responsibility is earned through the **Right-to-Scale Principle**.
9. Expansion requires evidence through the **Product Evidence Ladder**.
10. Every product must ultimately sustain the operational responsibility it creates.
11. Open standards and open-source collaboration remain compatible with commercial managed infrastructure services.
12. Coordination authority must never grow faster than capability, evidence, governance, cybersecurity, and trust.

---

## Core Portfolio Statement

> **We build digital energy infrastructure that progressively transforms heterogeneous physical resources into trusted facility, regional, and national coordination capabilities — while preserving local autonomy, open interoperability, institutional roles, and the mission to improve Africa's energy infrastructure.**
