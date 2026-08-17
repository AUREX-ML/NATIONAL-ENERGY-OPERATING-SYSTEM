# Market Products, Transactions & Settlement

## Purpose

Define the controlled lifecycle through which qualified flexibility becomes a market product, commitment, physical delivery, verified transaction and financial settlement.

## Market Product Specification

Every product should define product ID, service objective, eligible resources, location, direction, capacity unit, energy unit, availability window, response time, duration, ramp requirements, activation method, baseline method, measurement requirements, verification rules, settlement formula, penalty rules and version.

## Transaction Lifecycle

```text
QUALIFICATION
 ↓
OFFER
 ↓
VALIDATION
 ↓
ACCEPTANCE / CLEARING
 ↓
RESERVATION
 ↓
COMMITMENT
 ↓
ACTIVATION / DISPATCH
 ↓
DELIVERY
 ↓
MEASUREMENT
 ↓
VERIFICATION
 ↓
SETTLEMENT
 ↓
PAYMENT / RECONCILIATION
```

## Commitment Integrity

A commitment should record participant, product, quantity, location, delivery interval, price, responsible portfolio/resources, rule version and status. Reserved capacity must be protected against double commitment.

## Measurement & Verification

M&V determines whether contracted delivery occurred. The method must define source meters, time synchronization, baseline where applicable, data-quality rules, missing-data treatment, tolerance, calculation method and audit evidence.

## Settlement

Settlement converts verified delivery into financial obligation.

Conceptually:

```text
SETTLEMENT VALUE
=
VERIFIED DELIVERY VALUE
+ ADJUSTMENTS
- PENALTIES
```

The exact formula is product-specific and version-controlled.

## Settlement States

```text
PROVISIONAL
→ REVIEWED
→ DISPUTED (if applicable)
→ ADJUSTED
→ FINAL
→ PAID / RECONCILED
```

## Financial Controls

- Transaction and settlement identifiers remain immutable.
- Settlement is reproducible from retained evidence.
- Adjustments never silently overwrite original calculations.
- Rule and formula versions remain attached to historical settlements.
- Material settlement approvals should be separated from calculation where appropriate.
- Disputed amounts remain explicitly identified.

## Failure Handling

The system must support missing telemetry, invalid meter data, partial delivery, communications failure, resource substitution where rules allow, late data, settlement corrections and disputes.

## Audit Chain

```text
PRODUCT VERSION
→ OFFER
→ COMMITMENT
→ DISPATCH
→ METER DATA
→ M&V RESULT
→ SETTLEMENT
→ ADJUSTMENT
→ FINALITY
```

## Definition of Done

The organization can define versioned market products; qualify participants/resources; receive and validate offers; reserve capacity; maintain commitments; activate delivery; measure and verify outcomes; calculate reproducible settlements; process adjustments and disputes; and retain a complete audit trail.

---

[← Domain 18](./README.md)
