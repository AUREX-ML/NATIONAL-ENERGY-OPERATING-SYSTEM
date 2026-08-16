# Data Platform & Digital Twins

## Purpose

The data architecture creates trustworthy, interoperable representations of distributed physical infrastructure and separates operational state from raw vendor-specific data.

## Data Classes

- Master and registry data
- Configuration
- Telemetry
- Operational state
- Events
- Alarms and incidents
- Commands and responses
- Audit records
- Historical and analytical data

Each class can have different storage, retention, access, latency, and integrity requirements.

## Canonical Energy Model

The normalized resource model includes:

- Stable identity
- Resource type
- Capabilities
- Measurements
- State
- Setpoints
- Limits
- Availability
- Health
- Quality/freshness metadata

## Digital Twin Hierarchy

```text
National Twin
    ↓
Regional Twins
    ↓
Facility Twins
    ↓
Resource Twins
```

## Facility Twin

A facility twin may contain identity, location, electrical topology, resources, capabilities, measurements, operational state, health, configuration, control limits, and history.

## Data Flow

```text
Device measurement
      ↓
Edge validation
      ↓
Normalized facility state
      ↓
Regional aggregation
      ↓
National aggregation
```

Raw high-frequency data does not automatically need to propagate to every layer. Data should move according to operational purpose, latency, retention, and governance requirements.

## State Quality

State must carry sufficient evidence to distinguish fresh, stale, estimated, missing, invalid, unavailable, and unknown conditions where relevant. Unknown state must never silently become trusted control input.

## Event Architecture

Significant changes can publish domain events such as facility connection, telemetry staleness, resource unavailability, dispatch lifecycle events, alarms, and software/configuration changes.

## Historical Record

Stable identities allow operational, configuration, software, incident, maintenance, and performance histories to remain attributable throughout the asset lifecycle.

---

[← Technology & Digital Infrastructure](./README.md)
