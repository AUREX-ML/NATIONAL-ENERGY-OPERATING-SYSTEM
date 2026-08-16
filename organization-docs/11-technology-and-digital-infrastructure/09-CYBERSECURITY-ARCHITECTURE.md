# Cybersecurity & Critical Infrastructure Architecture

## Principle

Cybersecurity is a cross-cutting property of the National DERMS, not a feature attached after implementation.

## Trust Model

```text
Device
  ↓ verify
Facility Edge
  ↓ verify
Regional Platform
  ↓ verify
National Platform
  ↓ verify
External Systems
```

Network location alone does not establish trust.

## Security Capabilities

- Identity lifecycle management
- Device/service/user authentication
- Role- and policy-based authorization
- Credential and certificate management
- Encryption in transit and at rest where required
- Secrets management
- Network segmentation
- Secure software supply chain
- Vulnerability and patch management
- Security logging and audit
- Incident detection and response
- Backup and recovery protection

## Control Security

Material control requests follow:

```text
Identity
  ↓
Authentication
  ↓
Authorization
  ↓
Policy / Scope
  ↓
Command Limits
  ↓
Fresh-State Validation
  ↓
Local Safety Validation
  ↓
Execution
  ↓
Audit
```

## Least Privilege

Facility, regional, national, service, and external-party permissions are bounded to required functions and resources. A common platform does not imply universal control authority.

## Critical Infrastructure Boundary

Compromise of one user, service, facility, or region should not automatically provide authority over unrelated infrastructure. Architecture must minimize blast radius through segmentation, scoped identity, and failure/security boundaries.

## Software Supply Chain

Production artifacts should be traceable to source and build processes. Dependencies, versions, releases, and fleet deployments must be identifiable and auditable.

## Security Operations

Security events integrate with observability and incident management while preserving appropriate access restrictions. Recovery includes credential rotation, containment, restoration, verification, and reconciliation of physical state where control systems are involved.

---

[← Technology & Digital Infrastructure](./README.md)
