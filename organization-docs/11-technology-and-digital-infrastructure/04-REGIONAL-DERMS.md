# Regional DERMS Architecture

## Role

Regional DERMS aggregates and coordinates a portfolio of independently operable facilities. It is the primary fleet-management and regional coordination layer.

## Architecture

```text
Facility EMS ─┐
Facility EMS ─┼──→ Regional DERMS
Facility EMS ─┤
Facility EMS ─┘
```

## Responsibilities

- Facility registry and lifecycle management
- Fleet telemetry and state aggregation
- Regional digital twin
- Flexibility aggregation
- Regional forecasts
- Dispatch allocation
- Regional optimization
- Event and alarm processing
- Fleet health
- Software/configuration cohort management
- Regional operations and incident management

## Capability Aggregation

Regional DERMS consumes normalized facility capability rather than manufacturer-specific device details.

Example:

```text
Facility A: 100 kW available
Facility B: 250 kW available
Facility C:  50 kW available
Facility D: unavailable
-----------------------------
Regional usable flexibility: 400 kW
```

Actual calculations must respect technical constraints, confidence, availability, contractual permissions, grid constraints, and operational policy.

## Dispatch

Regional dispatch converts a regional objective into bounded facility objectives. Each facility retains authority to validate commands against local constraints and current physical state.

## Failure Boundary

Regional failure must not remove safe facility operation. Facilities continue locally and reconcile state when regional services recover.

## Regional Digital Twin

The regional representation includes facilities, DER capacity, current state, availability, flexibility, forecasts, active dispatch, health, alarms, incidents, and operational history.

## Scaling Principle

Regional services manage facilities as standardized energy units. This prevents national infrastructure from becoming tightly coupled to individual field devices.

---

[← Technology & Digital Infrastructure](./README.md)
