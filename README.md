# National Energy Operating System (NatEnerOS)

> A national digital infrastructure package for coordinating Distributed Energy Resources (DERs), improving last-mile grid visibility, and enabling renewable-energy integration at scale.

## Project Status

| Field | Value |
|---|---|
| Current version | `0.1.0` |
| Release stage | Concept / Foundation |
| Versioning standard | Semantic Versioning 2.0.0 |
| Last updated | 2026-07-22 |
| License | To be defined |

## Overview

The **National Energy Operating System (NatEnerOS)** is a national-level platform for managing and coordinating Distributed Energy Resources such as:

- Solar photovoltaic systems
- Battery energy storage systems
- Backup generators
- Smart meters
- Electric-vehicle charging infrastructure
- Controllable electrical loads
- Facility and community microgrids

NatEnerOS uses **OpenEMS** as a facility-level, behind-the-meter micro-DERMS. Each connected facility can monitor and control its local energy resources while exchanging operational data and flexibility signals with the wider national platform.

The result is a digital operating layer connecting individual energy assets, aggregators, utilities, investors, regulators, and government energy institutions.

## Objectives

NatEnerOS is designed to:

1. Aggregate geographically distributed energy resources into coordinated portfolios.
2. Improve visibility beyond utility meters and into the last mile of the grid.
3. Support higher penetration of variable renewable-energy sources.
4. Improve grid planning, reliability, resilience, and modernization.
5. Coordinate energy production, storage, consumption, and demand flexibility.
6. Enable data-driven policy, investment, and infrastructure decisions.
7. Create a foundation for energy SaaS, DER aggregation, and flexibility markets.

## System Architecture

```text
+---------------------------------------------------------------+
|             National Energy Operating System                  |
|                                                               |
|  National monitoring | Aggregation | Analytics | Markets      |
|  Planning | Policy | Investment | Utility integration         |
+-------------------------------+-------------------------------+
                                |
                  Secure APIs and data exchange
                                |
+-------------------------------+-------------------------------+
|               Regional / Utility Coordination                 |
|                                                               |
|  Grid operations | Forecasting | Dispatch | Asset portfolios  |
+-------------------------------+-------------------------------+
                                |
                     Aggregated DER control
                                |
+-------------------------------+-------------------------------+
|          Facility-Level OpenEMS Micro-DERMS Instances         |
|                                                               |
|  Solar | Batteries | Meters | EV charging | Loads | Generators|
+---------------------------------------------------------------+
```

## Core Capabilities

### DER Registration and Inventory

- Register facilities and individual energy assets.
- Maintain national and regional DER inventories.
- Track asset ownership, location, capacity, status, and connectivity.

### Monitoring and Telemetry

- Collect near-real-time operating data from facility-level systems.
- Monitor generation, storage, consumption, import, and export.
- Provide last-mile visibility for utilities and authorized institutions.

### Aggregation and Coordination

- Group DERs by geography, utility territory, technology, or ownership.
- Coordinate portfolios as virtual power plants or flexibility resources.
- Dispatch eligible assets while respecting local operating constraints.

### Forecasting and Analytics

- Forecast renewable generation and electricity demand.
- Analyze grid constraints, asset availability, and flexibility potential.
- Support infrastructure planning and renewable-energy policy.

### Grid and Market Integration

- Exchange data with utility operational and planning systems.
- Support demand response, ancillary services, and future flexibility markets.
- Provide auditable measurement and verification for delivered services.

### Commercial Services

- Software-as-a-Service subscriptions
- DER aggregation services
- Energy-management services
- Infrastructure and project investment
- Data and analytics services
- Operations and maintenance support
- Grid modernization programs

## Stakeholders

NatEnerOS can serve:

- National and local governments
- Energy regulators
- Transmission and distribution utilities
- Independent power producers
- Solar and storage developers
- Commercial and industrial facilities
- Mini-grid and microgrid operators
- Financial institutions and infrastructure investors
- Energy service companies and aggregators
- Research and standards organizations

## Proposed Package Structure

```text
national-energy-operating-system/
├── README.md
├── VERSION
├── CHANGELOG.md
├── LICENSE
├── docs/
│   ├── architecture/
│   ├── deployment/
│   ├── governance/
│   ├── security/
│   └── standards/
├── packages/
│   ├── facility-edge/
│   ├── der-registry/
│   ├── aggregation-service/
│   ├── telemetry-service/
│   ├── forecasting-service/
│   ├── grid-integration/
│   ├── market-services/
│   └── operator-portal/
├── infrastructure/
│   ├── containers/
│   ├── kubernetes/
│   └── terraform/
├── integrations/
│   ├── openems/
│   ├── utility-systems/
│   └── metering-platforms/
├── schemas/
├── tests/
└── examples/
```

