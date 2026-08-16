# National DERMS Architecture

## Role

National DERMS provides national visibility and coordination across regional distributed-energy capability. It coordinates regional systems rather than directly micromanaging field devices.

## Architecture

```text
Region A ─┐
Region B ─┼──→ National DERMS
Region C ─┤
Region N ─┘
```

## Responsibilities

- National DER registry
- National situational awareness
- Regional capability aggregation
- National forecasting
- National flexibility visibility
- Cross-region coordination
- System-wide optimization
- Dispatch coordination
- Grid/utility integration
- Market integration where applicable
- National operations and analytics

## Hierarchical Dispatch

```text
National Objective
       ↓
Regional Allocation
       ↓
Facility Allocation
       ↓
Resource Control
       ↓
Physical Response
```

Physical response is measured and propagated upward to close the loop.

## National Digital Twin

The national operational representation contains regions, facilities, DER capacity, aggregate state, availability, flexibility, dispatch, incidents, and maintenance/operational conditions appropriate to national coordination.

## System Boundary

National DERMS is a digital coordination platform. It does not replace physical protection, device controllers, Facility EMS, utility control systems, regulators, or electricity-market institutions. It integrates with them through governed interfaces.

## Authority Principle

National authority is broad but bounded. A national objective cannot override physical protection, device constraints, facility safety envelopes, authorization policy, or trustworthy-state requirements.

## Evolution

National capability is introduced after facility and regional operating models have been proven. National scale should be the federation of proven regional capability, not a premature centralization of unproven field control.

---

[← Technology & Digital Infrastructure](./README.md)
