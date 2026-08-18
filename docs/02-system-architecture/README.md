# System Architecture

This section explains the technical system being proposed.

## System Definition

The system is an open, interoperable energy coordination architecture that scales through abstraction:

```text
Physical DER Assets
  ↓
Facility EMS / Edge
  ↓
Regional DERMS
  ↓
National DERMS
  ↓
National Energy Operating System
```

Each layer has a different responsibility. Lower layers remain closer to physical control and safety. Higher layers coordinate, aggregate, forecast, verify, and govern broader energy-system objectives.

## Architecture Principles

- Coordinate globally; control locally.
- Preserve local autonomy and physical safety.
- Use open, documented, stable interfaces where practical.
- Normalize vendor-specific data into common energy-resource semantics.
- Treat identity, authorization, audit, and cybersecurity as core infrastructure.
- Scale through federation and aggregation, not direct national micromanagement of every device.

## Source Documents

- [Technology & Digital Infrastructure](../../organization-docs/11-technology-and-digital-infrastructure/)
- [Product Portfolio](../../organization-docs/04-product-portfolio/product-portfolio.md)
- [Product Roadmap](../../organization-docs/05-product-roadmap/product-roadmap.md)

## System Layers

| Layer | Primary Role |
|---|---|
| Facility EMS | Coordinate a complete facility energy system locally. |
| Regional DERMS | Aggregate and coordinate multiple facilities or distributed resources in a bounded region or network domain. |
| National DERMS | Federate regional capabilities for national visibility, forecasting, coordination, and verification. |
| National Energy Operating System | The broader operating environment connecting technical coordination, governance, market processes, evidence, assurance, and learning. |

