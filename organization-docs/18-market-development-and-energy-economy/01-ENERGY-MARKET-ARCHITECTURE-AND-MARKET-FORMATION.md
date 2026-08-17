# Energy Market Architecture & Market Formation

## Purpose

Define how NDEMS can support the transition from distributed energy infrastructure into governed energy-market participation without assuming that technical connectivity alone creates a functioning market.

## Market Formation Chain

```text
Physical DER
  ↓
Telemetry
  ↓
Observability
  ↓
Controllability
  ↓
Qualified Flexibility
  ↓
Aggregation
  ↓
Market Product
  ↓
Transaction
  ↓
Delivery
  ↓
Verification
  ↓
Settlement
```

## Market Participants

Potential actors include DER owners, facility operators, aggregators, VPP operators, utilities, system operators, market operators, settlement operators, regulators and service providers. Their responsibilities and authority must remain explicit.

## Market Formation Requirements

A viable market requires more than DER capacity. It requires resource qualification, trustworthy metering, defined products, participant rules, dispatch mechanisms, measurement and verification, settlement, dispute resolution, governance and sufficient buyer/seller participation.

## Market Layers

1. **Physical layer** — DERs, meters, grid connections and operational constraints.
2. **Digital layer** — telemetry, control, digital twins, APIs and interoperability.
3. **Coordination layer** — portfolios, forecasts, schedules and optimization.
4. **Market layer** — products, offers, commitments and transactions.
5. **Financial layer** — verification, settlement and payments.
6. **Governance layer** — authority, rules, oversight and disputes.

## Market Integrity Principles

- Connected MW is not equivalent to available flexibility.
- Availability must be time-bound and constraint-aware.
- Every market commitment must identify the responsible participant.
- Physical delivery must remain independently observable.
- Market activity must not override local safety.
- Rules and product definitions must be version controlled.
- Historical transactions must remain interpretable under the rule version that governed them.

## Market Development Stages

```text
Research
→ Simulation
→ Lab Validation
→ Field Pilot
→ Shadow Market
→ Limited Commercial Pilot
→ Production Market Service
→ Regional Scale
→ Institutional / National Integration
```

## Definition of Done

Market architecture is established when the organization can identify participants and authority; define resource qualification; distinguish technical capability from market eligibility; specify market products; maintain traceable commitments; measure delivery; settle verified performance; handle exceptions and disputes; and evolve rules under formal governance.

---

[← Domain 18](./README.md)
