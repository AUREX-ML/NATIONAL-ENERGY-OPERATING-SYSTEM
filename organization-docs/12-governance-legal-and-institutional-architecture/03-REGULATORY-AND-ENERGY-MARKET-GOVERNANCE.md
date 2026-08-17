# Regulatory & Energy-Market Governance

## Purpose

This document defines the institutional boundaries between the National DERMS organization, energy-sector authorities, utilities, customers, aggregators, asset owners, and market participants.

> **Master Regulatory Law:** Technical capability never creates regulatory authority. Every monitoring, coordination, dispatch, aggregation, or market function must operate within explicit legal, contractual, grid-code, and delegated authority.

## Regulatory Position

National DERMS is conceived as digital coordination infrastructure. It should not claim statutory powers merely because the platform can technically perform an action.

The organization should explicitly distinguish itself from roles such as:

- Energy regulator
- Generator
- Transmission system operator
- Distribution utility
- Retail supplier
- Market operator
- Asset owner
- EPC contractor

unless the legal entity later receives the corresponding authorization.

## Regulatory Architecture

```text
Law / Regulation
       ↓
Regulator / Public Authority
       ↓
Grid & Market Rules
       ↓
Licensed / Authorized Actors
       ↓
Contracts & Delegations
       ↓
National DERMS Permissions
       ↓
Technical Enforcement
```

The platform should encode authority rather than invent it.

## Regulatory Register

Maintain a structured register of relevant requirements, including:

- Applicable law or regulation
- Responsible authority
- Applicable organizational activity
- Requirement
- Internal owner
- Required control
- Evidence
- Review date

Requirements should be validated against current authoritative Kenyan sources and qualified counsel before regulated operations begin.

## Functional Classification

Every major capability should be classified by regulatory significance.

### Observe
Telemetry collection, asset inventory, visualization, reporting.

### Analyze
Forecasting, diagnostics, optimization recommendations.

### Coordinate
Schedules, flexibility requests, constraint communication.

### Control
Remote commands that alter physical equipment behavior.

### Aggregate
Portfolio-level coordination of multiple independent resources.

### Market Participation
Offering or settling energy/flexibility services in an organized or contractual market.

Authority requirements generally increase as the system moves from observation toward physical control and market participation.

## Control Authority

Remote control must require explicit authorization.

```text
Authorized Actor
      ↓
Identity
      ↓
Role / Permission
      ↓
Asset Scope
      ↓
Operational Constraints
      ↓
Command
      ↓
Audit
```

The platform should enforce least privilege and preserve an auditable record of material control actions.

## Local Safety Supremacy

Remote orchestration never overrides local protection and safety systems.

```text
Physical Protection
      >
Local Safety Controller
      >
DERMS Optimization
```

Loss of cloud or wide-area connectivity should not make a facility physically unsafe.

## Asset Owner Rights

Asset owners should understand:

- What is monitored
- Who may access telemetry
- Who may issue commands
- Permitted purposes
- Revocation mechanisms
- Operational limits
- Failure behavior
- Data rights

Consent or contractual authorization should be explicit where required.

## Utility Interfaces

Utility integration may support visibility, constraints, flexibility requests, or control within authorized scope.

Utility authority should be translated into machine-enforceable permissions rather than unrestricted administrator access.

## Aggregation and VPP Functions

Portfolio aggregation introduces additional governance questions:

- Who has contracted each resource?
- Who is authorized to dispatch it?
- Which grid constraints apply?
- How is performance measured?
- How are revenues allocated?
- Who carries non-performance risk?
- What regulatory authorization is required?

Aggregation should be activated only after the legal and market role is established.

## Market Participation

If National DERMS eventually facilitates flexibility or energy-market transactions, distinguish:

```text
Technical Platform
Market Participant
Market Operator
Settlement Function
Regulatory Authority
```

These roles may belong to different institutions.

## Interoperability

Regulatory and institutional scalability improve when interfaces use open standards and vendor-neutral models.

Interoperability should support:

- Multi-vendor DER integration
- Clear asset identity
- Portable data
- Standardized control semantics
- Auditable permissions
- Reduced vendor lock-in

## Data Governance

Energy data can have commercial, privacy, cybersecurity, and critical-infrastructure implications.

Apply classification, access control, retention, encryption, audit, and lawful processing requirements proportionate to data sensitivity.

## Regulatory Change

Regulatory architecture is not static.

```text
Regulatory Change
      ↓
Impact Assessment
      ↓
Legal / Compliance Interpretation
      ↓
Architecture / Process Change
      ↓
Testing
      ↓
Deployment
      ↓
Evidence
```

## Engagement Principle

Regulators and public institutions should be engaged with clear descriptions of what the platform does, what it does not do, who retains authority, and how safety and accountability are enforced.

Avoid presenting future regulatory permissions as if they already exist.

## Regulatory Laws

1. Technical capability does not confer statutory authority.
2. Monitoring, analysis, coordination, control, aggregation, and market participation are governed as distinct capabilities.
3. Physical control requires explicit authorization and bounded permissions.
4. Local physical safety overrides remote optimization.
5. Asset owners retain rights consistent with ownership, contracts, and applicable law.
6. Utility access is technically constrained to legitimate authority.
7. Aggregation begins only after resource rights and regulatory obligations are established.
8. Platform, market participant, market operator, and regulator remain distinct roles.
9. Regulatory requirements map to internal owners, controls, and evidence.
10. Regulatory changes feed directly into product, architecture, and operating processes.

## Definition of Done

The regulatory architecture is complete when the organization can answer:

1. Which activities are currently unregulated, regulated, licensed, contracted, or delegated?
2. Which authorities govern each material activity?
3. What grid and market rules apply?
4. Who can view each resource?
5. Who can control each resource?
6. How is control authority granted and revoked?
7. What local safety boundaries cannot be overridden?
8. What rights remain with asset owners?
9. What authority may utilities receive?
10. What additional requirements apply to aggregation?
11. What additional requirements apply to market participation?
12. How are regulatory obligations converted into technical controls and evidence?
13. How are regulatory changes tracked and implemented?
