# Kenya National Energy Operating System
## Problem Statement and Needs Assessment

| Document control | Value |
|---|---|
| **Document ID** | NEOS-PROBLEM-STATEMENT-001 |
| **Version** | 0.1 |
| **Status** | Working draft for validation and approval |
| **Date** | 23 July 2026 |
| **Document owner** | National Energy Operating System Programme |
| **Classification** | Project source — controlled working document |
| **Supersedes** | `problem-statement.txt` |
| **Related document** | `NEOS-PROJECT-DEFINITION-001-v0.1.md` |
| **Next review trigger** | Completion of stakeholder consultation, baseline studies, regulatory interpretation, pilot selection, or formal programme approval |

---

## 1. Purpose

This document defines the problem that the proposed Kenya National Energy Operating System (NEOS) programme is intended to address.

It is deliberately **solution-neutral at problem-definition level**. The problem is not that Kenya lacks a specific software product. The problem is that the electricity sector does not yet have a complete, nationally governed, interoperable, secure, and operationally accepted capability for coordinating eligible distributed energy resources across local control, system operation, network constraints, market participation, metering, data exchange, and settlement processes.

The document distinguishes:

- verified conditions supported by official sources;
- reasonable engineering inferences that require validation;
- project hypotheses to be tested through discovery and pilots; and
- unsupported claims removed from the original source.

---

## 2. Problem statement

Kenya's electricity sector is entering a more complex operating environment characterised by rising demand, expanding regional power trade, increasing adoption of distributed solar and storage, new net-metering arrangements, electricity-market reform, open-access provisions, and growing electric-mobility demand.

The Energy (Electricity Market, Bulk Supply and Open Access) Regulations, 2026 establish a regulated electricity-market framework and provide pathways for eligible participants to use transmission and distribution networks. These arrangements remain subject to licensing, technical assessment, system-operator coordination, approved contracts, Grid Code compliance, metering, energy accounting, network capacity, congestion management, and regulatory approval. They do not create unrestricted electricity trading or remove the responsibilities of licensed system, transmission, distribution, and retail operators.

At the same time, the Energy (Net-Metering) Regulations, 2024 permit qualified consumers to operate approved generation in parallel with a distribution network under defined capacity limits, metering requirements, interconnection controls, and billing rules. The regulations require smart bi-directional meters with two-way communication and provide for unused credits to be forfeited at the end of the licensee's financial year.

These reforms increase the number of assets, participants, measurements, operating limits, contracts, and settlement relationships that must be coordinated. Existing utility and regulatory systems may support parts of these functions, but the NEOS programme has not yet established evidence of a unified capability that can securely and consistently:

1. register and identify participating distributed assets;
2. obtain timely, validated, and time-synchronised operational data;
3. represent asset availability, owner consent, network limits, and dispatch constraints;
4. coordinate local optimisation with authorised system and network operations;
5. support scalable aggregation of flexible generation, storage, charging, and demand;
6. exchange information across utility, market, regulatory, billing, and payment systems;
7. produce traceable records for metering, energy accounting, wheeling, reconciliation, and audit; and
8. maintain cybersecurity, privacy, resilience, safety, and accountability across the full service lifecycle.

The resulting gap is a **digital coordination, interoperability, assurance, and operating-model problem**. Unless addressed, decentralised assets may remain under-observed or independently managed, emerging market processes may remain fragmented or labour-intensive, and opportunities to use distributed flexibility for consumer, network, and system benefits may be difficult to realise safely and at scale.

---

## 3. Verified sector context

### 3.1 Demand is growing

EPRA reported that electricity demand increased by 8.25% in July–December 2025 compared with the corresponding period in the previous financial year. National peak demand reached **2,439.06 MW on 3 December 2025**, up from 2,288.38 MW in the comparable 2024 period.

This does not by itself prove a generation shortage. It does demonstrate that system planning, network capacity, operational visibility, and demand management must accommodate a growing and changing load profile.

### 3.2 Regional electricity trade is material and increasing

EPRA reported electricity imports of **939.23 GWh** during July–December 2025, compared with 751.95 GWh in the corresponding prior period. The same report noted regional wheeling and electricity exchange activity.

