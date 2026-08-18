# Facility EMS Pilot Specification

## Phase II - Pilot Definition and Site Selection

| Document control | Value |
|---|---|
| Document ID | NEOS-FACILITY-EMS-PILOT-SPEC-001 |
| Version | 0.1 |
| Status | Working draft for Phase II pilot definition |
| Date | 18 August 2026 |
| Programme stage | Concept, architecture, and validation preparation |
| Classification | Programme source document |

## 1. Purpose

This specification begins Phase II of the National Energy Operating System Programme by defining how the first Facility Energy Management System pilot should be selected, scoped, evidenced, and governed.

It converts the current architecture and readiness material into a practical pilot-planning artifact. It does not identify a selected pilot site, approve implementation, claim regulatory authority, or claim that any live Facility EMS has been deployed.

The specification supports the programme progression:

```text
Facility EMS
  -> Regional DERMS
  -> National DERMS
  -> National Energy Operating System
```

The governing rule remains:

> Scale follows evidence.

## 2. Current Maturity Position

The repository currently establishes concept, architecture, governance, and validation-preparation material. It does not yet contain the evidence required to claim field implementation.

Current known gaps remain:

- no selected pilot site;
- no approved pilot mandate;
- no pilot budget or resourcing plan;
- no completed facility asset inventory;
- no baseline measurement report;
- no confirmed integration inventory;
- no live production system;
- no formal Facility EMS implementation evidence.

This document is therefore a planning and evidence-definition artifact for review, site discovery, and a Gate 1 pilot-readiness decision.

## 3. Architecture Basis

The pilot must follow the programme architecture principles:

- coordinate globally; control locally;
- preserve local autonomy and physical safety;
- normalize vendor-specific data into common energy-resource semantics;
- treat identity, authorization, cybersecurity, logging, and audit as core infrastructure;
- scale through federation and aggregation, not direct national micromanagement of every device;
- require explicit legal, contractual, operational, or delegated authority for monitoring, coordination, control, aggregation, dispatch, settlement, or market functions.

At this stage, the Facility EMS is the proving layer closest to the physical site. Regional and national capabilities remain dependent on facility-level proof.

## 4. Pilot Objective

The first Facility EMS pilot should prove whether a real facility with heterogeneous energy assets can be safely observed, represented, coordinated, and evaluated through a unified local operating layer.

The pilot objective is:

> Demonstrate that a Facility EMS can create reliable site-level energy visibility, generate useful operational recommendations, and, only where explicitly authorized, execute bounded operator-approved control while preserving local safety, asset-owner authority, and auditable evidence.

The pilot should answer:

1. Can the facility's energy assets be inventoried and represented accurately?
2. Can telemetry from different meters, devices, and systems be normalized into a trusted facility energy model?
3. Can the Facility EMS produce recommendations that operators understand and can validate?
4. Can any authorized control action be bounded, reversible, logged, and subordinate to local safety systems?
5. Does the evidence justify a second pilot, productization work, or redesign?

## 5. Site-Selection Criteria

A candidate site should be suitable enough to prove coordination, but controlled enough for a first pilot.

| Criterion | Required Evidence | Why It Matters |
|---|---|---|
| Multiple energy assets | Grid connection, meters, PV, battery, generator, EV charging, major loads, or sensors | Proves coordination rather than simple monitoring. |
| Clear operating problem | Energy cost, demand charge, outage, generator fuel, power quality, renewable curtailment, or similar pain point | Creates measurable value. |
| Cooperative owner or operator | Named site sponsor and decision owner | Enables access, data sharing, and operational feedback. |
| Electrical documentation | Single-line diagram, meter layout, panel schedules, asset manuals, or maintenance records where available | Reduces safety and integration risk. |
| Metering or monitoring feasibility | Existing smart meters, interval data, installable temporary meters, or gateway access | Enables baseline and verification. |
| Manageable safety risk | Known control boundaries, local override, and no critical dependency on experimental automation | Keeps the first pilot proportionate. |
| Integration feasibility | Known devices, protocols, network access, vendors, and data availability | Avoids selecting a site whose first barrier is unknown integration. |
| Data and consent feasibility | Clear data owner, permitted use, access rules, and retention expectations | Prevents ungoverned data collection. |
| Repeatability potential | Lessons likely transferable to similar sites | Supports productization after proof. |
| Budget and logistics feasibility | Access, installation window, local support, and cost estimate | Prevents a technically suitable but impractical pilot. |

