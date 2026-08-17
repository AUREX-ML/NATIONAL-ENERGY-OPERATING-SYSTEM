# Institutional Governance & Stakeholder Accountability

## Purpose

This document consolidates the governance, legal, regulatory, and risk architecture into a durable institutional decision system.

> **Master Institutional Law:** The organization shall distribute authority according to competence, legitimate mandate, and consequence; preserve accountability through explicit decision rights, controls, and evidence; protect stakeholder interests without confusing them with operational authority; and progressively transfer critical knowledge and capability from individuals into durable institutional systems.

## Governance as a Decision System

Governance answers:

```text
Who may decide?
      ↓
What may they decide?
      ↓
Within what limits?
      ↓
Who must be consulted?
      ↓
Who is accountable?
      ↓
How is the decision reviewed?
```

Good governance should make legitimate decisions faster rather than add bureaucracy for its own sake.

## Governance Layers

### Ownership Governance
Who owns the legal entity and exercises ownership rights?

### Board Governance
Who oversees the institution, mission, executive leadership, capital, and material risk?

### Executive Governance
Who runs the organization within delegated authority?

### Operational Governance
Who makes day-to-day technical, commercial, financial, safety, security, and operational decisions?

These layers remain distinct.

## Governing Board

At sufficient maturity, board responsibilities may include:

- Mission stewardship
- Executive oversight
- Strategic oversight
- Enterprise risk oversight
- Capital governance
- Financial integrity
- Reserved matters
- Institutional succession

The board should govern the organization rather than operate the DERMS.

## Reserved Matters

Certain decisions may remain above ordinary management authority, including:

- Change of organizational purpose
- Material equity issuance
- Sale or merger
- Material borrowing
- Major acquisition
- Appointment/removal of chief executive leadership
- Material related-party transactions
- Material ownership restructuring

Exact thresholds should be defined in formal governance documents.

## Executive Authority

Executive leadership converts strategic direction into operating plans and owns organizational performance within delegated authority.

```text
Board
  ↓ strategic direction / oversight
Executive Leadership
  ↓
Operating Plan
  ↓
Organization
```

## Founder Evolution

Founder authority should progressively become institutional capability.

```text
Vision + Strategy + Product + Engineering + Business
                    ↓
            Systems & Delegation
                    ↓
              Leadership Team
                    ↓
             Mission Stewardship
```

A useful resilience question is: **What stops if the founder is unavailable for 30 days?**

Critical dependencies should be reduced through documentation, delegated authority, secondary owners, access governance, runbooks, financial controls, and succession.

## Decision Classes

Material decisions may be classified as:

- Strategic
- Financial
- Technical
- Operational
- Security
- Safety
- Regulatory
- Commercial
- People

Each class should have clear authority and escalation.

## Decision Rights Matrix

| Decision | Primary Authority | Escalation |
|---|---|---|
| Mission | Board/owners | Reserved |
| Strategy | Executive | Board where material |
| Architecture | Technology leadership | Executive if strategic |
| Production release | Engineering/Ops | Incident authority where required |
| Safety limit | Energy/Safety authority | Executive |
| Security policy | Security authority | Executive |
| Customer pricing | Commercial | Executive thresholds |
| Major expenditure | Finance/Executive | Board thresholds |
| Equity issuance | Board/owners | Reserved |
| Regulatory commitment | Authorized executive/legal | Board if material |

## Delegated Authority

Delegations should define:

- Scope
- Financial limit
- Technical limit
- Geographic limit where relevant
- Duration where relevant
- Escalation threshold

> Decisions should be made at the lowest organizational level possessing sufficient information, competence, and legitimate authority to make them safely.

## Reversibility

Governance effort should reflect consequence and reversibility.

- Reversible, low-consequence decisions can be decentralized.
- Difficult-to-reverse, high-consequence decisions require stronger review.

## Emergency Authority

Major cyberattacks, safety events, grid emergencies, or platform failures may require temporary expanded authority.

```text
Emergency
   ↓
Authorized Incident Leader
   ↓
Temporary Expanded Authority
   ↓
Action
   ↓
Audit
   ↓
Post-Incident Review
```

Emergency powers expire when the emergency ends.

## Stakeholder Architecture

Important stakeholder classes may include:

- Government institutions
- Regulators
- Utilities
- Facility owners
- Customers
- Aggregators
- Investors
- Technology partners
- Device manufacturers
- Developers and open-source contributors
- Public/community interests

For each stakeholder define interest, authority, impact, information needs, engagement mechanism, and accountability.

Stakeholder interest does not automatically confer decision authority.

## Public Institutions

Relationships with public institutions must respect statutory mandates, procurement rules, transparency obligations, public interest, data governance, and institutional accountability.

The organization collaborates with public authorities rather than substituting itself for them.

## Utility Governance

Utility relationships should define operational requirements, permitted visibility, control rights, data exchange, accountability, and technical boundaries.

Permissions should be machine-enforceable and auditable.

## Customer Governance

Customers and facility owners should be able to understand:

- Data collected
- Data access
- Equipment control rights
- Operational limits
- Revocation rights
- Service commitments
- Failure behavior

## Investor Governance

Investors may receive economic and governance rights consistent with corporate arrangements, but equity ownership does not automatically confer operational access to energy infrastructure.

```text
Equity Ownership ≠ DER Control Authority
```

## Open-Source Community Governance

Community governance should provide:

- Contribution rules
- Technical decision process
- Maintainer responsibility
- License clarity
- Security disclosure process
- Roadmap visibility

Technical steering structures may govern public APIs, canonical models, interoperability, and major architecture proposals without automatically receiving authority over corporate finance or commercial contracts.

