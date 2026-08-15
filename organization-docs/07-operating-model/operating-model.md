# Operating Model

## Purpose

This document defines how the organization executes its mission in practice: how problems become work, how responsibility is assigned, how decisions are made, how software reaches production, how live infrastructure is operated, how knowledge is retained, how partners participate, and how authority is governed.

The operating model is designed around the same principles as the energy infrastructure the organization intends to coordinate: **distributed execution, local autonomy, shared standards, evidence, and higher-level coordination.**

---

## Core Operating Thesis

> **The organization operates as a distributed problem-solving system: responsibility and execution are placed as close as practical to the people and systems possessing the relevant knowledge, while shared standards, evidence, architecture, and governance preserve coordination toward one mission.**

The fundamental execution loop is:

```text
Problem → Understand → Build → Prove → Operate → Learn → Repeat
```

Progress is measured by validated capability or validated learning—not activity alone.

---

# 1. Execution Engine

The organization begins with real coordination problems rather than arbitrary features.

```text
REAL-WORLD PROBLEM
        ↓
RESEARCH
        ↓
ENGINEERING
        ↓
VALIDATION
        ↓
PRODUCT
        ↓
DEPLOYMENT
        ↓
OPERATIONS
        ↓
EVIDENCE
        ↓
LEARNING
        └──────────↺
```

Four primary operating functions support this loop:

- **Research** — determines what the problem is and what should be possible.
- **Engineering** — builds the required capability.
- **Delivery** — puts that capability into a real operating environment.
- **Operations** — keeps the deployed capability working and produces operating evidence.

The fundamental unit of organizational work is the **problem**.

Every important problem should define:

- owner;
- context;
- evidence;
- affected users or systems;
- required outcome;
- constraints;
- proposed solution where appropriate;
- validation method;
- Definition of Done.

### Operating Principle

> **The organization continuously identifies real coordination problems, understands them, engineers solutions, validates them in the field, operates what has been deployed, and feeds evidence back into the next decision.**

---

# 2. Organizational Structure

Structure follows responsibility rather than corporate convention.

A role should be created when a responsibility becomes persistent, specialized, and important enough that leaving it ambiguously owned creates operational risk.

## Early Stage

During laboratory development, several responsibilities may be concentrated in the founder or technical lead:

- product direction;
- research;
- architecture;
- software engineering;
- hardware integration;
- documentation;
- experimentation.

Once customers depend on Facility EMS, at least three explicit functions must exist even if one person temporarily holds several of them:

```text
Product / Technical Leadership
          │
   ┌──────┴──────┐
   ▼             ▼
Engineering    Delivery
   │             │
   └──────┬──────┘
          ▼
      Operations
```

As the organization matures, persistent responsibilities separate into Product, Research, Engineering, Delivery, Operations, Commercial/Partnerships, Security, Finance, Legal/Compliance, People, Program Management, Quality, and Governance.

The founder progressively moves from direct execution toward:

- mission;
- strategy;
- leadership;
- capital allocation;
- institutional relationships;
- governance.

### Structural Law

> **Distribute execution to the level possessing the relevant knowledge and authority while higher levels coordinate toward shared objectives.**

---

# 3. Roles, Ownership and Accountability

Collaboration may be distributed. Accountability must remain identifiable.

Every important problem has one clear **Problem Owner** responsible for ensuring closure.

Ownership does not mean personally performing all work. It means ensuring the required outcome is achieved and evidenced.

## Core Roles

### Founder / Leadership

Owns mission, long-term direction, strategic boundaries, leadership, major capital allocation, and institutional stewardship.

### Product Owner

Owns the translation of customer and system problems into product outcomes, priorities, requirements, Definition of Done, and product acceptance.

### Problem Owner

Owns a problem from discovery through understanding, solution, implementation, validation, and closure.

### Technical Owner

Owns technical design, architectural integrity, implementation quality, testing, maintainability, technical documentation, and technical risk for a capability or subsystem.

### Delivery Owner

Owns site readiness, deployment, integration, commissioning, acceptance evidence, and handover.

### Operational Owner

Owns monitoring, incidents, service health, maintenance, escalation, recovery, and operational performance after handover.

### Security Owner

Owns security requirements and security acceptance appropriate to the system's authority and risk.

## Accountability Chain

