# Product Roadmap

## Purpose

The Product Portfolio defines **what the organization builds**. This Product Roadmap defines **how the organization earns the right to build and operate those products at increasing scale**.

The roadmap is evidence-gated rather than ambition-gated.

> **Solve → Prove → Standardize → Earn Trust → Accept Greater Responsibility → Scale → Distribute Stewardship.**

---

## Governing Architecture

The organization scales through abstraction rather than centralized control:

```text
Assets
  ↓
Facility EMS
  ↓
Facility Capability
  ↓
Portfolio Aggregation
  ↓
Regional DERMS
  ↓
Regional Capability
  ↓
National DERMS
```

The permanent architectural law is:

> **Coordinate globally; control locally.**

Higher coordination layers express objectives and constraints. Lower layers retain responsibility for safe execution within their authorized operating boundaries.

Two additional laws apply throughout the roadmap:

> **Authority cannot increase as a request travels downward.**

> **Failure above must not destroy safe operation below.**

---

# Stage 0 — Facility EMS Laboratory

## Objective

Prove that heterogeneous distributed energy resources can be integrated, observed and coordinated as one facility energy system.

The laboratory validates the technical foundation before real operational responsibility is accepted.

## Core Proof

- Connect heterogeneous energy assets and protocols.
- Normalize their data into a coherent facility model.
- Observe system state through a unified interface.
- Execute bounded control logic safely.
- Test communications and equipment failures.
- Demonstrate that vendor differences do not prevent coordinated operation.

## Definition of Done

The laboratory is complete when the system can reliably observe, understand, coordinate and safely control representative heterogeneous facility energy resources as one system.

## Gate 0 — Technical Proof

> **Can the technology coordinate heterogeneous energy resources safely and coherently?**

If no, remain in Stage 0.

If yes, proceed to a real facility.

---

# Stage 1 — Facility EMS MVP

## Objective

Deploy Facility EMS in one controlled, energy-intensive commercial facility and prove operational value.

The deployment progresses through increasing authority:

```text
Connect
  ↓
Observe
  ↓
Validate
  ↓
Recommend
  ↓
Operator-approved control
  ↓
Limited automation
  ↓
Verified autonomous operation
```

## Primary Customer Outcomes

The MVP prioritizes:

1. Cost improvement.
2. Reliability improvement.

Secondary outcomes may include renewable utilization, maintenance visibility, operational reporting and reduced operator workload.

## Definition of Done

Stage 1 is complete when Facility EMS has operated reliably in a real commercial facility, is usable by the facility operator without continuous founder intervention, safely coordinates authorized energy resources, survives realistic failures and demonstrates measurable value against an established baseline.

## Gate 1 — Operational Proof

> **Can this facility depend on Facility EMS during normal operations without depending on its founder?**

---

# Stage 2 — Facility EMS Production

## Objective

Turn the successful facility deployment into a repeatable product.

The organization must demonstrate that different facilities can be deployed without rebuilding the software for every customer.

## Productization Requirements

- Standard edge appliance lifecycle.
- Configuration separated from source code.
- Supported integration catalogue.
- Common facility information model.
- Standard deployment and commissioning procedures.
- Remote fleet operations.
- Productized cybersecurity.
- Support and maintenance processes.
- Measured unit economics.
- Declining site-specific engineering effort.

The delivery model is:

> **Edge Appliance + Managed Service.**

## Definition of Done

Stage 2 is complete when Facility EMS can be repeatedly deployed, commissioned, operated, updated and supported across heterogeneous facilities using standardized technology and documented processes, with acceptable unit economics and without continuous founder-level engineering intervention.

## Gate 2 — Product Proof

> **Can another trained engineer deploy and operate Facility EMS successfully using the organization's platform, tools and documentation?**

If no, the organization still has a founder-led engineering service.

If yes, it has a product.

---

# Stage 3 — Portfolio Aggregation

## Objective

Prove that multiple independent Facility EMS deployments can be organized and represented as one customer portfolio without sacrificing facility autonomy.

Portfolio aggregation is a **capability**, not a separate product.

Example hierarchy:

```text
Organization
  ↓
Portfolio
  ├── Facility A
  ├── Facility B
  └── Facility C
```

A customer owning twenty hotels remains one organization with twenty facilities—not twenty unrelated customers.

## Core Capabilities

- Organization and ownership hierarchy.
- Multi-tenant identity and access control.
- Portfolio-wide visibility.
- Facility benchmarking.
- Facility-level drill-down.
- Standardized facility capability abstraction.
- Capability aggregation.
- Explicit participation permissions.
- Continued local operation during backend failure.

## Definition of Done