Possible facility categories may include hotels, hospitals, campuses, commercial buildings, industrial sites, logistics depots, EV-charging depots, water infrastructure, or public-service facilities. This list is illustrative only and does not select a site.

## 6. Candidate-Site Assessment Template

Use this template for each candidate site. Do not promote a site to pilot implementation until evidence is attached or referenced.

| Field | Response |
|---|---|
| Candidate site ID | TBD |
| Facility name | TBD |
| Facility type | TBD |
| Location | TBD |
| Owner or operator | TBD |
| Site sponsor | TBD |
| Decision owner | TBD |
| Facility operating hours | TBD |
| Main energy pain point | TBD |
| Existing grid connection summary | TBD |
| Known on-site generation | TBD |
| Known storage assets | TBD |
| Known backup generation | TBD |
| Known controllable loads | TBD |
| Existing metering and monitoring | TBD |
| Electrical documentation available | TBD |
| Utility or grid-interface considerations | TBD |
| Data owner or controller | TBD |
| Required permissions | TBD |
| Physical access constraints | TBD |
| Connectivity constraints | TBD |
| Safety constraints | TBD |
| Cybersecurity constraints | TBD |
| Operational disruption risk | TBD |
| Estimated discovery effort | TBD |
| Estimated pilot complexity | TBD |
| Baseline measurement feasibility | TBD |
| Repeatability potential | TBD |
| Open questions | TBD |
| Assessment recommendation | Do not decide / proceed to discovery / hold / reject |

Use scores only as decision support. They do not replace safety, authority, or evidence review.

| Assessment Area | Score 0-3 | Notes |
|---|---:|---|
| Asset complexity | TBD | TBD |
| Measurable value potential | TBD | TBD |
| Owner/operator support | TBD | TBD |
| Metering and data availability | TBD | TBD |
| Integration feasibility | TBD | TBD |
| Safety manageability | TBD | TBD |
| Data-governance feasibility | TBD | TBD |
| Repeatability | TBD | TBD |
| Budget/logistics feasibility | TBD | TBD |
| Overall recommendation | TBD | TBD |

## 7. Asset Inventory Template

The asset inventory is required before pilot implementation. It should distinguish observation, advisory coordination, and possible control.

| Field | Response |
|---|---|
| Asset ID | TBD |
| Asset class | Grid meter / sub-meter / PV inverter / battery / generator / EV charger / HVAC / pump / process load / sensor / switchgear / other |
| Asset name or label | TBD |
| Owner | TBD |
| Operator | TBD |
| Vendor or manufacturer | TBD |
| Model | TBD |
| Rated capacity | TBD |
| Electrical location | TBD |
| Physical location | TBD |
| Existing controller or BMS/SCADA link | TBD |
| Monitoring status | Existing / installable / unavailable / unknown |
| Control status | No control / advisory only / operator-approved / automatic prohibited / unknown |
| Available measurements | TBD |
| Required measurements | TBD |
| Available commands, if any | TBD |
| Operating limits | TBD |
| Protection or interlock constraints | TBD |
| Manual override method | TBD |
| Maintenance owner | TBD |
| Documentation available | TBD |
| Criticality to facility operations | Low / medium / high / critical / TBD |
| Failure impact | TBD |
| Cybersecurity sensitivity | Low / medium / high / TBD |
| Evidence source | Document / inspection / vendor record / operator interview / TBD |
| Notes | TBD |

Minimum inventory categories include grid supply and utility metering, sub-metering, PV, battery storage, backup generation, EV charging, large controllable loads, building management or SCADA systems, network or gateway equipment, and protection or manual fallback equipment where present.

## 8. Integration and Protocol Inventory

The integration inventory should be completed before software or hardware commitments are made.