Imports should not be characterised as inherently unreliable or undesirable without supporting evidence. Regional trade can strengthen adequacy, lower costs, and improve system flexibility. It also increases the importance of accurate scheduling, energy accounting, metering, congestion management, and settlement.

### 3.3 Network expansion and reinforcement remain necessary

KETRACO's Transmission Master Plan 2025–2044 identifies continued demand growth, renewable-energy integration, regional interconnection, reliability, system-strengthening, and network expansion as major planning requirements. Physical grid investment remains essential.

A digital platform cannot replace transmission lines, substations, distribution reinforcement, protection systems, reactive-power equipment, or maintenance. Its potential role is complementary: improved visibility, coordination, forecasting, flexibility management, and information exchange may help operators use available infrastructure more effectively and identify where physical investment is still required.

### 3.4 System losses remain above the regulatory allowance

EPRA reported total energy losses of **22.07%** during July–December 2025, compared with an allowed threshold of 16.50% for the 2025/26 financial year.

These losses include both technical and non-technical causes. A distributed-energy coordination platform cannot independently solve all loss drivers. It may contribute through better metering visibility, anomaly detection, reconciliation, local optimisation, and data quality, but loss reduction also depends on network upgrades, commercial controls, meter management, enforcement, and operating discipline.

### 3.5 Electric-mobility electricity use is growing from a small base

EPRA reported that electricity consumption in the electric-mobility category increased from 1.81 GWh to **4.57 GWh** in July–December 2025, a 152.49% increase over the corresponding prior period.

The absolute energy volume remains small relative to total national demand, but the growth rate and the concentration of charging at depots, hubs, and high-power sites create a credible planning need. Unmanaged charging can contribute to local peak demand where many chargers are connected behind constrained transformers or feeders. The actual risk must be evaluated site by site through load-flow studies, connection assessments, diversity assumptions, charging profiles, and network measurements.

### 3.6 Kenya has introduced regulated net metering

The Energy (Net-Metering) Regulations, 2024 set the following installed-capacity limits:

- up to 4 kW for a domestic consumer on single-phase supply;
- up to 10 kW for a domestic consumer on three-phase supply; and
- up to 1 MW for a commercial or industrial consumer, also subject to the applicable maximum-demand limitation.

The regulations require smart bi-directional metering, technical approval, compliant interconnection, and measures preventing unsafe back-feed into a de-energised line. Exported energy is credited under the applicable billing arrangement; unused credits are forfeited at the end of the licensee's financial year.

Net metering is not equivalent to unrestricted peer-to-peer trading, participation in an ancillary-services market, or permission for a third party to dispatch a consumer's asset. Those functions require separate legal, contractual, technical, and regulatory authority.

### 3.7 Electricity-market and open-access reform creates new coordination requirements

The Energy (Electricity Market, Bulk Supply and Open Access) Regulations, 2026 provide for:

- wholesale and retail electricity-market segments;
- bilateral, spot, and forward contractual arrangements;
- market-participant registration and operational procedures;
- system-operator coordination;
- network access applications and technical assessments;
- wheeling agreements and regulatory approval;
- energy accounting, imbalance treatment, losses, and network charges;
- compliance with the Grid Code; and
- congestion management and curtailment by the system operator.

Open access is therefore a controlled operational and commercial process, not merely a software billing function. Any NEOS capability must support—rather than bypass—the statutory responsibilities, approvals, and decision rights established by law.

---

## 4. Core problem dimensions

### 4.1 Fragmented asset visibility

Distributed solar, batteries, mini-grids, controllable loads, and charging infrastructure are owned and operated by many independent parties using heterogeneous equipment and vendor platforms. Without common onboarding, identity, telemetry, time-synchronisation, and data-quality standards, authorised operators may lack a consistent view of what assets exist, where they are connected, what they can do, and whether they are available.

**Validation required:** national inventory, device compatibility survey, telemetry availability assessment, smart-meter coverage, asset ownership and consent mapping, and data-quality baseline.

### 4.2 Limited interoperability across devices and institutions

Participating assets may use different protocols, data models, firmware, interfaces, control semantics, and security arrangements. Utilities, regulators, aggregators, payment providers, and asset owners may also operate separate systems with different identifiers and records.

This creates a risk of bespoke integrations, inconsistent data interpretation, vendor lock-in, duplicated records, and difficult reconciliation.