Stage 3 is complete when multiple independently operating Facility EMS deployments can be securely organized into ownership portfolios, centrally observed and benchmarked, and represented through standardized facility-level energy capabilities while preserving local operational autonomy and explicit control permissions.

## Gate 3 — Aggregation Proof

> **Can many facilities behave as one portfolio to the layer above without becoming one centrally controlled facility?**

---

# Stage 4 — Regional DERMS Prototype

## Objective

Build the first Regional DERMS prototype and prove distributed coordination against an external electricity-system objective.

Example objective:

> Reduce demand on a constrained feeder by 300 kW for a defined period.

## Regional DERMS Operating Loop

```text
Discover
  ↓
Observe
  ↓
Forecast
  ↓
Aggregate
  ↓
Evaluate constraints
  ↓
Optimize
  ↓
Coordinate
  ↓
Verify
  ↓
Adapt
  ↺
```

## Architectural Contract

Regional DERMS specifies **what** capability is required.

Facility EMS determines **how** that capability can be safely delivered locally.

Facilities must be able to accept, partially accept, reject or declare themselves unavailable.

## Definition of Done

Stage 4 is complete when Regional DERMS can discover and aggregate standardized capabilities from multiple autonomous Facility EMS nodes, forecast system conditions, evaluate relevant constraints, optimize responses to an external objective, coordinate distributed actions, verify delivered response and safely adapt to failures or changing availability without overriding local authority.

## Gate 4 — Coordination Proof

> **Can Regional DERMS solve a system-level energy problem using distributed facility capabilities without directly controlling the underlying DERs?**

---

# Stage 5 — Regional DERMS MVP

## Objective

Move Regional DERMS from simulation into a real bounded electricity system.

The preferred first proving environment is a private mini-grid or similarly bounded distribution-system operator.

## Authority Progression

```text
Observe
  ↓
Forecast
  ↓
Recommend
  ↓
Operator-approved coordination
  ↓
Bounded automated coordination
```

## Core Proof

- Establish real system baseline.
- Integrate existing operational infrastructure.
- Provide operator decision support.
- Coordinate generation, storage, demand and flexibility.
- Improve renewable integration where applicable.
- Handle real operational failures.
- Measure resource reliability and flexibility confidence.
- Strengthen cybersecurity controls.
- Preserve operator override and institutional authority.

## Definition of Done

Stage 5 is complete when Regional DERMS has operated within a real bounded electricity system, provided trusted visibility and forecasting, successfully coordinated authorized distributed resources under actual constraints, verified delivered responses, handled failures safely, demonstrated measurable system value and earned sustained operator trust without assuming authority belonging to the system operator.

## Gate 5 — Regional Operational Proof

> **Would this electricity-system operator continue depending on Regional DERMS after the pilot team leaves?**

---

# Stage 6 — Utility Pilot

## Objective

Integrate Regional DERMS into a bounded operational domain of an established electricity utility.

The goal is not to replace existing utility infrastructure. The goal is to add useful distributed-energy coordination capability.

## Pilot Principles

- Select one bounded utility use case.
- Integrate before expanding control authority.
- Coexist with relevant utility systems.
- Build electrical-location awareness.
- Maintain a trustworthy DER capability registry.
- Represent technical capability, operational authority and participation permission separately.
- Maintain complete auditability.
- Meet utility-grade cybersecurity and governance requirements.
- Prove organizational—not merely software—readiness.
- Ensure utility core operations continue safely if DERMS becomes unavailable.

## Definition of Done

Stage 6 is complete when Regional DERMS has been safely integrated into a bounded utility operational domain, demonstrated measurable value for an approved distribution-system use case, interoperated with relevant utility systems, coordinated authorized distributed capabilities under utility-defined constraints, produced auditable and verifiable responses, met required security and governance expectations and demonstrated organizational capacity for utility-grade operations.

## Gate 6 — Institutional Proof

> **Would an established electricity utility trust this organization and its platform with a larger coordination responsibility?**

---

# Stage 7 — National DERMS Prototype

## Objective

Prove federation across multiple independently governed Regional DERMS domains.

National DERMS does not directly coordinate millions of individual devices.

Instead:

```text
National DERMS
      │
      ├── Regional DERMS A
      ├── Regional DERMS B
      ├── Regional DERMS C
      └── Regional DERMS D
```

Each regional domain exposes a standardized **Regional Capability** upward.

## Federation Principles

National DERMS specifies national objectives.

Regional DERMS coordinates regional capability.

Facility EMS controls local resources.

Regional systems retain the right to accept, partially accept or reject national requests according to their constraints and authority.

Verification aggregates upward from physical resources to facilities, regions and ultimately the national layer.

## Resilience Principle

```text
National DERMS failure
        ↓
Regional DERMS continues
        ↓
Facility EMS continues
```

