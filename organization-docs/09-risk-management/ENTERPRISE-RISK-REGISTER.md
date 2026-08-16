# Enterprise Risk Register

## Purpose

The Enterprise Risk Register is the authoritative organizational view of material uncertainty capable of affecting strategy, safety, infrastructure, customers, operations, cybersecurity, finances, regulation, people, reputation, or organizational continuity.

This is a living management instrument. Ratings below are initial placeholders and must be validated against evidence as the organization moves from research into pilots and operations.

## Register Schema

Each risk should maintain:

- Risk ID
- Category
- Risk statement
- Objective at risk
- Risk owner
- Inherent likelihood
- Inherent impact
- Inherent rating
- Key controls
- Control effectiveness
- Residual likelihood
- Residual impact
- Residual rating
- Appetite / tolerance
- KRIs
- Treatment
- Action owner
- Target date
- Trend
- Status
- Last review
- Next review

## Initial Enterprise Risk Universe

| ID | Category | Risk | Initial Priority | Primary Treatment Direction |
|---|---|---|---|---|
| R-001 | Financial | Insufficient sustainable financing prevents delivery or continuity | High | Reduce / diversify |
| R-002 | Cybersecurity | Unauthorized access enables malicious or unsafe DER control | Critical | Reduce |
| R-003 | Safety | Control action contributes to unsafe physical operation or equipment damage | Critical | Avoid / reduce |
| R-004 | Operational | Central platform failure materially disrupts monitoring or coordination | High | Reduce |
| R-005 | Operational | Facility connectivity loss creates telemetry and control blind spots | High | Reduce |
| R-006 | Supply Chain | Critical dependency on a single supplier or technology creates operational fragility | High | Reduce / diversify |
| R-007 | Regulatory | Required authorization is absent, delayed, or changes materially | High | Avoid / reduce |
| R-008 | Commercial | Excessive dependence on a small number of customers weakens financial resilience | High | Reduce |
| R-009 | People | Loss or unavailability of key personnel disrupts critical capability | High | Reduce |
| R-010 | Cybersecurity | Software supply-chain compromise introduces malicious or vulnerable components | High | Reduce |
| R-011 | Data | Corrupted, incomplete, or misleading telemetry causes incorrect decisions | High | Reduce |
| R-012 | Technology / Safety | Large-scale control algorithm error produces correlated adverse behavior | Critical | Avoid / reduce |
| R-013 | Legal / IP | Open-source license or intellectual-property obligations are violated | Moderate–High | Reduce |
| R-014 | Cybersecurity / Data | Material data breach compromises protected or operational information | High | Reduce |
| R-015 | Strategic | Product fails to achieve sufficient adoption or stakeholder alignment | High | Reduce / accept within appetite |

## Example Risk Statement — R-002

> Because privileged identities, credentials, devices, or software components may be compromised, there is a risk that unauthorized commands are issued to connected distributed energy resources, resulting in equipment damage, operational disruption, safety exposure, regulatory consequences, or loss of trust.

Potential controls include:

- strong identity and authentication;
- role-based authorization;
- least privilege;
- command validation;
- asset-level operating constraints;
- immutable or protected audit logging;
- anomaly detection;
- credential rotation;
- secure device identity;
- emergency isolation and fail-safe behavior.

Potential KRIs include:

- critical privileged-access exceptions;
- failed privileged authentications;
- unsupported production gateways;
- critical vulnerabilities beyond remediation tolerance;
- unusual control-command activity.

## Example Risk Statement — R-003

> Because incorrect configuration, stale telemetry, software defects, operator error, or failed safeguards may produce an unsafe control action, there is a risk of physical harm, equipment damage, service disruption, or cascading infrastructure impact.

Potential controls include:

- validated operating envelopes;
- local interlocks;
- commissioning procedures;
- command limits;
- fail-safe behavior;
- qualified engineering review;
- maintenance lockouts;
- independent testing for high-consequence control functions.

## KRI Threshold Model

Each material KRI should define:

```text
GREEN      Within expected operating range
AMBER      Exposure approaching tolerance
RED        Tolerance breached
HARD LIMIT Immediate containment or stop where required
```

Thresholds must be evidence-based. Numerical values should not be invented merely to make the register appear complete.

## Trend

Risks should show direction:

- ↑ Worsening
- → Stable
- ↓ Improving

## Treatment Tracking

When residual exposure exceeds tolerance:

```text
Risk
 ↓
Tolerance Breach
 ↓
Treatment
 ↓
Action Owner
 ↓
Target Date
 ↓
Monitoring
 ↓
Verification
```

## Emerging Risk Watchlist

Emerging risks may include:

- changing electricity-market rules;
- AI-enabled cyberattack capability;
- new DER protocols and interoperability requirements;
- changing grid architecture;
- climate-related infrastructure stress;
- battery technology changes;
- geopolitical supply-chain disruption;
- new cybersecurity and critical-infrastructure regulation.

Emerging risks should be monitored without pretending that immature uncertainty can always be scored precisely.

## Review Triggers

The register must be reassessed after major incidents, material architecture changes, increased control authority, new jurisdictions, major customers, significant financing, regulatory change, major supplier failure, or substantial deployment growth.

## Closure

A risk may be closed only when the exposure no longer exists, has permanently changed, or has been formally absorbed into another managed risk. Historical records should be preserved as institutional memory.
