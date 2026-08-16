# Reliability, Resilience & Safety

## Objective

The system must fail predictably, contain faults, preserve physical safety, recover trustworthy state, and restore higher-level authority only after verification.

## Degradation Hierarchy

```text
NORMAL
National + Regional + Facility

↓ national unavailable

DEGRADED
Regional + Facility

↓ regional unavailable

LOCAL
Facility EMS

↓ facility EMS unavailable

DEVICE
Native device control and protection
```

The architecture should lose optimization and coordination before it loses local physical protection.

## Failure Domains

- Device
- Facility
- Region
- Nation

Failures should be contained at the smallest practical boundary.

## Recovery Lifecycle

```text
Failure
  ↓
Detect
  ↓
Isolate
  ↓
Enter Safe/Degraded Operation
  ↓
Recover
  ↓
Reconcile Physical State
  ↓
Verify
  ↓
Restore Authority
```

Restarting a process alone does not prove recovery.

## Safety Authority

```text
Physical Protection
       ↓
Device Safety
       ↓
Facility Safety
       ↓
Facility Control
       ↓
Regional Control
       ↓
National Optimization
```

Higher-level optimization is subordinate to trustworthy local physical constraints.

## Stale State

Control decisions must account for measurement age, communication health, confidence, and state validity. Stale or unknown information cannot silently be treated as current physical truth.

## Resilience Mechanisms

Depending on consequence, services may use redundancy, retries with bounded behavior, idempotency, queues, buffering, circuit breaking, backpressure, replicated storage, backups, failover, and disaster recovery.

## Testing

Resilience must be demonstrated through failure testing, including connectivity loss, delayed telemetry, device failure, service restart, partial platform outage, failed software rollout, data-store recovery, and restoration/reconciliation workflows.

---

[← Technology & Digital Infrastructure](./README.md)
