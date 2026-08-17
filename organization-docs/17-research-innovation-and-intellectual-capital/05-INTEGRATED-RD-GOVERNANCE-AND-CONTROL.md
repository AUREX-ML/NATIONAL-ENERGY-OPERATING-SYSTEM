# Integrated R&D Governance & Control

## Purpose

This document integrates research, experimentation, interoperability, standards, conformance, open source and intellectual-capital governance into one R&D operating model.

> Research creates knowledge. Governance determines which knowledge is trustworthy enough to become infrastructure.

## Integrated R&D Loop

```text
Strategic Unknown
      ↓
Research Agenda
      ↓
Question / Hypothesis
      ↓
Experiment
      ↓
Evidence
      ↓
Validation
      ↓
Decision
      ↓
Architecture / Standard / Product / Operations
      ↓
Deployment
      ↓
Field Evidence
      ↓
Learning
      ↓
New Research
```

## Governance Hierarchy

```text
Research Policy → Research Agenda → Program → Project → Question → Experiment
```

This keeps experiments connected to strategic uncertainty and prevents research activity from becoming detached from institutional decisions.

## Evidence Hierarchy

Evidence may progress from assumption and expert judgment through simulation, laboratory observation, repeated laboratory evidence, controlled field evidence, multi-site field evidence and production evidence. Strength is evaluated for relevance, quality, reproducibility, representativeness, independence, coverage, recency and uncertainty.

## Claim-to-Evidence Discipline

Consequential claims must point to appropriate evidence. If evidence does not exist, the statement remains a hypothesis. Public and internal documentation should distinguish concept, hypothesis, simulated, lab-validated, field-validated and production-proven capability.

## R&D Gates

```text
G0 Question
G1 Research Approved
G2 Experiment Valid
G3 Concept Proven
G4 Laboratory Validated
G5 Field Validated
G6 Production Qualified
G7 Scale Qualified
```

Gate outcomes are pass, pass with conditions, rework, hold or stop. TRL describes technology maturity; a gate describes permission to progress.

Production qualification considers function, safety, security, reliability, operability, maintainability, supportability and documentation. Scale qualification additionally requires multi-site evidence, repeatable deployment, support model, economics, security at scale and field reliability.

## Separation of Responsibilities

Consequential work distinguishes researcher, reviewer, decision owner, implementer and assurance responsibilities. Early-stage organizations may combine roles, but responsibilities remain explicit.

## Transfer Governance

Research transfers through explicit paths:

```text
RQ → Experiment → Finding → ADR → Implementation
```

```text
Research → RFC → Reference Implementation → Conformance Test → Standard
```

```text
Research → Validated Capability → Product Requirement → Engineering → Release
```

Operational findings may instead become procedures, runbooks, alerts, maintenance rules or training.

## Research Debt & Stop Decisions

Research debt includes untested critical assumptions, missing field evidence, stale data, unreproduced results, unverified scale claims and uncertified integrations. Governance must permit work to stop when evidence shows insufficient value, unacceptable risk, technical infeasibility, unsustainable cost or a superior existing solution.

## Review Cadence

- Regular research review: active experiments, blockers, evidence, failed hypotheses, debt and transfer decisions.
- Portfolio review: strategic alignment, resource allocation, TRL movement, field validation and stop/scale decisions.
- Research agenda review: technology, market, regulatory, grid and organizational changes.

## Revalidation

Material software, firmware, protocol, model, security, operating-environment, deployment-scale or regulatory changes may trigger revalidation. Evidence can expire when its underlying conditions no longer represent the current system.

## Stage Integrity

`CURRENT-STAGE.md` should state organizational stage, product stage, current TRL, deployment scale, validated and experimental capabilities, unvalidated assumptions, active pilots, blockers and next evidence gate.

> The institution describes itself according to demonstrated maturity, not intended maturity.

## Integrated Controls

- RD-01 Strategic research alignment
- RD-02 Research question ownership
- RD-03 Research protocol
- RD-04 Experimental reproducibility
- RD-05 Data lineage
- RD-06 Safety review
- RD-07 Security review
- RD-08 Evidence quality
- RD-09 Independent review
- RD-10 Technology readiness
- RD-11 Field validation
- RD-12 Research-to-architecture transfer
- RD-13 Research-to-standard transfer
- RD-14 Research-to-product transfer
- RD-15 IP/provenance governance
- RD-16 Open-source contribution governance
- RD-17 Conformance validation
- RD-18 Research debt management
- RD-19 Revalidation
- RD-20 Stage-status integrity

## Master Control Laws

1. Research follows strategically important uncertainty.
2. Every consequential question has an accountable owner.
3. Evidence retains method, environment, lineage, limitations and version context.
4. Evidence strength is proportional to decision consequence.
5. Unsupported claims remain hypotheses.
6. Technology maturity and permission to progress are distinct.
7. Prototypes do not become production systems because they worked once.
8. Field-scale claims require field evidence.
9. National-scale claims require evidence appropriate to national consequence.
10. Research transfers through explicit decisions.
11. Negative results and rejected paths remain institutional knowledge.
12. Research cannot independently authorize production, certification or operational control.
13. Critical research debt remains visible.
14. Material changes can trigger revalidation.
15. Current-stage documentation reflects demonstrated maturity rather than ambition.

## Master R&D Law

> The organization shall convert strategically important uncertainty into governed questions, reproducible experiments, traceable evidence and explicit decisions; progressively validate technology from simulation through laboratory, field and production environments; transfer validated findings deliberately into architecture, products, standards and operations; preserve uncertainty, negative results and institutional knowledge; and require increasingly strong evidence as the consequence and scale of infrastructure responsibility increase.
