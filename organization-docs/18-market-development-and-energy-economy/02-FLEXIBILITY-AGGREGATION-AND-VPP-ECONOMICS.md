# Flexibility, Aggregation & VPP Economics

## Purpose

Define how physical DER capability becomes qualified flexibility, how resources may be aggregated, and how portfolio economics are evaluated without compromising facility constraints or asset-owner authority.

## Flexibility

Flexibility is the ability of a resource or portfolio to change its expected power or energy trajectory within defined constraints, response times and durations.

```text
RESOURCE CAPABILITY
- BASELINE
- ASSET LIMITS
- CUSTOMER LIMITS
- GRID LIMITS
- RESERVES
= QUALIFIED FLEXIBILITY
```

Nameplate capacity is not flexibility.

## Flexibility Attributes

Each flexibility capability should describe direction, power, energy, start time, duration, response time, ramp rate, confidence, recovery requirements, availability window and constraints.

## Aggregation Hierarchy

```text
DER
 ↓
Facility
 ↓
Portfolio
 ↓
Aggregator / VPP
 ↓
Market / Utility Service
```

Aggregation must preserve resource provenance and local constraints.

## Technical vs Commercial Aggregation

Technical aggregation combines resources for monitoring, forecasting, optimization or control. Commercial aggregation combines resources under contractual and market obligations. A technically aggregated portfolio does not automatically possess authority to transact.

## Portfolio Optimization

Portfolio optimization may consider energy cost, availability, forecast uncertainty, degradation, customer constraints, grid constraints, market value, penalties and reserves.

```text
NET PORTFOLIO VALUE
=
MARKET / OPERATIONAL VALUE
- DEGRADATION COST
- DELIVERY COST
- PENALTIES
- RISK COST
```

## VPP Architecture

A VPP is treated as a coordinated portfolio capability rather than a single physical generator. It requires qualified resources, forecasting, portfolio state, commitment management, dispatch, M&V, settlement interfaces and participant governance.

## Availability States

Resources may be classified as connected, observable, controllable, qualified, available, reserved, committed, dispatched and delivered. These states must not be conflated.

## Portfolio Risk

Key risks include forecast error, correlated resource failure, communications loss, customer opt-out, asset degradation, market-price exposure, under-delivery and portfolio concentration.

## Control Principles

- Local safety constraints override portfolio optimization.
- Customer participation rights remain explicit.
- Aggregation does not erase asset identity.
- Flexibility claims must include uncertainty.
- Reserved capacity cannot be double committed.
- Delivery obligations must be traceable to underlying resources.

## Definition of Done

This capability is complete when the organization can calculate resource flexibility; qualify it; aggregate resources without losing constraints; forecast portfolio availability; reserve and commit capacity; dispatch portfolios safely; measure delivery; allocate portfolio value; and expose uncertainty and risk.

---

[← Domain 18](./README.md)
