# Legal Entity, Ownership, IP & Open Source

## Purpose

This document establishes the legal and ownership architecture required to convert a founder-led technical project into a durable institution while preserving an open-source ecosystem.

> **Master Legal Architecture Law:** The institution must clearly separate ownership of the company, ownership and licensing of software, ownership of customer and operational data, rights in third-party components, and authority over physical energy assets so that collaboration can expand without creating ambiguity over control.

## Legal Entity

The operating organization should ultimately exist as an identifiable legal entity capable of entering contracts, employing people, receiving investment, holding assets, protecting intellectual property, maintaining accounts, carrying liabilities, and continuing independently of its founder.

The exact legal structure should be selected with qualified Kenyan legal and tax advice when incorporation and financing requirements are finalized.

## Ownership Layers

Ownership is not one concept. Distinguish at least:

```text
Corporate Equity
Software Copyright
Trademarks / Brand
Patents or Inventions
Operational Data
Customer Data
Physical Energy Assets
Infrastructure Credentials
Third-party Components
```

Owning one does not automatically confer rights over the others.

## Founder Contributions

Founder-created intellectual property intended for the organization should be documented and, where appropriate, formally assigned or licensed to the legal entity.

Relevant material may include:

- Source code
- Architecture
- Documentation
- Designs
- Data models
- Trademarks and brand assets
- Research
- Domain names
- Inventions

This avoids future uncertainty over whether important assets belong personally to the founder or institutionally to the company.

## Employee and Contractor IP

Employment and contractor arrangements should clearly address ownership and licensing of work created for the organization.

Contracts should cover, as appropriate:

- Confidentiality
- IP assignment
- Open-source obligations
- Security responsibilities
- Data handling
- Pre-existing intellectual property
- Termination and handover

## Open Source Is a Licensing Model

Publishing source code does not mean abandoning ownership.

```text
Copyright Owner
      ↓
Open-source License
      ↓
Permission to Use / Modify / Distribute
```

The organization may retain copyright while granting broad rights under an open-source license.

## License Governance

Before public release, each repository should have a deliberate license decision.

Considerations include:

- Permissive versus copyleft strategy
- Compatibility with upstream projects
- Commercial adoption
- Contributor expectations
- Patent provisions
- Distribution obligations
- Notice requirements

Do not copy code merely because it is publicly visible. License terms remain binding.

## Third-Party Dependencies

Maintain an inventory of material dependencies and their licenses.

Track:

- Package/component
- Version
- Source
- License
- Modification status
- Distribution obligations
- Security status

A software bill of materials can progressively support this function.

## Contributions

External contribution governance should establish how rights are granted to the project. Depending on project structure, this may rely on the repository license, Developer Certificate of Origin, Contributor License Agreement, or another documented contribution mechanism.

The chosen mechanism should preserve contributor rights while ensuring the project can legally maintain and distribute accepted contributions.

## Brand and Trademark

Open-source code rights and brand rights are separate.

The organization may permit broad use of software while protecting names, logos, certification marks, or claims of official affiliation from misleading use.

## Data Ownership and Rights

Operational data governance should distinguish:

- Raw device data
- Customer account data
- Derived analytics
- Aggregated statistics
- System metadata
- Audit records

Contracts and policies should define who owns or controls each class, what processing rights the platform receives, permitted purposes, retention, access, portability, deletion, and regulatory obligations.

## Physical Assets

Software integration does not create ownership of the physical energy resource.

```text
Facility / Asset Owner
        ↓ owns asset
National DERMS
        ↓ receives authorized digital access
Monitoring / Coordination / Control
```

Control authority must come from explicit legal, contractual, or regulatory authorization.

## Credentials and Digital Authority

Credentials, keys, certificates, and control permissions represent institutional authority and must be treated as controlled assets.

They require:

- Ownership records
- Access restrictions
- Rotation
- Revocation
- Auditability
- Handover procedures

## Commercial and Open Components

An open-source strategy can coexist with commercial services.

Potential commercial value may arise from:

- Deployment
- Integration
- Managed operations
- Hosting
- Support
- Enterprise controls
- Assurance
- Training
- Data services
- Infrastructure coordination

The business should not depend on artificial lock-in if the strategic mission requires interoperability.

## Confidential Information

Not all organizational information belongs in public repositories. Protect legitimate:

- Credentials
- Vulnerability details
- Customer information
- Sensitive infrastructure configurations
- Commercial contracts
- Personal data
- Security architecture where disclosure materially increases risk

## Legal Registers

As the organization matures, maintain registers for:

- Corporate ownership
- Directors/officers
- Material contracts
- Intellectual property
- Open-source dependencies
- Data processing relationships
- Licenses and permits
- Insurance
- Material legal obligations

## Legal Architecture Laws

1. Corporate ownership, software ownership, data rights, physical asset ownership, and operational authority are separate concepts.
2. Founder-created institutional IP should be explicitly documented and transferred or licensed appropriately.
3. Open source grants rights through licenses; it does not erase copyright ownership.
4. Third-party software is used only under compatible license terms.
5. Accepted external contributions require a clear rights framework.
6. Brand rights remain separable from source-code rights.
7. Device integration does not confer ownership or unrestricted control over physical assets.
8. Data rights and processing rights are explicitly defined rather than assumed.
9. Credentials and digital permissions are controlled institutional assets.
10. Commercial services may coexist with an open-source core without relying on proprietary lock-in.

## Definition of Done

This architecture is complete when the institution can identify:

1. The legal entity that contracts and carries liability.
2. Corporate ownership and governance rights.
3. Ownership of core software and documentation.
4. Rights in founder-created IP.
5. Rights in employee and contractor work.
6. Licenses governing every public repository.
7. Obligations created by material third-party dependencies.
8. The contribution-rights mechanism.
9. Brand and trademark ownership.
10. Data ownership and processing rights.
11. Physical asset ownership and control authorization.
12. Ownership and governance of credentials and certificates.
13. Which information is public versus confidential.
14. Which legal registers must be maintained.