**Validation required:** interface inventory, protocol and device matrix, enterprise-integration assessment, common information model evaluation, and master-data governance design.

### 4.3 Separation between local control and central coordination

Fast site-level functions must remain local where communications latency or failure would make central dependence unsafe. National or portfolio-level coordination requires a slower supervisory layer that respects local protection, owner preferences, network constraints, and authorised operator instructions.

The sector therefore needs an explicit control hierarchy, fail-safe behaviour, command-authority model, acknowledgement process, and override rules. A central platform must not directly replace certified protection systems or assume unlimited control of connected assets.

**Validation required:** control-loop classification, latency budget, fail-safe analysis, protection coordination, communications-failure scenarios, and operator-authority mapping.

### 4.4 Emerging market, wheeling, and settlement complexity

Open access and new market structures require coordinated handling of participant registration, contracts, metering points, nominations or schedules, network capacity, energy accounting, losses, imbalances, charges, invoices, disputes, and audit evidence.

The 2026 regulations assign key responsibilities to the system operator, network service providers, licensees, eligible consumers, and EPRA. NEOS must not duplicate or contradict those responsibilities. Its role, if approved, would be to provide interoperable technical services and trusted data flows within the authorised market architecture.

**Validation required:** market-process mapping, regulatory interpretation, metering and settlement architecture, data-authority matrix, tariff-interface requirements, and legal admissibility of digital records.

### 4.5 Distribution-level flexibility is not automatically available

Installed solar, storage, EV batteries, and flexible loads cannot be assumed to be available to the grid. Availability depends on asset capability, state of charge, primary customer needs, warranties, connection agreements, owner consent, aggregator contracts, network conditions, communications, and approved operating rules.

A virtual power plant is therefore a controlled portfolio with measured and contracted availability—not the sum of all installed distributed capacity.

**Validation required:** flexibility-resource assessment, contractual availability model, baseline methodology, dispatch-performance tests, and network hosting-capacity studies.

### 4.6 Cybersecurity, privacy, and critical-infrastructure assurance

Connecting field devices to central systems expands the attack surface. Risks include unauthorised commands, compromised gateways, stolen credentials, manipulated telemetry, software-supply-chain vulnerabilities, insecure remote updates, denial of service, privacy breaches, and unsafe interactions with operational technology.

National use requires security architecture, certificate and key management, secure development, device certification, monitoring, incident response, segmentation, audit, recovery, and independent assurance. Encryption alone is insufficient.

**Validation required:** threat model, criticality classification, privacy impact assessment, security control baseline, software-assurance process, incident-response model, and penetration and resilience testing.

### 4.7 Institutional mandate and operating ownership are unresolved

A platform of this nature crosses policy, regulation, system operation, network operation, market operation, commercial settlement, cybersecurity, data protection, consumer protection, and asset ownership. Technical deployment without clear authority would create operational and legal risk.

The project must determine which existing institution—or formally established arrangement—owns, operates, regulates, funds, audits, and is liable for each service. The creation of a new agency must not be assumed before legal, institutional, fiscal, and policy approval.

**Validation required:** institutional-options analysis, statutory mandate review, RACI matrix, liability model, funding model, and stakeholder approval.

### 4.8 Benefits and economics are not yet proven

Potential benefits include improved visibility, demand response, charging coordination, renewable integration, operational support, settlement efficiency, loss detection, and deferred network investment. These benefits are plausible but are not automatic.

They depend on the value of flexibility at specific network locations and times, participant behaviour, implementation cost, avoided-cost methodology, market rules, baseline accuracy, communications, asset performance, and operator adoption.

**Validation required:** baseline study, cost-benefit analysis, counterfactual definition, avoided-cost methodology, pilot measurement plan, and benefits-realisation framework.

---

## 5. Root causes

The principal root causes to be tested are:

1. **Rapid sector change:** regulation, distributed generation, regional trade, digital metering, and e-mobility are changing faster than common operating and data arrangements are being standardised.
2. **Heterogeneous technology:** devices and institutional systems were procured for local objectives and do not necessarily share common interfaces or control semantics.
3. **Incomplete data governance:** asset, meter, customer, network, contract, and settlement data may have different owners, identifiers, quality controls, and access rules.
4. **Legacy integration constraints:** existing SCADA, billing, metering, outage, network-planning, and regulatory systems may not expose consistent real-time or transactional interfaces.
5. **Unresolved operating authority:** distributed assets cross boundaries between private ownership, local optimisation, distribution operation, system operation, regulation, and market participation.
6. **Limited standard certification:** there is no project-approved national conformance regime for NEOS-compatible gateways, software, device drivers, security, telemetry, and control behaviour.
7. **Uneven communications and field capability:** telecommunications quality, site engineering, maintenance capacity, and cybersecurity maturity vary across locations.
8. **Unproven commercial mechanisms:** the value, tariffs, compensation, liabilities, and settlement rules for distributed flexibility require legal and economic definition.

These causes are programme hypotheses and must be confirmed through structured discovery rather than treated as established facts in every institution or region.

---

## 6. Affected stakeholders

The coordination gap may affect:

- **System and network operators**, which require reliable data, predictable behaviour, and clear control authority;
- **EPRA and policy institutions**, which require auditable compliance, market information, consumer safeguards, and evidence for regulatory decisions;
- **Generators, retailers, and eligible consumers**, which require clear access, metering, contracting, scheduling, and settlement processes;
- **Commercial and industrial asset owners**, which require protection of their primary operations, transparent participation terms, and measurable returns;
- **Aggregators and technology providers**, which require standard interfaces, certification requirements, and non-discriminatory access rules;
- **EV charging and fleet operators**, which require network-aware charging arrangements and reliable service;
- **Households and small prosumers**, which require simple onboarding, accurate billing, privacy, safety, fair compensation, and accessible dispute resolution;
- **Mini-grid and off-grid operators**, which require local autonomy and carefully governed interaction with wider systems where interconnection exists;
- **Cybersecurity and data-protection authorities**, which require enforceable controls over critical systems and personal data; and
- **Financiers and development partners**, which require measurable outcomes, credible costs, safeguards, and accountable implementation.

---

## 7. Consequences if the problem remains unresolved

If coordination capabilities do not mature alongside sector reform and distributed-resource growth, Kenya may experience:

- slow, inconsistent, or costly integration of distributed assets;
- limited operational visibility of participating resources;
- underuse of technically available flexibility;
- increased integration and reconciliation effort across institutions;
- settlement disputes caused by inconsistent identifiers, timestamps, meter data, or contractual records;
- difficulty managing concentrated charging or generation on constrained feeders;
- avoidable renewable-energy curtailment in specific locations or periods;
- continued dependence on manual or fragmented market processes;
- greater cybersecurity exposure from unmanaged third-party connections;
- vendor lock-in and duplicated proprietary platforms;
- reduced confidence among participants, operators, regulators, and financiers; and
- delayed realisation of consumer, reliability, access, and decarbonisation benefits.

These are credible risks, not guaranteed outcomes. The original claims that the electricity market will “collapse,” that a utility “death spiral” is inevitable, or that low-income consumers will necessarily be stranded are speculative and are not retained as factual conclusions.

---

## 8. Problem boundaries

NEOS can potentially address digital coordination and information-flow gaps. It cannot, by itself, solve:

- insufficient generation adequacy;
- transmission or distribution capacity shortages;
- poor equipment condition or inadequate maintenance;
- all technical and non-technical losses;
- electricity affordability or tariff design;
- fuel-price or foreign-exchange exposure;
- weak enforcement of licences and contracts;
- lack of certified meters, protection equipment, or field engineering;
- unreliable telecommunications in every location;
- electricity-access financing and physical last-mile connections;
- participant unwillingness to make assets available; or
- institutional conflicts that have not been resolved through law and governance.

The programme must be designed as one component of wider grid, market, utility, access, and institutional reform.

---

## 9. Evidence gaps requiring baseline studies

Before approving solution scope or quantified benefits, the programme should establish:

| Evidence area | Required baseline |
|---|---|
| **DER inventory** | Number, type, rating, location, connection voltage, ownership, controllability, and communications capability of relevant assets |
| **Network constraints** | Feeder and substation hosting capacity, congestion, voltage excursions, outages, losses, and planned reinforcement |
| **Metering readiness** | Smart-meter population, accuracy classes, communications, interval data, time synchronisation, and data-access rights |
| **System interfaces** | Existing SCADA/EMS/DMS, metering, billing, outage, market, regulatory, payment, and data-platform capabilities |
| **Flexibility potential** | Technically available and contractually available MW/MWh by location, time, duration, and service type |
| **EV charging** | Charger count, rating, location, duty cycle, depot concentration, load profile, and planned expansion |
| **Market operations** | Current and target processes for registration, contracting, scheduling, wheeling, energy accounting, settlement, and dispute resolution |
| **Cybersecurity maturity** | Field-device security, identity, remote access, patching, monitoring, incident response, recovery, and third-party risks |
| **Telecommunications** | Coverage, latency, availability, bandwidth, cost, and outage behaviour across candidate sites |
| **Economics** | Implementation and operating costs, avoided costs, participant incentives, tariff implications, and distributional impacts |
| **Institutional capacity** | Mandates, staffing, skills, operating procedures, procurement capacity, and long-term funding |

---

## 10. Initial programme need

The immediate need is not national-scale deployment. It is a controlled definition and validation programme that can:

1. establish authoritative baselines;
2. map legal and institutional decision rights;
3. define priority use cases and measurable value;
4. specify functional, performance, security, safety, and interoperability requirements;
5. assess existing systems before proposing replacements or extensions;
6. develop a reference architecture and certification approach;
7. implement limited pilots at representative sites;
8. independently test technical, operational, regulatory, cybersecurity, and economic feasibility; and
9. use evidence-based decision gates for further investment and scale-up.

---

## 11. Problem-resolution success measures

The programme should define baselines and targets for at least:

- percentage of participating assets with verified identity and complete registry records;
- telemetry completeness, validity, timeliness, and clock accuracy;
- number and capacity of assets proven interoperable through certification;
- local-control continuity during central communications failure;
- command success, acknowledgement, and safe-rejection rates;
- dispatchable flexibility demonstrated by location, duration, and response time;
- reduction in manual processing time for approved market or settlement processes;
- reconciliation accuracy and dispute rate;
- availability and recovery performance of platform services;
- cybersecurity detection, containment, patching, and recovery metrics;
- quantified network, consumer, utility, and market benefits against approved counterfactuals; and
- participant satisfaction, complaints, opt-out, and compensation performance.

National claims should not be made from pilot results without a documented scaling methodology.

---

## 12. Truthfulness and feasibility assessment of the superseded source

| Original claim | Assessment | Corrected position |
|---|---|---|
| The 2026 regulations ended Kenya Power's bulk-supply monopoly | **Overstated** | The regulations establish market and open-access arrangements with licensed participants, technical assessments, contracts, network charges, system-operator coordination, and EPRA approval. Existing utility roles remain material. |
| IPPs and C&I prosumers can freely generate, stream, and sell power directly through existing networks | **Misleading** | Participation depends on participant status, licences, eligible-consumer rules, connection and network capacity, approved agreements, Grid Code compliance, charges, and system-operation requirements. |
| The grid cannot route multi-directional electron flows without an EOS | **Technically inaccurate wording** | Electrical power flows according to network physics. Digital systems can improve measurement, forecasting, coordination, control, constraint management, and accounting; they do not independently “route electrons.” |
| Decentralised generation is already causing severe national grid instability | **Not established by the cited source** | Distributed generation can create local voltage, protection, reverse-flow, and congestion issues under certain conditions. The location, severity, and causality require network studies and operational data. |
| No major state plant has been commissioned because of a structural freeze | **Unsupported and removed** | Generation adequacy and commissioning history require a separate evidence-based planning assessment. |
| Kenya relies on erratic imports and costly thermal peakers | **Loaded and partially unsupported** | Regional imports are significant and increasing, but their reliability and economic effect must be assessed from contracts, prices, availability, and system studies. |
| C&I sites produce exactly 300.5 MW of variable captive solar | **Unsupported and removed** | A national and site-level DER inventory is required before quoting aggregate capacity. Named companies must not be assigned capacities without verified source data. |
| Lack of OpenEMS causes voltage drops, outages, and grid rejection | **False causality** | Voltage and reliability events have multiple electrical and operational causes. OpenEMS is a possible technology foundation, not a proven missing cause of outages. |
| Net-metering meters are static or “dumb” | **Incorrect** | The 2024 regulations require smart, bi-directional meters with two-way communication and time-of-use capability. |
| Net-metering credits expire at the end of each calendar year | **Incorrect detail** | Unused credits are forfeited at the end of the licensee's financial year. |
| Private solar and batteries are massive reserves available to a VPP | **Unproven** | Installed capacity is not equivalent to controllable or contractually available flexibility. Capability, consent, state of charge, warranties, network limits, and regulation determine availability. |
| Electricity tariffs of KSh 18–28/kWh are causing industrial grid defection | **Unsupported generalisation** | Effective tariffs vary by customer class, consumption, time, taxes, levies, fuel, foreign exchange, and tariff period. Customer-sited generation decisions have multiple drivers. |
| Wheeling administration is currently an EPRA bottleneck | **Unverified** | The 2026 framework creates complex technical and commercial processes. Current process performance must be measured before claiming a bottleneck. |
| The liberalised market will collapse and create an inevitable utility death spiral | **Speculative and removed** | Reform introduces opportunities and risks. Financial consequences depend on tariffs, costs, network revenues, customer behaviour, regulation, and utility strategy. |
| NEOS will enable 100% clean, reliable, affordable electricity | **Not a defensible project guarantee** | NEOS may contribute to renewable integration, flexibility, efficiency, and better coordination, but national affordability, reliability, access, and generation mix depend on many programmes and policies. |

