# Facility EMS & Edge Architecture

## Role

The Facility EMS is the smallest complete operational unit of the architecture. It connects heterogeneous physical resources and presents the facility upstream as a normalized, manageable energy system.

## Architecture

```text
DER Devices
    ↓
Industrial Protocols
    ↓
Device Adapters
    ↓
Canonical Energy Model
    ↓
Facility EMS
    ↓
Secure Upstream Interface
```

## Device Integration

Supported integrations may include Modbus TCP/RTU, SunSpec, MQTT, CAN, HTTP APIs, IEC protocols, and vendor-specific APIs.

Adapters isolate manufacturer-specific implementation details from higher-level energy logic.

## Facility EMS Responsibilities

- Discover/configure supported resources
- Acquire and validate telemetry
- Normalize measurements and capabilities
- Maintain facility/resource digital twins
- Execute local optimization
- Enforce local safety envelopes
- Translate normalized setpoints into device commands
- Buffer data during upstream outages
- Reconcile state after reconnection
- Publish health, capability, telemetry, and events upstream
- Support remote diagnostics and managed software/configuration

## Edge Computing

The prototype edge computer may use NVIDIA Jetson hardware, but the architecture does not depend on one hardware platform. Edge compute must provide sufficient reliability, storage, communications, security, and local processing for the target facility.

## Local Control Path

```text
Objective / Setpoint
       ↓
Authorization & Policy
       ↓
Facility EMS
       ↓
Safety Validation
       ↓
Device Adapter
       ↓
Physical Resource
       ↓
Measured Response
```

## Local Autonomy

During loss of WAN, Regional DERMS, or National DERMS connectivity, the Facility EMS retains bounded local functionality. It must never require continuous central connectivity for fundamental physical safety.

## Facility Definition of Done

A facility implementation is architecturally valid when it can:

- Observe supported resources as one system
- Maintain stable identities and normalized state
- Safely coordinate supported controllable resources
- Continue bounded local operation during upstream loss
- Distinguish stale, unknown, unavailable, and healthy states
- Buffer/reconcile appropriate data
- Expose auditable remote interfaces

---

[← Technology & Digital Infrastructure](./README.md)