## Committees

Create standing committees only where recurring, cross-functional, consequential decisions justify persistent collective governance.

Possible mature committees include audit/risk, technology/security, and nomination/remuneration. They are not prototype-stage requirements.

## Accountability

Every material function should have:

```text
Owner
  ↓
Objective
  ↓
Authority
  ↓
Metric
  ↓
Reporting
  ↓
Review
```

Responsibility without authority is ineffective; authority without accountability is dangerous.

## Escalation

Escalation should depend on impact, risk, urgency, and authority required:

```text
Team
 ↓
Function Lead
 ↓
Executive
 ↓
Board / Governance
```

Not every problem belongs with the founder.

## Conflict of Interest and Related Parties

Material conflicts should be disclosed, assessed, recorded, and subject to recusal where necessary. Related-party transactions require enhanced review and approval.

## Protected Escalation

At organizational scale, people need a safe route to report serious fraud, corruption, safety concerns, security violations, or major policy breaches outside ordinary reporting lines where necessary.

## Anti-Corruption

Public infrastructure exposure requires explicit controls around procurement, permits, contracts, public officials, and large capital projects. Commercial growth never justifies improper influence.

## Procurement and Vendor Governance

Purchasing should progressively follow:

```text
Requirement
   ↓
Budget
   ↓
Supplier Assessment
   ↓
Approval
   ↓
Purchase
   ↓
Receipt
   ↓
Payment
```

Critical vendors should be assessed for technical capability, cybersecurity, financial stability, support, licensing, supply continuity, data handling, and exit strategy.

## Partnership Governance

Strategic partnerships should define:

- Objective
- Contributions
- Rights
- Responsibilities
- Data
- IP
- Financial arrangements
- Decision rights
- Duration
- Exit

Use agreements appropriate to the relationship, such as MOUs for exploration, pilot agreements for controlled implementation, service agreements for commercial operations, and strategic agreements for long-term collaboration.

## Information Governance

Classify information proportionately:

- Public
- Internal
- Confidential
- Restricted

Open source does not mean open credentials, customer information, sensitive infrastructure configurations, or commercial secrets.

## Institutional Reporting

Leadership reporting should provide decision-grade information on:

- Mission and strategy
- Finance
- Product
- Operations
- Customers
- Security
- Risk
- People
- Partnerships

Board reporting should focus on strategic progress, financial position, top risks, major incidents, commercial status, regulatory developments, people, and decisions requiring governance action.

## Succession and Institutional Memory

Every critical role should progressively have a secondary owner or successor, documented responsibilities, access-transfer procedures, and knowledge-transfer mechanisms.

Important knowledge should move from individual memory into documentation, repositories, decision records, procedures, and institutional data.

A critical function with a bus factor of one is a governance risk.

## Governance Maturity

### Stage 1 — Founder-led Project
- Founder authority
- Documented decisions
- Basic financial records
- Source control
- IP clarity
- Risk register

### Stage 2 — Incorporated Startup
- Legal entity
- Cap table
- Directors
- Banking controls
- Contracts
- Delegated authority
- Basic policies

### Stage 3 — Pilot Organization
- Customer contracts
- Partner governance
- Security governance
- Pilot authority
- Incident governance
- Data governance
- Regulatory engagement

### Stage 4 — Commercial Company
- Management team
- Formal financial controls
- Board oversight
- Enterprise risk
- Service governance
- Audit/assurance
- Succession

### Stage 5 — Infrastructure Institution
- Independent governance
- Critical-infrastructure assurance
- Regulatory accountability
- Formal succession
- Public/private stakeholder governance
- Continuity
- Institutional trust

## Institutional Governance Laws

1. Governance is an architecture of legitimate decision rights, accountability, and oversight.
2. Ownership, board governance, executive management, and operational authority remain distinct.
3. Decisions are made at the lowest level possessing sufficient competence, information, and legitimate authority.
4. Governance effort increases with consequence and irreversibility.
5. Authority is explicitly delegated and bounded.
6. Emergency authority is temporary, auditable, and reviewed.
7. Stakeholder interest does not automatically confer decision authority.
8. Equity ownership does not confer direct DER control authority.
9. Stakeholder rights and responsibilities are explicitly defined.
10. Material conflicts are disclosed and governed.
11. Critical knowledge, authority, and access progressively cease to depend on one individual.
12. Succession is institutional resilience applied to people.
13. Transparency is maximized where it improves trust while legitimate security, privacy, and confidentiality remain protected.
14. Committees exist only where their decision function justifies them.
15. Governance grows with consequence without unnecessarily slowing execution.

## Domain Definition of Done

Governance, Legal & Institutional Architecture is complete when the organization can clearly answer:

1. What legal institution are we building?
2. What belongs to the founder and what belongs to the organization?
3. What belongs to third parties and open-source communities?
4. What can investors own and govern?
5. What regulatory role does the organization occupy?
6. What activities require additional authorization?
7. Who may monitor and control each energy resource?
8. What are the major enterprise risks and who owns them?
9. What controls and evidence manage those risks?
10. Who governs the organization?
11. Which matters are reserved and which are delegated?
12. Who makes technical, financial, commercial, safety, security, and operational decisions?
13. How are emergency powers handled?
14. How are conflicts of interest handled?
15. How are stakeholders represented without confusing interest with authority?
16. How are public institutions, utilities, customers, investors, partners, and contributors engaged?
17. How does institutional knowledge survive personnel changes?
18. How does founder dependency decline over time?
19. How does leadership succession work?
20. How does governance mature from prototype to national infrastructure?
21. Can the institution continue pursuing its mission when its original personnel eventually change?