```text
Leadership
Why should this be solved?
        ↓
Product Owner
What outcome is required?
        ↓
Problem Owner
Who ensures closure?
        ↓
Technical Owner
How is it built?
        ↓
Delivery Owner
Does it work here?
        ↓
Operational Owner
Does it keep working?
```

### Accountability Laws

> **Every important problem has one identifiable owner responsible for closure.**

> **Authority must accompany accountability.**

---

# 4. Decision-Making System

Decisions belong at the lowest level possessing sufficient context, competence, and authority to make them safely.

Five decision levels are recognized:

1. **Local execution** — routine implementation and operational decisions.
2. **Cross-functional** — decisions affecting multiple functions and requiring consultation.
3. **Architectural** — decisions changing fundamental system structure or interfaces.
4. **Strategic** — decisions affecting markets, products, business model, capital, or organizational direction.
5. **Governance** — mission-changing, institution-threatening, ownership, or critical-authority decisions.

Consultation informs the Decision Owner; it does not automatically transfer the decision to a committee.

Decision effort increases with:

- consequence;
- uncertainty;
- irreversibility.

Where evidence can resolve disagreement, the organization should test before escalating opinion.

Important architectural and strategic decisions should be preserved through decision records containing context, decision, alternatives, evidence, consequences, owner, date, and review trigger.

### Decision Laws

> **Autonomy operates within mission, architecture, safety, security, and governance boundaries.**

> **Important decisions become organizational memory through documented reasoning.**

---

# 5. Work Management System

Incoming requests are not automatically engineering work.

```text
REQUEST
   ↓
UNDERSTAND
   ↓
PROBLEM
   ↓
CLASSIFY
   ↓
PRIORITIZE
   ↓
OWNER
   ↓
EXECUTE
   ↓
VALIDATE
   ↓
EVIDENCE
   ↓
DONE
   ↓
KNOWLEDGE
```

Primary work classes are:

- Incident;
- Defect;
- Capability;
- Integration;
- Research;
- Strategic initiative.

Critical incidents bypass normal prioritization.

For normal work, priority is determined by mission relevance, customer/system value, current roadmap-gate relevance, cost, and risk.

The current Product Roadmap gate receives priority over attractive future-stage work unless operational, security, safety, or strategic urgency justifies an override.

Work in progress should be deliberately limited. Finishing validated work creates more organizational value than continuously starting new work.

### Work Laws

> **Requests enter as problems to understand, not solutions to blindly implement.**

> **Work is not complete until its required outcome has been validated.**

> **Every completed piece of work should leave the organization with greater capability or greater knowledge.**

---

# 6. Operating Cadence

Different problems operate at different speeds.

```text
REAL-TIME  → incidents and operational response
DAILY      → execution and system visibility
WEEKLY     → execution + product/problem review
MONTHLY    → business + operational review
QUARTERLY  → strategy review
GATE       → evidence-triggered roadmap review
ANNUAL     → direction + governance review
```

Each horizon answers a different question:

- **Real-time:** Is the system safe?
- **Daily:** Are we executing?
- **Weekly:** Are we solving the right problems?
- **Monthly:** Is the organization healthy?
- **Quarterly:** Is the strategy working?
- **Gate:** Have we earned the right to scale?
- **Annual:** Are we still heading toward the right future?

Roadmap gates are triggered by evidence, not calendars.

Gate outcomes are **Pass**, **Conditional**, or **Fail**.

### Cadence Law

> **Status belongs in systems; meetings exist for decisions, coordination, ambiguity, and learning.**

---

# 7. Knowledge and Documentation System

Important knowledge belongs to the organization rather than the memory of the individual who discovered it.

Every important artifact needs:

- one canonical home;
- an identifiable owner;
- a clear authority/status;
- appropriate access control.

Knowledge domains include:

- organizational doctrine;
- product documentation;
- engineering documentation;
- Architecture Decision Records;
- research;
- integration knowledge;
- deployment records;
- operational runbooks;
- incident postmortems;
- customer knowledge.

Documentation should form part of Definition of Done where required.

Documentation lifecycle:

```text
DRAFT → REVIEWED → ACCEPTED → CURRENT → SUPERSEDED / ARCHIVED
```

Git should preserve technical and organizational history where appropriate, while credentials, personal data, customer secrets, sensitive infrastructure information, security secrets, contracts, and restricted operational data remain in controlled systems.

### Knowledge Law

