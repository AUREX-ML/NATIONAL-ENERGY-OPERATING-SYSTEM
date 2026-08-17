# Session 1 — National Deployment Architecture & Infrastructure Scaling

## Purpose

Define how a validated DERMS capability progresses from individual facilities to regional and national deployment without sacrificing safety, interoperability, observability or operational accountability.

## Deployment Hierarchy

```text
DEVICE
  ↓
FACILITY
  ↓
MULTI-SITE PORTFOLIO
  ↓
REGIONAL COORDINATION
  ↓
MULTI-REGION
  ↓
NATIONAL PLATFORM
```

The facility remains the smallest complete operational deployment unit. National scale is built by coordinating autonomous facilities, not by eliminating local control.

## Deployment Maturity

A resource may be:

1. Discovered
2. Registered
3. Observable
4. Managed
5. Safely controllable
6. Service-enabled
7. Market-enabled

These states must not be treated as equivalent.

## Site Readiness

Before onboarding, each site should have evidence for:

- Ownership and operator identity
- Electrical topology
- DER inventory
- Metering and telemetry
- Communications
- Protocol compatibility
- Cybersecurity prerequisites
- Control boundaries
- Safety constraints
- Commissioning acceptance
- Operations ownership

## Deployment Waves

Scale proceeds through evidence-gated waves:

```text
LAB → REFERENCE SITE → MULTI-SITE → REGIONAL → MULTI-REGION → NATIONAL
```

Each wave must prove the assumptions required for the next.

## Standardization

National scaling depends on reusable:

- Site profiles
- Device profiles
- Data models
- Protocol adapters
- Commissioning procedures
- Security baselines
- Monitoring templates
- Acceptance tests
- Operations handover packages

## National Infrastructure Principle

The national layer coordinates shared services, visibility and policy while preserving local device protection and facility autonomy.

## Key Controls

- No site enters production without an identified owner and operator.
- Control authority is explicit and revocable.
- Deployment evidence is retained.
- Unsupported device/protocol combinations are not silently accepted.
- Expansion is blocked when operational capacity cannot sustain it.
- National-platform failure must not defeat local electrical safety.

## Status

**Session 1: COMPLETE**

---

[← Domain 19](./README.md)