| Field | Response |
|---|---|
| Integration ID | TBD |
| Asset or system | TBD |
| Vendor/system owner | TBD |
| Interface type | Meter / inverter / BMS / generator controller / EV charger / BMS or SCADA / API / file export / manual upload / other |
| Protocol or method | Modbus TCP / Modbus RTU / MQTT / OPC UA / REST API / IEC 61850 / OCPP / BACnet / DNP3 / CSV / vendor portal / unknown / other |
| Network path | Local LAN / RS-485 / cellular / cloud API / isolated network / manual / TBD |
| Data direction | Read-only / write-only / read-write / TBD |
| Required data points | TBD |
| Available data points | TBD |
| Control commands, if any | TBD |
| Authentication method | TBD |
| Credential owner | TBD |
| Polling or event frequency | TBD |
| Time synchronization method | TBD |
| Data quality risks | TBD |
| Latency constraints | TBD |
| Availability constraints | TBD |
| Cybersecurity constraints | TBD |
| Vendor support required | Yes / no / TBD |
| Test environment available | Yes / no / TBD |
| Fallback mode | TBD |
| Integration confidence | Low / medium / high / TBD |
| Open issues | TBD |

Where a protocol is unknown, the inventory should say unknown. It should not infer integration feasibility from asset type alone.

## 9. Minimum Functional Capabilities

The first Facility EMS pilot should be scoped around minimum capabilities needed to prove value and safety.

### Required Before Observation

- site asset registry;
- meter and telemetry map;
- data access permissions;
- identity and access model;
- basic cybersecurity controls;
- data retention and permitted-use rules;
- evidence log structure;
- baseline measurement plan.

### Observation Capabilities

- collect telemetry from approved meters, devices, or data exports;
- normalize site data into common facility energy-resource semantics;
- show facility-level power, energy, status, and asset availability;
- flag missing, stale, invalid, or conflicting data;
- maintain timestamped event and data-quality logs;
- produce baseline and operating reports.

### Advisory Capabilities

- identify operating opportunities such as peak reduction, generator avoidance, battery scheduling, PV utilization, or load shifting where relevant;
- show recommended action, expected benefit, constraints, and confidence;
- allow operators to accept, reject, or comment on recommendations;
- compare recommendations with actual site operation;
- record operator feedback for evaluation.

### Operator-Approved Control Capabilities

Control is optional for the first pilot and must be explicitly authorized. If included, it must be limited to defined use cases.

Minimum control requirements:

- named control owner and approver;
- approved command list and operating limits;
- pre-command safety checks;
- local override or manual fallback;
- command logging with actor, timestamp, target, command, reason, result, and rollback status;
- test procedure before live use;
- incident and exception recording;
- ability to disable control mode quickly.

## 10. Safety and Authority Boundaries

Technical capability does not create authority. The pilot must operate only within approved site, asset, legal, contractual, data, and operational boundaries.

| Level | Description | First-Pilot Position | Required Approval |
|---|---|---|---|
| Observation | Read approved data without affecting physical operation | Allowed after data and access approval | Site sponsor, data owner, cybersecurity reviewer |
| Advisory | Generate recommendations for human review | Allowed after operating constraints are known | Site operator and pilot decision owner |
| Operator-approved control | Execute bounded commands only after explicit human approval | Conditional | Site decision owner, asset owner/operator, safety reviewer, cybersecurity reviewer |
| Automatic control | Execute commands without case-by-case human approval | Not assumed; generally out of scope | Separate approval, testing, and evidence required |
| Regional or national dispatch | Coordinate site response to external grid, market, or system commands | Out of scope | Separate legal, regulatory, contractual, and operational authority required |
| Market settlement | Use pilot data for billing, settlement, trading, or payment | Out of scope unless separately authorized | Formal commercial and regulatory basis required |

Non-negotiable boundaries:

- local protection systems remain superior to any Facility EMS action;
- facility operators retain local override and operational stop authority;
- the pilot must not bypass interlocks, protection relays, manual isolation, or manufacturer safety controls;
- no device may be controlled unless it is listed in the approved control scope;
- no remote control may be enabled without written authorization and an approved fallback procedure;
- no national deployment, government approval, regulatory approval, or production readiness may be claimed from this specification;
- any export, grid-interactive, market, billing, or settlement function requires separate authority review.