> **Open what strengthens interoperability and collective capability; protect what confidentiality, security, safety, or institutional responsibility requires us to protect.**

---

# 8. Quality, Safety and Release Management

Production control authority is earned through evidence proportional to consequence.

Software moves progressively through:

```text
CODE
 ↓
REVIEW
 ↓
AUTOMATED TESTS
 ↓
INTEGRATION TEST
 ↓
SIMULATION
 ↓
LAB / HARDWARE-IN-THE-LOOP
 ↓
STAGING
 ↓
CONTROLLED DEPLOYMENT
 ↓
PRODUCTION
 ↓
MONITORING
```

Changes should be classified by risk, ranging from informational changes through observability, optimization, control, and safety/security-critical changes.

Physical protection remains below coordination software. Optimization may request and control may coordinate, but local protection retains final authority over physical safety.

Production changes include code, configuration, device mappings, control policies, permissions, certificates, and infrastructure.

Every significant production change should be traceable, observable, and recoverable.

Deployment should progress from laboratory/internal use through canary deployment and controlled cohorts before general rollout where risk justifies it.

## Right to Control

```text
OBSERVE
   ↓
RECOMMEND
   ↓
SCHEDULE
   ↓
CONTROL WITH SUPERVISION
   ↓
AUTOMATED CONTROL
```

> **Software earns the right to control physical energy infrastructure only after demonstrating sufficient evidence that it can operate within defined safety, security, and operational boundaries.**

---

# 9. Incident and Reliability Management

An incident is a temporary loss or degradation of a capability the organization accepted responsibility for providing.

Incident priorities are:

```text
1. Safety
2. Containment
3. Essential service
4. Restoration
5. Full capability/data
6. Root cause
```

Severity levels range from critical infrastructure/safety/security incidents to minor defects handled through normal work management.

Serious incidents receive an **Incident Commander** with predefined emergency authority.

Systems should degrade gracefully:

```text
NORMAL
  ↓
DEGRADED
  ↓
LOCAL AUTONOMY
  ↓
SAFE STATE
```

A failure at a higher coordination layer must not unnecessarily destroy safe operation below it.

Service Level Objectives should be established from measured operating evidence before contractual Service Level Agreements are promised.

Every significant incident produces a postmortem and owned corrective work.

### Reliability Laws

> **Safety and containment outrank restoration speed.**

> **A failure should have the smallest practical blast radius.**

> **Every significant incident must create corrective knowledge and owned improvement work.**

---

# 10. Security Operating Model

Open source does not mean open access.

The organization protects:

- people;
- energy infrastructure;
- information;
- control authority.

Production access follows:

```text
IDENTITY
   ↓
AUTHENTICATE
   ↓
AUTHORIZE
   ↓
MINIMUM REQUIRED ACCESS
   ↓
ACTION
   ↓
AUDIT
```

Human and machine identities receive only the minimum authority required for the minimum scope and duration necessary.

Control permissions are separated from ordinary information access.

Secrets have controlled lifecycles and must not be stored casually in source code, documentation, chats, or issue trackers.

Development, staging, and production trust domains should remain separated.

Customer and facility isolation should minimize lateral impact if one environment is compromised.

Security findings become owned operational problems with severity, owner, remediation, deadline, and closure evidence.

### Security Laws

> **Compromise of one layer must not automatically compromise the layers beneath or beside it.**

> **Design every layer assuming another layer may eventually be compromised.**

---

# 11. Customer and Deployment Operating Model

A customer lifecycle follows:

```text
QUALIFY
   ↓
DISCOVER
   ↓
ASSESS
   ↓
DESIGN
   ↓
CONTRACT
   ↓
PREPARE
   ↓
DEPLOY
   ↓
COMMISSION
   ↓
ACCEPT
   ↓
HANDOVER
   ↓
OPERATE
   ↓
REVIEW
   ↓
RENEW
   ↓
EXPAND
```

The organization does not sell a deployment before understanding the coordination problem and establishing technical feasibility.

Commercial commitments must correspond to capabilities Engineering and Delivery can responsibly provide.

Installation is not completion. Commissioning and acceptance evidence define completion.

Operations explicitly accepts responsibility through handover rather than inheriting undocumented deployments.

The Facility EMS overarching Definition of Done is:

> **The facility can observe, understand, coordinate, and safely control its energy resources as one system.**

Each facility remains its own managed energy system during the initial product stages, even when multiple facilities share a common owner. Expansion follows demonstrated value at previous deployments.

