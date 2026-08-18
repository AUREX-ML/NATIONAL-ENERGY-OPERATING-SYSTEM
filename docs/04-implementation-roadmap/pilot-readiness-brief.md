# Pilot Readiness Brief

## Facility EMS First Pilot

| Document control | Value |
|---|---|
| Document ID | NEOS-PILOT-READINESS-001 |
| Version | 0.1 |
| Status | Working draft for pilot planning |
| Date | 18 August 2026 |
| Programme stage | Concept, architecture, and validation preparation |
| Classification | Programme source document |

## 1. Purpose

This document defines the recommended first pilot pathway for the National Energy Operating System Programme.

The recommended first pilot is a **Facility Energy Management System pilot** in a real, energy-intensive facility with multiple energy assets and clear operational value to measure.

The first pilot should prove facility-level coordination before any regional or national coordination claim is made.

## 2. Why Start at Facility Level

A facility is the smallest complete energy system where the programme can safely test real coordination.

A suitable facility may include:

- grid supply;
- smart or interval metering;
- solar PV;
- battery storage;
- backup generator;
- EV charging;
- controllable loads;
- HVAC or other major loads;
- protection and switching equipment;
- facility operators;
- cost, reliability, and maintenance constraints.

If the programme cannot coordinate a real facility safely, reliably, and usefully, it is not ready to coordinate regions or national systems.

## 3. Pilot Objective

The pilot objective is to demonstrate that heterogeneous facility energy assets can be observed, represented, coordinated, and operated through a unified digital layer while preserving local safety, asset-owner authority, and operator control.

The pilot should answer:

> Can one facility operate its distributed energy resources as a coordinated system and produce evidence of value?

## 4. Pilot Scope

### In Scope

- Asset inventory and site energy-system mapping.
- Metering and telemetry assessment.
- Device integration feasibility review.
- Local energy data model and facility digital twin.
- Monitoring dashboard or operational view.
- Read-only observation phase.
- Advisory optimization phase.
- Operator-approved control where safe and authorized.
- Failure-mode testing.
- Baseline and post-pilot measurement.
- Cybersecurity and access-control baseline.
- Operator feedback and training.
- Evidence report and decision gate.

### Out of Scope for First Pilot

- National dispatch.
- Market settlement.
- Unrestricted remote control.
- Peer-to-peer trading.
- Automated control without explicit acceptance.
- Critical grid operation dependency.
- Claims of national production readiness.

## 5. Candidate Pilot-Site Criteria

A credible first pilot site should have:

| Criterion | Reason |
|---|---|
| Multiple energy assets | Proves coordination, not simple monitoring. |
| Meaningful energy cost or reliability issue | Creates measurable value. |
| Cooperative facility owner/operator | Enables access, data, and operational learning. |
| Available electrical documentation | Reduces safety and integration risk. |
| Metering or installable monitoring | Enables baseline and verification. |
| Manageable operational risk | Allows controlled experimentation. |
| Clear decision owner | Prevents stalled approvals. |
| Repeatability potential | Lessons should apply to other facilities. |

Possible facility types include hotels, hospitals, industrial facilities, campuses, commercial buildings, logistics depots, EV-charging depots, water infrastructure, or public-service facilities.

## 6. Pilot Phases

### Phase 0 — Discovery

Purpose: understand the facility before any technical commitment.

Outputs:

- site profile;
- asset inventory;
- metering assessment;
- electrical single-line review where available;
- operating pain points;
- stakeholder and authority map;
- data-access requirements;
- initial risk assessment;
- pilot feasibility decision.

### Phase 1 — Baseline

Purpose: establish current performance before intervention.

Outputs:

- demand profile;
- energy cost baseline;
- reliability and outage history where available;
- generator use baseline;
- solar or storage performance where applicable;
- operational process baseline;
- data-quality assessment.

### Phase 2 — Observe

Purpose: create trusted visibility.

Outputs:

- connected telemetry;
- normalized facility energy model;
- operational dashboard;
- state-quality indicators;
- asset health and availability view;
- data gaps and integration issues.

### Phase 3 — Recommend

Purpose: test optimization logic without automatic control.

Outputs:

- recommendations;
- operator review;
- estimated value;
- constraint validation;
- comparison between recommendation and actual operation;
- acceptance or rejection reasons.

### Phase 4 — Operator-Approved Control

Purpose: test bounded control only where safe and authorized.

Outputs:

- approved control cases;
- command authorization records;
- safety checks;
- measured response;
- rollback procedure;
- operator feedback;
- incident and exception records.

### Phase 5 — Evaluation

Purpose: decide whether the pilot proved enough to continue.

Outputs:

- pilot evidence report;
- value assessment;
- safety and cybersecurity review;
- reliability review;
- operator acceptance review;
- implementation lessons;
- productization backlog;
- decision gate recommendation.

## 7. Evidence Required

The pilot should produce evidence across these categories:

| Evidence Category | Examples |
|---|---|
| Technical | Integration reliability, telemetry quality, state accuracy, control response. |
| Operational | Operator usability, incident handling, maintenance impact, workflow fit. |
| Safety | Control limits, local override, failure behaviour, protection boundaries. |
| Cybersecurity | Identity, access control, credential handling, logging, secure communications. |
| Economic | Cost savings, demand reduction, generator use reduction, avoided waste, cost to serve. |
| Environmental | Renewable utilization, fuel reduction, emissions estimate where defensible. |
| Institutional | Authority clarity, approvals, data rights, stakeholder acceptance. |
| Productization | Repeatability, deployment effort, documentation gaps, support requirements. |

## 8. Minimum Controls Before Live Operation

Before any live pilot control function is enabled, the following controls should exist:

- named facility decision owner;
- written pilot authorization;
- asset and control scope definition;
- approved operating limits;
- local override or manual fallback;
- role-based access;
- credential control;
- command logging;
- change record;
- incident contact list;
- rollback procedure;
- safety review;
- cybersecurity review proportionate to the pilot risk.

## 9. Pilot Success Criteria

The first pilot should be considered successful if it demonstrates:

- reliable visibility of key facility energy assets;
- useful normalized facility energy model;
- operator trust in the information presented;
- measurable operational or economic value;
- safe handling of failures and unavailable state;
- bounded control where explicitly authorized;
- evidence that the approach can be repeated at another facility;
- a clear productization backlog.

## 10. Decision Gate

At the end of the pilot, the decision should not be whether to build a national system.

The decision should be:

> Has Facility EMS proven enough value, safety, reliability, and repeatability to justify a second pilot or productization phase?

Possible outcomes:

- proceed to second facility pilot;
- productize selected capabilities;
- extend current pilot;
- redesign architecture;
- pause until critical gaps are resolved.

## 11. Immediate Next Actions

1. Identify 2-3 candidate pilot sites.
2. Select one preferred site for discovery.
3. Obtain permission for non-invasive site assessment.
4. Collect basic asset, metering, and energy-cost information.
5. Define pilot objectives and baseline metrics.
6. Produce a pilot concept note and budget.
7. Run legal, safety, cybersecurity, and operational review.
8. Decide whether to proceed to implementation planning.