## 11. Success Criteria

Success must be measured against the pilot objective and baseline, not against national-scale ambition.

| Area | Minimum Success Criterion | Evidence |
|---|---|---|
| Site readiness | Candidate site selected through documented assessment | Candidate-site assessment and approval record |
| Inventory completeness | Key assets, meters, integrations, and constraints documented | Asset and integration inventories |
| Telemetry reliability | Approved data sources produce usable timestamped records for the pilot period | Data-quality report and logs |
| Facility model | Core assets and measurements are represented in a normalized facility energy model | Model description and validation notes |
| Operator usability | Operators can interpret the operational view and recommendations | Operator feedback and usage records |
| Advisory value | Recommendations are understandable, constraint-aware, and measurable against actual operation | Recommendation log and evaluation report |
| Safety | No unauthorized control, unsafe state, or uncontrolled dependency is introduced | Safety review, incident log, control records |
| Cybersecurity | Access, credentials, logging, and connectivity are controlled proportionate to pilot risk | Cybersecurity checklist and audit records |
| Economic or operational value | At least one value hypothesis is measured against baseline | Baseline and post-pilot comparison |
| Repeatability | Lessons support a second site or productization backlog | Evidence report and backlog |

A pilot may still be valuable if it disproves assumptions, identifies integration blockers, or recommends redesign. It should not be called successful unless evidence supports the conclusion.

## 12. Evidence Plan

Evidence should be designed before implementation begins. Each artifact should have an owner, date, source, and version.

| Evidence Artifact | Purpose | Required Before |
|---|---|---|
| Stakeholder and authority record | Shows who may approve discovery, monitoring, data access, and control | Site discovery |
| Candidate-site assessment | Compares sites and documents selection rationale | Gate 1 |
| Asset inventory | Defines what exists and what can be observed or controlled | Gate 1 |
| Integration and protocol inventory | Defines technical integration feasibility and unknowns | Gate 1 |
| Data-governance note | Defines data owner, permitted use, retention, and sharing | Observation |
| Safety boundary review | Defines operating limits, fallback, and prohibited actions | Any control planning |
| Cybersecurity minimum review | Defines identity, access, credentials, logging, and connectivity controls | Any connection to site systems |
| Baseline measurement plan | Defines metrics, sources, period, and analysis method | Baseline phase |
| Baseline measurement report | Establishes current performance before intervention | Advisory or control evaluation |
| Observation logs | Prove telemetry reliability and data quality | Evaluation |
| Recommendation logs | Capture advisory logic, expected benefit, operator decision, and outcome | Evaluation |
| Command logs, if applicable | Capture approved control action, result, and rollback | Evaluation |
| Incident and exception register | Records safety, operational, cybersecurity, and data incidents | Evaluation |
| Operator feedback record | Captures usability, trust, workflow fit, and concerns | Evaluation |
| Final pilot evidence report | Supports Gate 2 decision | Gate 2 |

## 13. Pilot Exit Gate

The pilot exit gate corresponds to Gate 2 - Facility EMS Evidence.

The decision question is:

> Did the Facility EMS pilot prove useful, safe, reliable, measurable, and repeatable enough to justify a second pilot or productization phase?

Possible outcomes:

| Outcome | Meaning |
|---|---|
| Proceed to second facility pilot | Facility-level proof is credible, but more evidence is needed across another site. |
| Productize selected capabilities | A narrow capability set is sufficiently proven for repeatable development. |
| Extend current pilot | More evidence is needed from the same site before a decision. |
| Redesign architecture or scope | Evidence shows the approach needs material change. |
| Hold | Critical authority, safety, data, funding, or technical gaps remain unresolved. |
| Stop current pilot path | Evidence does not justify continuing in the current form. |

The exit gate must not be framed as approval to build a national system. Regional and national work remain dependent on lower-level evidence and legitimate authority.

## 14. Implementation Phases