### Deployment Law

> **Every deployment must leave behind a functioning energy system, a satisfied responsibility, and evidence that makes the next deployment better.**

---

# 12. Partner and Open-Source Operating Model

The organization scales through **Build → Collaborate → Partner**.

External participation may include:

- contributors;
- maintainers;
- core maintainers;
- technology partners;
- integration partners;
- certified integrators;
- deployment partners;
- universities and research institutions;
- utilities;
- public institutions.

Participation is open; authority is earned through demonstrated competence and responsibility.

Code contribution authority and production-control authority remain separate trust domains.

Partners implement against shared standards rather than redefining architecture around proprietary interests.

Certification represents demonstrated capability and may be suspended or revoked when evidence no longer supports it.

The organization retains stewardship over:

- core architecture;
- common energy model;
- interoperability standards;
- control-authority model;
- security baselines;
- certification requirements;
- product direction;
- federation model;
- mission.

### Ecosystem Law

> **Scale by distributing execution while preserving interoperability through shared standards, evidence, and governance.**

---

# 13. Governance Model

Governance protects the institution; management operates it.

Authority is separated across domains including:

- mission stewardship;
- corporate governance;
- executive governance;
- technical governance;
- open-source governance;
- operational governance;
- security governance.

The mission and core organizational principles form the outer boundary within which other authorities operate.

Founder authority may be broad during the earliest stage but should progressively become institutionalized through documentation, leadership, technical ownership, governance, and succession.

Economic ownership must not automatically become unlimited technical or operational authority.

Open-source governance, corporate governance, and production-control governance remain distinct trust domains.

Conflicts of interest must be disclosed and governed.

Mission-changing and institution-threatening decisions should eventually become reserved matters requiring stronger authority than ordinary executive action.

Governance maturity increases with infrastructure responsibility—from founder-led laboratory governance through formal corporate, technical, security, operational, and institutional governance at national scale.

### Governance Law

> **No single actor should possess unnecessary unilateral authority over infrastructure whose value depends on many independent actors trusting it.**

---

# Master Operating Architecture

```text
MISSION
   ↓
ORGANIZATIONAL PRINCIPLES
   ↓
STRATEGY
   ↓
PRODUCT ROADMAP
   ↓
CURRENT EVIDENCE GATE
   ↓
PROBLEMS
   ↓
OWNERS
   ↓
WORK
   ↓
VALIDATION
   ↓
DEPLOYMENT
   ↓
OPERATIONS
   ↓
EVIDENCE
   ↓
KNOWLEDGE
   ↓
BETTER DECISIONS
   ↓
GREATER CAPABILITY
   ↺
```

The organization and its technical architecture deliberately share the same pattern:

```text
ENERGY SYSTEM
Distributed resources
+ Local autonomy
+ Shared standards
+ Higher-level coordination

ORGANIZATION
Distributed people and partners
+ Local authority
+ Shared principles and standards
+ Higher-level coordination
```

The organization therefore does not merely build distributed coordination infrastructure.

**It operates according to the same principles.**

---

# Operating Laws

1. **Problem → Understand → Build → Prove → Operate → Learn → Repeat.**
2. **Structure follows persistent responsibility.**
3. **Every important outcome has one identifiable owner.**
4. **Authority accompanies accountability.**
5. **Decisions belong at the lowest competent and sufficiently authorized level.**
6. **Current evidence gates outrank future-stage excitement.**
7. **Work is complete only when the required outcome is validated.**
8. **Status belongs in systems; human synchronization exists for decisions, coordination, and learning.**
9. **Important knowledge belongs to the organization rather than individual memory.**
10. **Production control authority is earned through evidence proportional to consequence.**
11. **Physical safety does not depend solely on coordination software.**
12. **Failures should have the smallest practical blast radius and degrade gracefully.**
13. **Open source does not mean open access.**
14. **Commercial commitments must correspond to capabilities the organization can responsibly deliver and operate.**
15. **Participation is open; authority is earned.**
16. **Commercial influence must not silently become architectural authority.**
17. **Governance protects the institution; management operates it.**
18. **No actor receives unnecessary unilateral authority over shared infrastructure.**

---

## Final Principle

> **Distribute execution. Preserve local autonomy. Standardize interfaces. Demand evidence. Coordinate at the appropriate level. Protect the mission through governance.**