Higher-layer failure must never destroy safe lower-layer operation.

## Definition of Done

Stage 7 is complete when multiple independently governed Regional DERMS domains can expose standardized regional capabilities to National DERMS, participate in national forecasting and coordination objectives, accept or reject requests according to their own constraints and authority, provide verifiable aggregated responses, adapt to changing availability and continue safe independent operation during higher-layer failures.

## Gate 7 — Federation Proof

> **Can distributed energy resources behave as a nationally useful resource without requiring a national system to directly control those resources?**

---

# Stage 8 — National DERMS Deployment

## Objective

Transition the proven federation architecture into nationally significant digital energy infrastructure under legitimate institutional governance.

Stage 8 requires convergence of:

```text
Technical evidence
        +
Operational evidence
        +
Utility evidence
        +
Cybersecurity maturity
        +
Regulatory legitimacy
        +
Institutional agreement
        +
Governance
        +
Sustainable economics
        =
National deployment
```

## Institutional Principle

National DERMS exists inside the country's established energy governance structure—not above it.

The organization may build and operate infrastructure without assuming legal system-operating authority.

Ownership, operation and authority must be explicitly separated.

## National Infrastructure Requirements

- Explicit institutional mandate.
- Defined ownership and operating model.
- Defined authority and accountability.
- Production redundancy and disaster recovery.
- National-grade cybersecurity governance.
- Data ownership, access and retention rules.
- Open standards and documented interfaces.
- Replaceable components.
- Multiple trained operators.
- Sustainable financing and operations.
- Continuity across vendor, technology and leadership changes.

Open source does not mean open customer data, and open standards do not mean unrestricted infrastructure access.

## Definition of Done

National DERMS is operationally complete when authorized national institutions can reliably use a secure, federated and interoperable platform to understand and coordinate distributed energy capability across participating regions; regional and local systems retain appropriate autonomy; governance, authority and accountability are explicit; operations are financially and institutionally sustainable; and continuity does not depend on any single vendor, technology, organization or individual.

## Gate 8 — Infrastructure Stewardship

> **Can this infrastructure continue serving the energy system safely, sustainably and independently across institutional, technological and leadership change?**

---

# Roadmap Summary

| Stage | Capability | Gate |
|---|---|---|
| 0 | Facility EMS Laboratory | Technical Proof |
| 1 | Facility EMS MVP | Operational Proof |
| 2 | Facility EMS Production | Product Proof |
| 3 | Portfolio Aggregation | Aggregation Proof |
| 4 | Regional DERMS Prototype | Coordination Proof |
| 5 | Regional DERMS MVP | Regional Operational Proof |
| 6 | Utility Pilot | Institutional Proof |
| 7 | National DERMS Prototype | Federation Proof |
| 8 | National DERMS Deployment | Infrastructure Stewardship |

```text
Facility EMS Laboratory
        ↓
Facility EMS MVP
        ↓
Facility EMS Production
        ↓
Portfolio Aggregation
        ↓
Regional DERMS Prototype
        ↓
Regional DERMS MVP
        ↓
Utility Pilot
        ↓
National DERMS Prototype
        ↓
National DERMS
        ↓
Federated Energy Ecosystem
```

---

# Evidence Model

Every stage must produce evidence before progression. Depending on the stage, the evidence package should include:

- architecture and information models;
- asset and integration registers;
- commissioning evidence;
- reliability and performance metrics;
- incident records;
- cybersecurity assessments;
- authority and permission matrices;
- customer/operator feedback;
- before-and-after operational measurements;
- economic analysis;
- failure and resilience tests;
- lessons learned;
- formal stage review and gate decision.

The roadmap therefore does not advance because a feature exists.

It advances because the organization has **evidence that the capability works at the current level of responsibility**.

---

# Organizational Scaling Law

The organization should not expand because opportunity appears.

It expands after solving the real coordination problem at its current service level.

At facility level, the organization is not done until the facility operator can manage the facility's energy system coherently.

At regional level, it is not done until distributed facilities can provide useful coordinated capability to the relevant electricity-system operator.

At national level, it is not done until independently governed regional systems can participate in national coordination without surrendering appropriate autonomy.

Growth therefore follows demonstrated service capability, stakeholder collaboration and earned trust.

---

# Stewardship End State

The founder's role is to initiate the system—not to remain its permanent dependency.

The desired progression is:

```text
Founder
   ↓
Organization
   ↓
Community + Partners + Institutions
   ↓
Distributed stewardship
   ↓
Infrastructure continues
```

The organization succeeds when its technology can continue serving the mission through an ecosystem of capable stewards while remaining open, interoperable and resilient.

> **The mission is to transform Africa's energy infrastructure—not merely to sell technology.**
