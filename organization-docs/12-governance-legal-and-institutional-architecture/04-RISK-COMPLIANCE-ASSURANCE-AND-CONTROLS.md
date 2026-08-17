# Risk, Compliance, Assurance & Internal Controls

## Purpose

This document defines how the organization identifies uncertainty against its objectives, assigns ownership, implements controls, generates evidence, and gains assurance that material risks remain within acceptable boundaries.

> **Master Risk Law:** The organization shall identify uncertainty against its objectives, assign clear ownership, maintain controls proportional to consequence, generate evidence that those controls operate, and continuously convert incidents, changing conditions, and assurance findings into better decisions.

## Risk Architecture

```text
Mission
  ↓
Objectives
  ↓
Risks
  ↓
Controls
  ↓
Evidence
  ↓
Assurance
  ↓
Governance
```

Risk management begins with organizational objectives rather than generic checklists.

## Enterprise Risk Taxonomy

Material risks may include:

- Strategic
- Financial
- Technology
- Cybersecurity
- Operational
- Safety
- Regulatory
- Legal
- Data and privacy
- Commercial
- People
- Partner / third-party
- Supply-chain
- Reputational

## Risk Register

Each material risk should record:

| Field | Purpose |
|---|---|
| Risk ID | Stable identifier |
| Category | Risk domain |
| Description | What could happen |
| Cause | Why it could happen |
| Impact | Consequence |
| Likelihood | Probability assessment |
| Inherent risk | Exposure before controls |
| Controls | Existing mitigation |
| Residual risk | Exposure after controls |
| Owner | Accountable person/function |
| Treatment | Avoid, reduce, transfer, accept |
| Status | Current condition |

## Risk Scoring

A simple early-stage model may use:

```text
Risk Score = Likelihood × Impact
```

Scores support prioritization rather than pretending uncertainty can be measured with perfect precision.

Impact assessment should consider safety, grid operation, customers, finance, legal exposure, regulation, data, reputation, and mission.

## Risk Appetite

Risk appetite varies by consequence.

Typical posture:

- Reversible technology experimentation — moderate tolerance
- Financial experimentation — controlled tolerance
- Production outage — low tolerance
- Cybersecurity compromise — very low tolerance
- Unauthorized infrastructure control — extremely low tolerance
- Physical safety — extremely low tolerance
- Fraud — extremely low tolerance

Risks above delegated tolerance require treatment or escalation.

## Risk Ownership

Every material risk has one accountable owner. A risk owner may depend on several control owners, but accountability for the overall exposure remains identifiable.

```text
Risk Owner → overall exposure
Control Owner → specific mitigation
```

## Risk Treatment

Four standard treatments:

- Avoid
- Reduce
- Transfer
- Accept

Residual risk acceptance requires appropriate delegated authority.

## Controls

Controls may be technical, procedural, contractual, physical, financial, or governance-based.

### Preventive
Stop an undesirable event from occurring.

Examples: access control, segregation of duties, local safety limits, code review, input validation.

### Detective
Identify undesirable conditions.

Examples: monitoring, audit logs, reconciliation, anomaly detection, security alerts.

### Corrective
Restore acceptable operation.

Examples: rollback, backup restoration, account revocation, failover, incident response.

For high-consequence risks use layered controls:

```text
Prevent → Detect → Contain → Recover → Learn
```

## Internal Controls

Important financial controls include:

- Payment authorization
- Bank reconciliation
- Expense approval
- Procurement approval
- Accounting records
- Asset register

Important technical controls include:

- Peer review
- Protected production access
- Change approval
- Deployment records
- Audit logging
- Separation of high-risk privileges

## Change Control

Material production changes should follow:

```text
Change Request
     ↓
Risk Assessment
     ↓
Review
     ↓
Approval
     ↓
Deploy
     ↓
Verify
     ↓
Record
```

Emergency changes may use accelerated procedures but remain auditable and subject to retrospective review.

## Control Library

Reusable controls should receive stable identifiers and definitions.

Example:

```text
CTRL-IAM-001
Name: Production MFA
Objective: Prevent unauthorized privileged access
Owner: Security
Evidence: Authentication records
```

## Compliance

Compliance requirements may originate from law, regulation, grid codes, licenses, contracts, standards, and internal policies.

Map requirements to reusable controls:

```text
Requirement
    ↓
Control
    ↓
Owner
    ↓
Evidence
    ↓
Status
```

One strong control may satisfy several obligations.

## Evidence

Evidence may include:

- System logs
- Configuration records
- Approval records
- Test results
- Signed agreements
- Reconciliations
- Incident records
- Deployment records

Prefer evidence generated naturally through operation where practical.

## Assurance

Assurance tests both:

1. **Design effectiveness** — is the control appropriately designed?
2. **Operating effectiveness** — does the control actually operate as intended?

Assurance may progress from control-owner self-assessment to independent security testing, financial audit, safety assessment, internal audit, external audit, or regulatory inspection as consequence increases.

## Control Exceptions

Exceptions require:

- Owner
- Rationale
- Risk assessment
- Compensating controls
- Expiry date

Exceptions must not become invisible permanent architecture.

## Key Indicators

### Key Risk Indicators
Possible examples:

- Unsupported software percentage
- Privileged account count
- Critical vulnerabilities overdue
- Customer concentration
- Cash runway
- Maintenance backlog
- Unresolved critical incidents

### Key Control Indicators
Possible examples:

- Production accounts protected by MFA
- Changes peer-reviewed
- Backups successfully tested
- Critical commands audited
- Vendors risk-assessed

## Incident Feedback

```text
Incident / Near Miss
       ↓
Root Cause
       ↓
Control Failure?
       ↓
Risk Reassessment
       ↓
Control / Architecture Improvement
```

Incidents and near misses are inputs to institutional learning.

## Business Continuity

Identify critical functions and define minimum operating capability during disruption.

Potential critical functions include:

- Energy operations
- Security response
- Customer support
- Platform operations
- Financial access
- Stakeholder communication

Business continuity keeps the institution functioning; disaster recovery restores supporting technology.

## Crisis Management

Major cyber incidents, serious safety events, national platform failures, financial crises, or major legal events may require temporary crisis governance with clear leadership, expanded but bounded authority, communications responsibilities, and post-crisis review.

## Risk Culture

The organization should reward early reporting of problems, errors, safety concerns, and unknown conditions. Accurate risk information is more valuable than artificially positive reporting.

Learning does not eliminate accountability for negligence, fraud, malicious actions, or deliberate policy violations.

## Maturity Path

### Prototype
- Top risks identified
- Owners assigned
- Critical controls documented
- Source control protected
- Financial records maintained
- Backups verified

### Pilot
- Security and safety reviews
- Incident response
- Data governance
- Change management
- Third-party review
- Risk register operational

### Commercial
- Formal financial controls
- Vendor management
- Business continuity
- Compliance monitoring
- Periodic control testing

### Infrastructure Scale
- Independent assurance
- Continuous security monitoring
- Formal audit
- Regulatory reporting
- Resilience testing
- Supply-chain assurance
- Crisis management

## Risk & Assurance Laws

1. Risk management begins with organizational objectives.
2. Every material risk has one accountable owner.
3. Inherent risk, control effectiveness, and residual risk are assessed separately.
4. Risk appetite varies by consequence.
5. Risks above tolerance are treated or escalated.
6. High-consequence risks use layered controls.
7. Controls require owners and evidence.
8. Compliance requirements map to reusable controls where possible.
9. Assurance tests design and operating effectiveness.
10. Exceptions are explicit, compensated, and temporary.
11. Incidents and near misses update risk understanding.
12. Business continuity protects critical institutional functions.
13. Independent assurance increases with infrastructure consequence.

## Definition of Done

The risk architecture is complete when material risks are identifiable, owned, scored, treated, controlled, evidenced, periodically reviewed, and escalated according to defined authority; critical functions have continuity strategies; and governance can determine whether the organization is operating within accepted risk boundaries.
