# Validation Readiness Checklist

## National Energy Operating System Programme

| Document control | Value |
|---|---|
| Document ID | NEOS-VALIDATION-CHECKLIST-001 |
| Version | 0.1 |
| Status | Working draft for review |
| Date | 18 August 2026 |
| Programme stage | Concept, architecture, and validation preparation |
| Classification | Programme source document |

## 1. Purpose

This checklist defines the minimum validation areas that should be addressed before the National Energy Operating System Programme advances from concept and architecture into live pilot implementation.

The checklist is designed to prevent premature claims, unclear authority, unsafe technical assumptions, weak evidence, and ungoverned field deployment.

## 2. Validation Principle

The programme should advance only when evidence is sufficient for the consequence of the next decision.

```text
Claim
  ↓
Evidence Required
  ↓
Validation Owner
  ↓
Review
  ↓
Decision
```

## 3. Checklist Summary

| Area | Required Before Pilot? | Status |
|---|---:|---|
| Problem validation | Yes | Pending stakeholder review |
| Stakeholder and authority mapping | Yes | Draft created |
| Candidate pilot-site assessment | Yes | Pending |
| Facility asset inventory | Yes | Pending |
| Baseline measurement plan | Yes | Pending |
| Data access and consent | Yes | Pending |
| Safety and control boundary review | Yes | Pending |
| Cybersecurity minimum baseline | Yes | Pending |
| Legal and regulatory screening | Yes | Pending |
| Pilot budget and resourcing | Yes | Pending |
| Pilot acceptance criteria | Yes | Pending |
| Evidence and reporting plan | Yes | Pending |

## 4. Problem Validation

The programme must validate that the problem statement accurately reflects the needs of relevant stakeholders.

Minimum evidence:

- stakeholder review notes;
- confirmed problem dimensions;
- rejected or corrected assumptions;
- official or authoritative sector references;
- list of unresolved questions.

Validation questions:

- Is the coordination gap real?
- Which parts of the problem are national, regional, facility-level, regulatory, commercial, or technical?
- Which claims require stronger evidence?

## 5. Stakeholder and Authority Validation

The programme must identify who has authority over policy, regulation, system operation, distribution networks, facility access, asset control, data access, and funding decisions.

Minimum evidence:

- stakeholder map;
- authority matrix;
- engagement log;
- unresolved mandate questions;
- decision-owner list for the next phase.

Validation questions:

- Who may approve discovery?
- Who may approve pilot implementation?
- Who may authorize monitoring?
- Who may authorize control?
- Which institution must review legal or regulatory implications?

## 6. Pilot-Site Validation

The first pilot site must be appropriate for Facility EMS proof.

Minimum evidence:

- site profile;
- asset inventory;
- metering and telemetry review;
- electrical documentation where available;
- operating pain points;
- site access requirements;
- decision owner;
- pilot risk screen.

Validation questions:

- Does the site have enough energy-system complexity to prove coordination?
- Is the site manageable enough for a first pilot?
- Is there a clear operational problem to measure?
- Is the owner or operator willing to support the pilot?

## 7. Technical Readiness

The pilot should not proceed until the team understands what must be integrated and what technical uncertainty remains.

Minimum evidence:

- asset and device list;
- protocol and integration assessment;
- telemetry requirements;
- edge-compute requirements;
- connectivity assessment;
- system architecture for the pilot;
- known technical risks;
- test plan.

Validation questions:

- Which devices are read-only?
- Which devices may be controllable?
- Which integrations are standard, custom, or unknown?
- What happens when communications fail?

## 8. Safety and Control Readiness

Any control function must be bounded, authorized, auditable, and reversible.

Minimum evidence:

- control-scope definition;
- operating limits;
- local override procedure;
- fallback mode;
- safety review;
- command logging design;
- control acceptance criteria;
- emergency contact and escalation list.

Validation questions:

- Can the pilot run safely in observation-only mode?
- Which control actions are allowed, if any?
- Who approves each control mode?
- Can the site return to normal operation quickly?

## 9. Cybersecurity Readiness

Cybersecurity must be treated as a pilot entry condition, not an afterthought.

Minimum evidence:

- identity and access model;
- credential handling plan;
- network connectivity model;
- encryption approach where applicable;
- logging and audit design;
- update and patch approach;
- incident contact list;
- minimum threat review.

Validation questions:

- Who has access to the system?
- How are credentials issued, stored, rotated, and revoked?
- What systems are exposed to external networks?
- What logs will exist for review?

## 10. Data Governance Readiness

The pilot must define what data is collected, why it is collected, who may access it, how long it is retained, and how it may be used.

Minimum evidence:

- data inventory;
- data owner or controller identification;
- permitted use;
- access rules;
- retention rules;
- sharing rules;
- privacy and confidentiality screening;
- reporting format.

Validation questions:

- Is personal, customer, commercial, or operationally sensitive data involved?
- Who can approve data access?
- Can data be used for research, reporting, or product development?
- What data must be anonymized or aggregated?

## 11. Economic and Impact Readiness

The pilot must define how value will be measured before implementation begins.

Minimum evidence:

- baseline period;
- energy-cost baseline;
- demand or reliability baseline;
- generator or fuel baseline where relevant;
- expected value hypotheses;
- measurement method;
- cost-to-serve estimate;
- post-pilot evaluation plan.

Validation questions:

- What would count as success?
- What would count as failure?
- How will value be separated from normal variation?
- What costs must be included?

## 12. Legal and Regulatory Readiness

The pilot must be screened for legal, regulatory, contractual, licensing, grid-code, safety, data-protection, and liability implications.

Minimum evidence:

- regulatory screening note;
- legal authority questions;
- contract or permission requirements;
- liability assumptions;
- data-protection screening;
- grid interconnection considerations where relevant;
- list of approvals required before live operation.

Validation questions:

- Is the pilot only monitoring, or does it affect physical operation?
- Does the pilot interact with utility metering, billing, grid export, or settlement?
- Are any regulated activities triggered?
- What approvals are required before each phase?

## 13. Evidence Reporting

Every pilot should produce a final evidence report.

Minimum report contents:

- pilot objectives;
- site description;
- baseline;
- implementation summary;
- technical results;
- operational results;
- safety and cybersecurity findings;
- economic and impact findings;
- incidents and exceptions;
- lessons learned;
- decision recommendation.

## 14. Readiness Decision

Before pilot implementation, the programme should make one of four decisions:

| Decision | Meaning |
|---|---|
| Proceed | Minimum readiness is satisfied. |
| Proceed with conditions | Pilot may proceed after named controls or approvals are completed. |
| Hold | Critical gaps must be resolved before proceeding. |
| Stop / redesign | The proposed pilot is not suitable. |