## Versioning Policy

NatEnerOS follows **Semantic Versioning** using the format:

```text
MAJOR.MINOR.PATCH
```

- **MAJOR**: Incompatible architecture, API, schema, or deployment changes.
- **MINOR**: Backward-compatible features and capability additions.
- **PATCH**: Backward-compatible fixes, documentation updates, and security patches.

Pre-release versions may use suffixes such as:

```text
0.2.0-alpha.1
0.2.0-beta.1
1.0.0-rc.1
```

### Version Sources

The authoritative version should be maintained in:

1. The repository root `VERSION` file.
2. This README project-status table.
3. Release tags using the format `vMAJOR.MINOR.PATCH`.
4. `CHANGELOG.md` for release details.
5. Package manifests and container image tags.

### Compatibility Rule

All independently deployable NatEnerOS packages should declare:

- Package version
- Supported platform version
- API version
- Data-schema version
- Minimum compatible OpenEMS integration version

Example:

```yaml
package: der-registry
version: 0.1.0
platformVersion: ">=0.1.0 <0.2.0"
apiVersion: v1alpha1
schemaVersion: 1
openemsCompatibility: "to-be-defined"
```

## Release Process

1. Define the release scope and target version.
2. Update package manifests and the root `VERSION` file.
3. Update the version table in this README.
4. Add release notes to `CHANGELOG.md`.
5. Run automated tests, security checks, and compatibility validation.
6. Create a signed Git tag such as `v0.2.0`.
7. Build and publish versioned packages and container images.
8. Publish deployment and rollback instructions.

## Version History

| Version | Date | Stage | Summary |
|---|---|---|---|
| `0.1.0` | 2026-07-22 | Foundation | Initial project definition, objectives, architecture, package model, and versioning policy. |

## Roadmap

### `0.1.x` — Foundation

- Define the national operating model.
- Establish architecture, governance, and security requirements.
- Define DER, facility, telemetry, and control schemas.
- Document the OpenEMS integration pattern.

### `0.2.x` — Pilot Platform

- Implement the DER registry and facility onboarding workflow.
- Connect initial OpenEMS facilities.
- Deploy telemetry ingestion and operator dashboards.
- Validate access control and data-quality processes.

### `0.3.x` — Aggregation

- Introduce portfolio aggregation and forecasting.
- Implement flexibility estimation and dispatch workflows.
- Add utility-system integration interfaces.

### `0.4.x` — Commercial Services

- Add tenant management and SaaS billing foundations.
- Support investment and asset-performance reporting.
- Introduce measurement and verification services.

### `1.0.0` — Production Release

- Stable national platform APIs and schemas.
- Production security, resilience, and disaster recovery.
- Audited governance and operational procedures.
- Supported upgrade and rollback paths.

## Security and Governance

Because NatEnerOS coordinates critical energy infrastructure, implementations should include:

- Zero-trust access controls
- Strong device and service identity
- Encryption in transit and at rest
- Role-based and attribute-based authorization
- Complete audit logs
- Data residency and retention policies
- Secure remote update mechanisms
- Incident response and disaster recovery
- Separation of monitoring, advisory, and control privileges
- Human authorization for high-impact control actions

## Deployment Principles

- **Federated:** Facility systems continue operating safely during central outages.
- **Interoperable:** Use open interfaces and documented schemas.
- **Modular:** Services can be deployed and upgraded independently.
- **Secure by default:** Access is denied unless explicitly authorized.
- **Observable:** Every critical component exposes health, logs, metrics, and traces.
- **Versioned:** APIs, schemas, packages, deployments, and integrations are traceable.
- **Vendor-neutral:** National capabilities should not depend on a single hardware vendor.

## Getting Started

The project is currently at the foundation stage. Initial implementation work should begin with:

1. Selecting pilot facilities and utility partners.
2. Defining the national DER data model.
3. Establishing OpenEMS facility integration requirements.
4. Creating the DER registry and secure identity services.
5. Building telemetry ingestion and operational dashboards.
6. Defining governance, cybersecurity, and data-sharing policies.

## Contributing

Contributions should be proposed through version-controlled changes and reviewed for:

- Architectural compatibility
- Cybersecurity impact
- Grid-operational safety
- Data governance
- API and schema compatibility
- Test coverage
- Deployment and rollback requirements

Changes affecting public APIs or shared schemas must include migration guidance and an appropriate semantic-version increment.

## Changelog

Release details are maintained in [`CHANGELOG.md`](CHANGELOG.md).

## License

The project license and ownership framework are **to be defined**. National deployments should establish clear rules for source-code ownership, operator access, data rights, commercial participation, and public-interest obligations.