| Phase | Purpose | Outputs | Status |
|---|---|---|---|
| Phase II-A - Pilot Definition | Convert architecture into pilot-ready definition | This specification, templates, success criteria, evidence plan, initial risks | Initiated by this document |
| Phase II-B - Candidate-Site Screening | Identify and compare 2-3 possible pilot sites without claiming selection | Completed candidate-site assessments, shortlist recommendation, discovery authorization request | Pending |
| Phase II-C - Site Discovery | Confirm whether a preferred candidate can support a controlled pilot | Site profile, verified inventories, authority record, safety/cyber/data screens | Pending |
| Phase II-D - Baseline Planning and Measurement | Establish current performance before intervention | Baseline plan, source list, measurement period, baseline report | Pending |
| Phase II-E - Observation Build | Create trusted visibility before recommendations or control | Approved telemetry, facility model, dashboard or operating view, observation report | Pending |
| Phase II-F - Advisory Operation | Test recommendations without automatic control | Recommendation log, operator feedback, value estimate, advisory-performance report | Pending |
| Phase II-G - Bounded Control, If Authorized | Test limited operator-approved control where safe and explicitly authorized | Approved control list, test procedure, command log, rollback evidence | Optional / conditional |
| Phase II-H - Evaluation and Gate 2 Recommendation | Decide what the evidence supports | Final evidence report, success assessment, productization or second-site backlog, Gate 2 recommendation | Pending |

## 15. Risks and Controls

| Risk | Description | Control |
|---|---|---|
| Premature maturity claim | Documentation could be misread as evidence of deployment | Keep document status, current gaps, and exit gates explicit. |
| Unclear authority | Monitoring or control may be attempted without proper approval | Require named decision owners and written authorization by phase. |
| Unsafe control | Commands could affect facility safety or operations | Start with observation, require approved control scope, fallback, and local override. |
| Weak baseline | Value cannot be measured without credible pre-pilot data | Define baseline period, data sources, and measurement method before intervention. |
| Integration uncertainty | Vendor devices or protocols may be inaccessible or undocumented | Complete integration inventory and confidence rating before build commitments. |
| Poor data quality | Stale, missing, or conflicting data may undermine trust | Log data quality, show state confidence, and avoid control from unreliable data. |
| Cybersecurity exposure | Site systems may be exposed through weak access or credentials | Define identity, credential, network, logging, and incident controls before connection. |
| Operator rejection | The pilot may not fit facility workflows | Include operators during discovery, advisory review, and evaluation. |
| Scope creep | National, market, or automated-control ambitions may enter the first pilot | Keep out-of-scope boundaries visible and enforce Gate 1 and Gate 2 decisions. |
| Non-repeatable implementation | A bespoke pilot may not support productization | Record deployment effort, configuration choices, and reusable patterns. |
| Commercial sensitivity | Energy and operational data may reveal confidential facility information | Define permitted use, access rules, retention, and reporting constraints. |
| Budget underdefinition | Pilot may stall after discovery | Create a scoped concept note and resourcing plan before implementation. |

## 16. Immediate Next Actions

1. Identify 2-3 candidate pilot sites for non-invasive assessment.
2. For each candidate, complete the candidate-site assessment template using evidence rather than assumptions.
3. Confirm a named site sponsor and decision owner for any site advanced to discovery.
4. Collect preliminary asset, metering, tariff, operational, and documentation information where access is permitted.
5. Complete preliminary safety, cybersecurity, data-governance, and authority screens.
6. Define baseline metrics and the minimum measurement period for the preferred candidate.
7. Prepare a Facility EMS pilot concept note and budget using the evidence collected.
8. Review Gate 1 readiness: site, authority, baseline, risk controls, implementation plan, and acceptance criteria.
9. Decide whether to proceed, proceed with conditions, hold, redesign, or reject the candidate pilot path.

## 17. Related Documents

- [Pilot Readiness Brief](./pilot-readiness-brief.md)
- [Implementation Roadmap](./README.md)
- [System Architecture](../02-system-architecture/)
- [Validation Readiness Checklist](../05-governance-assurance/validation-readiness-checklist.md)
- [Decision Gate Framework](../05-governance-assurance/decision-gate-framework.md)
- [Repository Status](../../STATUS.md)