No deliberate falsehood can be established from the text alone. The principal defects were unsupported precision, exaggerated causality, solution bias, incorrect interpretation of net-metering requirements, and speculative consequences presented as certain outcomes.

---

## 13. Authoritative problem statement

> Kenya's electricity sector is becoming more decentralised, data-intensive, and operationally complex as demand grows and regulated pathways emerge for net metering, open access, market participation, regional trade, distributed generation, storage, and electric mobility. The sector does not yet have a programme-validated, nationally governed capability that consistently connects asset identity, telemetry, local controls, network constraints, participant rights, system-operator instructions, market processes, metering, energy accounting, settlement, cybersecurity, privacy, and audit. This coordination gap may limit the safe and economic use of distributed flexibility and increase integration, operational, and reconciliation burdens. The immediate requirement is to validate the gap, define authority and standards, establish baselines, and prove priority use cases through controlled pilots before any national-scale implementation.

---

## 14. Source and verification references

1. **Original project source:** `problem-statement.txt`.
2. **Energy and Petroleum Regulatory Authority:** *Biannual Energy & Petroleum Statistics Report, Financial Year 2025/2026* (reporting July–December 2025), published March 2026.  
   <https://www.epra.go.ke/biannual-statistics-report-2025-2026>
3. **Kenya Law:** *The Energy (Electricity Market, Bulk Supply and Open Access) Regulations, 2026*, Legal Notice No. 79 of 2026, dated 8 May 2026.  
   <https://new.kenyalaw.org/akn/ke/act/ln/2026/79/>
4. **Kenya Law:** *The Energy (Net-Metering) Regulations, 2024*, Legal Notice No. 104 of 2024, commenced 18 July 2024.  
   <https://new.kenyalaw.org/akn/ke/act/ln/2024/104/>
5. **Kenya Electricity Transmission Company:** *Transmission Master Plan 2025–2044, Volume I*.  
   <https://www.ketraco.co.ke/sites/default/files/downloads/KETRACO%20TMP%202025-2044_Vol%201_.pdf>
6. **Kenya Power:** *Audited Financial Results for the Year Ended 30 June 2025*.  
   <https://kplc.co.ke/annual-reports>
7. **Ministry of Energy and Petroleum:** *Kenya National Energy Compact 2025*.  
   <https://www.energy.go.ke/sites/default/files/Kenya%20National%20Energy%20Compact%2022AUG2025%20%281%29.pdf>

Official legal texts, regulator publications, and current approved policies take precedence over this working document where any inconsistency arises.

---

## 15. Version history

| Version | Date | Author/owner | Change description |
|---|---|---|---|
| 0.1 | 23 July 2026 | National Energy Operating System Programme | Replaced the initial problem statement; corrected regulatory interpretation, removed unsupported capacity and causality claims, established an evidence-backed sector context, defined the coordination gap, added boundaries, baseline requirements, success measures, and claim-by-claim truthfulness assessment. |
